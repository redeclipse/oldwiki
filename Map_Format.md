## Overview

This map format is based on the [Sauerbraten Map Format](http://incoherency.co.uk/interest/sauer_map.html) and does not currently include extensions in Red Eclipse or updates.

The file is organised into several sections, concatenated together and gzip'd to produce a .mpz map file.

-   Header
-   Variables
-   Gameident
-   'Extras'
-   Texture MRU
-   Entities
-   Map geometry (octree)
-   Lightmaps, PVS, blendmap

## File Specifications

Integer values used in this specification are all little-endian.

### Header

A structure containing meta information about the map, including the number of things stored in each section. The structure used in Red Eclipse has been described in this section.

|            |           |                                                                                   |                 |               |
|------------|-----------|-----------------------------------------------------------------------------------|-----------------|---------------|
| Name       | Data Type | Description                                                                       | Example (value) | Example (hex) |
| head       | char\[4\] | 4-byte string indicating what type of file it is. "MAPZ" is used for Red Eclipse. | "MAPZ"          |               |
| version    | int       | Version number                                                                    | 42              | 2a 00 00 00   |
| headersize | int       | Number of bytes in the header.                                                    | 48              | 30 00 00 00   |
| worldsize  | int       | Size of the cube containing the map. This must be a power of 2.                   | 1024            | 00 04 00 00   |
| numents    | int       | Number of entities in the Entities section of the file.                           | 1               | 01 00 00 00   |
| numpvs     | int       | Unknown                                                                           | 0               | 00 00 00 00   |
| lightmaps  | int       | Unknown                                                                           | 0               | 00 00 00 00   |
| blendmap   | int       | Unknown                                                                           | 0               | 00 00 00 00   |
| numvars    | int       | Number of variables in the Variables section of the file.                         | 1               | 01 00 00 00   |

#### Example

|      |         |            |           |         |        |           |          |         |         |          |        |      |     |     |      |     |     |     |     |     |     |     |     |             |             |             |             |
|------|---------|------------|-----------|---------|--------|-----------|----------|---------|---------|----------|--------|------|-----|-----|------|-----|-----|-----|-----|-----|-----|-----|-----|-------------|-------------|-------------|-------------|
| head | version | headersize | worldsize | numents | numpvs | lightmaps | blendmap | numvars | gamever | revision | gameid | MAPZ | 42  | 48  | 1024 | 96  | 0   | 7   | 0   | 79  | 217 | 200 | fps | 4d 41 50 5a | 2a 00 00 00 | 30 00 00 00 | 00 04 00 00 |

### Variables

A series of map variables such as the [skybox](skybox "wikilink"). There are five sections to each variable, listed below.

|               |               |                                                                         |                                                                                                      |                    |
|---------------|---------------|-------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|--------------------|
| Name          | Data Length   | Description                                                             | Example (value)                                                                                      | Example (hex)      |
| type          | 1 byte        | The type of variable stored in value. This may be one of the following: 
                                                                                                          
                                 -   VAR (0) - An int                                                     
                                 -   FVAR (1) - A float                                                   
                                 -   SVAR (2) - A string                                                  | SVAR                                                                                                 | 02                 |
| name length   | 2 bytes       | The length of the variable name that is to come.                        | 6                                                                                                    | 06 00              |
| variable name | defined above | The string representation of the variable, not zero-terminated.         | skybox                                                                                               | 73 6b 79 62 6f 78  |
| value         | VAR           | 4 bytes                                                                 | The value of the variable, or in the case of an SVAR, preceded by length of the string in the value. | 15:ik2k/env/iklake |
| FVAR          | 4 bytes       |
| SVAR          | 2 bytes+      |

### Gameident

This simply specifies what game mode the map is created for. In the case of Red Eclipse can be set to 'fps'.

|        |                                                |       |             |
|--------|------------------------------------------------|-------|-------------|
| name   | Description                                    | Value | Hex         |
| length | The length of the string.                      | 3     | 03          |
| string | The string, including a zero-terminating byte. | fps   | 66 70 73 00 |

### 'Extras'

The documentation on this section is unclear. It appears to be two unsigned shorts of value 0.
