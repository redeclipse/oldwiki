This page was automatically generated from the source of Red Eclipse, please do not edit it manually.

<table style="border:1px solid #000000; width:100%;">
<tr>
<th>
Name & Parameters

</th>
<th>
Description

</th>
<th>
Type

</th>
<th>
Default Value

</th>
<th>
Range

</th>
<th>
Identifier Flags

</th>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>=entattr</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n || \[strcmp \* $arg2\] \[= (entattr $arg1) $arg2\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>=enttype</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n || \[strcmp \* $arg1\] \[strcmp (enttype) $arg1\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>a</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>addbot</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
botoffset (+ $botoffset 1)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>addtip</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n tips = (+ $tips 1)^n \[tip@tips\] = $arg1^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>addvoice</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n voices = (+ $voices 1)^n \[voice@\[voices\]str\] = $arg1^n \[voice@\[voices\]snd\] = (registersound $arg2 255 512 8 $arg3)^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>aiclip</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmat aiclip $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>air</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editmat air $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>alpha</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmat alpha $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>append</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
$arg1 = (concat (getalias $arg1) $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg1</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg10</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg11</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg12</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg13</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg14</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg15</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg16</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg17</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg18</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg19</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg20</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg21</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg22</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg23</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg24</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg25</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg3</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg4</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg5</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg6</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg7</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>arg8</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>arg9</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_ARGS

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>autosave</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if (= $noautosave 0) \[^n savemap^n sleep 600000 \[ autosave \]^n \] \[ noautosave = 0 \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>b</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bb</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to bomber-ball on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: bb futuresport (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
bomber $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bindactions</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n forward backward left right ^"universaldelta 1^" ^"universaldelta -1^" ^"spectator 1^" ^"spectator 0^"^n ^"primary^" ^"secondary^" ^"reload^" ^"use^" ^"jump^" ^"pacing^" ^"crouch^" ^"special^" ^"drop^" ^"affinity^"^n ^"weapon 0^" ^"weapon 1^" ^"weapon 2^" ^"weapon 3^" ^"weapon 4^" ^"weapon 5^" ^"weapon 6^" ^"weapon 7^" ^"weapon 8^" ^"weapon 9^"^n ^"saycommand /^" saytextcommand sayteamcommand toggleconsole edittoggle takescreenshot^n addbot delbot ^"showgui maps 1^" ^"showgui maps 2^" ^"setpriv 1^" ^"showgui loadout^" ^"showgui team^"^n ^"showcompass voice^" ^"showcompass team^"^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bindmod</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n bind $arg1 \[@arg2 1; onrelease \[@@arg2 0\]\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bindnames</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n forward backward left right ^"scroll up^" ^"scroll down^" ^"enter spectator^" ^"exit spectator^"^n ^"primary^" ^"secondary^" ^"reload^" ^"use^" ^"jump^" ^"run/walk^" ^"crouch^" ^"parkour/kick^" ^"drop^" ^"flag/bomb^"^n ^"melee^" ^"pistol^" ^"sword^" ^"shotgun^" ^"smg^" ^"flamer^" ^"plasma^" ^"rifle^" ^"grenade^" ^"rocket^"^n ^"cmd input^" ^"all chat^" ^"team chat^" ^"toggle console^" ^"toggle editing^" ^"screenshot^"^n ^"add bot^" ^"delete bot^" ^"maps menu^" ^"maps voting^" ^"claim privileges^" ^"loadout menu^" ^"team menu^"^n ^"voice compass^" ^"team compass^"^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bindvar</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n bind $arg1 \[@arg2 (= $@arg2 0); if (= $@arg2 0) \[echo @@arg2 OFF\] \[ echo @@arg2 ON\]\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bloom</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n clearpostfx^n if (&gt;= $numargs 1) \[setupbloom 6 $arg1\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bloomshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n defershader 0 $arg1 \[^n forceshader ^"bloom\_scale^"^n forceshader ^"bloom\_init^"^n shader 0 @arg1 \[^n @fsvs^n TEMP tc;^n MOV tc, vertex.texcoord\[0\];^n @@(loopconcat i $arg2 \[concat ^"MUL tc, tc, 0.5; MOV result.texcoord\[^" (+ $i 1) ^"\], tc;^"\])^n END^n \] \[^n @fsps^n TEMP scaled, bloom;^n @@(loopconcat i $arg2 \[^n format \[^n TEX @(if (&gt; $i 0) \[result ^"scaled^"\] \[result ^"bloom^"\]), fragment.texcoord\[%1\], texture\[%1\], RECT;^n @(if (&gt; $i 0) \[result \[^n ADD bloom, bloom, scaled;^n \]\])^n \] (+ $i 1)^n \])^n MAD result.color, bloom, program.env\[0\].x, sample;^n END^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>blur3shader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n lazyshader 0 $arg1 \[^n !!ARBvp1.0^n MOV result.position, vertex.position;^n ADD result.texcoord\[0\], vertex.texcoord\[0\], { @(if $arg2 -0.5 0), @(if $arg3 -0.5 0), 0, 0 };^n ADD result.texcoord\[1\], vertex.texcoord\[0\], { @(if $arg2 0.5 0), @(if $arg3 0.5 0), 0, 0 };^n END^n \] \[^n @fpstart^n TEMP c1, c2;^n TEX c1, fragment.texcoord\[0\], texture\[0\], RECT;^n TEX c2, fragment.texcoord\[1\], texture\[0\], RECT;^n ADD c1, c1, c2;^n MUL result.color, c1, 0.5;^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>blur5shader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n lazyshader 0 $arg1 \[^n @fsvs^n ADD result.texcoord\[1\], vertex.texcoord\[0\], { @(if $arg2 -1.333 0), @(if $arg3 -1.333 0), 0, 0 };^n ADD result.texcoord\[2\], vertex.texcoord\[0\], { @(if $arg2 1.333 0), @(if $arg3 1.333 0), 0, 0 };^n END^n \] \[^n @fpstart^n TEMP c0, c1, c2;^n TEX c0, fragment.texcoord\[0\], texture\[0\], RECT;^n TEX c1, fragment.texcoord\[1\], texture\[0\], RECT;^n TEX c2, fragment.texcoord\[2\], texture\[0\], RECT;^n ADD c1, c1, c2;^n MUL c0, c0, 0.4;^n MAD result.color, c1, 0.3, c0;^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>blurshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n shader 0 $arg1 \[^n !!ARBvp1.0^n MOV result.position, vertex.position;^n MOV result.texcoord\[0\], vertex.texcoord\[0\];^n TEMP tc1, tc2;^n MAD tc1, program.env\[1\], { 1, 1, 0, 0 }, vertex.texcoord\[0\];^n MAD tc2, program.env\[1\], { -1, -1, 0, 0 }, vertex.texcoord\[0\];^n MOV result.texcoord\[1\], tc1;^n MOV result.texcoord\[2\], tc2;^n @(loopconcat i (min (- $arg2 1) 2) \[concatword \[^n ADD tc1.@@arg3, tc1, program.env\[1\].@(at ^"z w^" $i);^n SUB tc2.@@arg3, tc2, program.env\[1\].@(at ^"z w^" $i);^n MOV result.texcoord\[@@(+ (\* $i 2) 3)\], tc1;^n MOV result.texcoord\[@@(+ (\* $i 2) 4)\], tc2;^n \]\])^n END^n \] \[^n @fpstart^n TEMP val, blur1, blur2;^n TEX val, fragment.texcoord\[0\], texture\[0\], @arg4;^n MUL val, val, program.env\[0\].x;^n @(if (&gt; $arg2 3) \[result \[^n TEMP tc1, tc2;^n \]\])^n @(loopconcat i $arg2 \[concatword \[^n @(if (&lt; $i 3) \[result \[^n TEX blur1, fragment.texcoord\[@@(+ (\* $i 2) 1)\], texture\[0\], @@@@arg4;^n TEX blur2, fragment.texcoord\[@@(+ (\* $i 2) 2)\], texture\[0\], @@@@arg4;^n \]\] \[result \[^n ADD tc1, fragment.texcoord\[0\], program.env\[@@(+ $i 0)\];^n SUB tc2, fragment.texcoord\[0\], program.env\[@@(+ $i 0)\];^n TEX blur1, tc1, texture\[0\], @@@@arg4;^n TEX blur2, tc2, texture\[0\], @@@@arg4;^n \]\])^n ADD blur1, blur1, blur2;^n @(if (&lt; $i 3) \[result \[^n MAD @(if (= (+ $i 1) $arg2) \[result ^"result.color^"\] \[result ^"val^"\]), blur1, program.env\[0\].@(at ^"y z w^" $i), val;^n \]\] \[result \[^n MAD @(if (= (+ $i 1) $arg2) \[result ^"result.color^"\] \[result ^"val^"\]), blur1, program.env\[2\].@(at ^"x y z w^" (- $i 3)), val;^n \]\])^n \]\])^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bomber</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to bomber-ball on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: bomber futuresport (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
start $arg1 $modeidxbomber (+ 0 $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>brush\_0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n brushname = \[Circle 1-0 Brush\]^n clearbrush^n brushhandle 0 0; brushverts \[1\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>brush\_1</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n brushname = \[Circle 2-1 Brush\]^n clearbrush^n brushhandle 2 2; brushverts \[^n ^"^"^n ^"0 0 1 ^"^n ^"0 1 2 1 ^"^n ^"0 0 1 ^"^n\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>brush\_2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n brushname = \[Circle 4-2-1 Brush\]^n clearbrush^n brushhandle 2 2; brushverts \[^n ^"0 0 1 ^"^n ^"0 1 2 1 ^"^n ^"1 2 4 2 1 ^"^n ^"0 1 2 1 ^"^n ^"0 0 1 ^"^n\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>brush\_3</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n brushname = \[Square 3x3 brush\]^n clearbrush^n brushhandle 1 1; brushverts \[^n ^"1 1 1 ^"^n ^"1 1 1 ^"^n ^"1 1 1 ^"^n\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>brush\_4</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n brushname = \[Square 5x5 brush\]^n clearbrush^n brushhandle 2 2; brushverts \[^n ^"1 1 1 1 1 ^"^n ^"1 1 1 1 1 ^"^n ^"1 1 1 1 1 ^"^n ^"1 1 1 1 1 ^"^n ^"1 1 1 1 1 ^"^n\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>brush\_5</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n brushname = \[Square 7x7 brush\]^n clearbrush^n brushhandle 3 3; brushverts \[^n ^"1 1 1 1 1 1 1 ^"^n ^"1 1 1 1 1 1 1 ^"^n ^"1 1 1 1 1 1 1 ^"^n ^"1 1 1 1 1 1 1 ^"^n ^"1 1 1 1 1 1 1 ^"^n ^"1 1 1 1 1 1 1 ^"^n ^"1 1 1 1 1 1 1 ^"^n\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>brush\_6</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n brushname = \[Smooth 3x3 brush\]^n clearbrush^n brushhandle 1 1; brushverts \[^n ^"0 0 0 ^"^n ^"0 ^"^n ^"0 ^"^n\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>brush\_7</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n brushname = \[Smooth 5x5 brush\]^n clearbrush^n brushhandle 2 2; brushverts \[^n ^"0 0 0 0 0 ^"^n ^"0 ^"^n ^"0 ^"^n ^"0 ^"^n ^"0 ^"^n\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>brush\_8</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n brushname = \[Smooth 7x7 brush\]^n clearbrush^n brushhandle 3 3; brushverts \[^n ^"0 0 0 0 0 0 0^"^n ^"0 ^"^n ^"0 ^"^n ^"0 ^"^n ^"0 ^"^n ^"0 ^"^n ^"0 ^"^n\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>brush\_9</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n brushname = \[Noise 25x25 Brush\]^n clearbrush^n brushhandle 12 12; brushverts \[^n ^"0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 ^"^n ^"^"^n ^"0 0 0 0 0 0 0 1 0 1 0 0 0 0 0 0 0 0 0 0 1 1 0 1 ^"^n ^"0 0 0 0 0 1 0 0 0 1 0 0 0 0 1 0 1 0 0 1 0 0 2 2 ^"^n ^"0 0 0 0 1 1 1 0 0 0 0 0 1 0 0 0 0 0 0 0 0 0 0 1 1 ^"^n ^"0 0 0 0 0 1 0 0 0 0 0 2 0 0 0 0 1 0 0 0 1 1 0 0 1 ^"^n ^"0 0 1 0 0 0 1 0 1 1 0 0 0 0 1 0 0 1 0 0 0 0 2 ^"^n ^"0 0 0 1 0 1 1 0 0 0 0 0 0 0 0 0 0 1 1 1 2 ^"^n ^"0 0 0 0 0 0 0 1 0 0 0 0 1 0 0 0 0 0 0 0 1 0 0 1 1 ^"^n ^"0 0 0 0 1 1 1 0 0 1 0 0 0 0 0 0 0 0 1 0 0 1 0 1 ^"^n ^"0 1 0 2 0 1 1 1 1 0 0 1 0 0 0 0 1 ^"^n ^"0 0 0 0 2 0 0 0 0 0 0 0 0 0 0 0 1 1 0 1 1 ^"^n ^"1 0 1 0 0 0 0 0 1 0 0 0 1 0 1 ^"^n ^"0 0 0 0 0 0 0 1 1 0 1 1 0 0 1 0 0 1 0 0 0 0 1 0 0 1 ^"^n ^"0 1 1 1 0 3 0 2 0 0 0 1 1 0 0 0 1 1 ^"^n ^"0 0 1 0 0 1 0 0 1 0 1 1 0 1 0 0 0 0 0 1 ^"^n ^"0 0 1 1 0 0 0 0 2 0 0 1 0 0 0 0 0 1 0 0 0 0 0 1 1 ^"^n ^"0 1 1 0 1 0 0 1 0 0 0 0 0 1 0 0 1 1 0 0 0 0 1 ^"^n ^"1 0 0 0 0 0 1 0 0 1 0 0 1 0 0 0 0 0 0 0 1 0 0 1 0 1 ^"^n ^"0 0 0 1 0 0 1 0 1 1 0 0 0 0 0 0 0 1 ^"^n ^"0 0 0 0 0 0 1 1 1 0 1 1 1 0 0 0 0 0 0 0 0 0 0 1 ^"^n ^"0 0 0 0 1 0 1 1 0 2 0 0 0 0 0 1 0 0 0 1 0 0 0 0 1 ^"^n ^"0 0 0 0 0 0 0 0 0 1 0 1 ^"^n ^"0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 ^"^n\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>brushhandle</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n brushx $arg1^n brushy $arg2^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>brushindex</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
-1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>brushmax</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
9

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>brushname</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
Circle 4-2-1 Brush

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>brushverts</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n loop y (listlen $arg1) \[^n bv = (at $arg1 $y)^n loop x (listlen $bv) \[^n brushvert $x $y (at $bv $x)^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>btopt</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
&gt;= (strstr $bumptype $arg1) 0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bumpshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n defershader (if (&gt;= (strstr $arg2 ^"e^") 0) \[result 3\] \[result 1\]) $arg1 \[^n bumpvariantshader @arg1 @arg2^n if (|| (btopt ^"g^") (btopt ^"s^")) \[^n bumpvariantshader @@arg1 (strreplace (concatword @@arg2 ^"i^") ^"r^")^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>bumpvariantshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n bumptype = $arg2^n normtex = (if (btopt ^"e^") \[result ^"texture\[4\]^"\] \[result ^"texture\[3\]^"\])^n glowtex = (if (btopt ^"e^") \[result ^"texture\[5\]^"\] \[result ^"texture\[4\]^"\])^n stype = (if (btopt ^"e^") \[result 3\] \[result 1\])^n if (! (btopt ^"i^")) \[^n if (btopt ^"G^") \[^n defpixelparam ^"glowcolor^" 0 1 1 1 ^n defvertexparam ^"pulseglowspeed^" 4 1 ^n defpixelparam ^"pulseglowcolor^" 5 0 0 0 ^n \] \[if (btopt ^"g^") \[^n defpixelparam ^"glowcolor^" 0 1 1 1 ^n \]\]^n if (btopt ^"S^") \[^n defpixelparam ^"specscale^" 1 6 6 6 ^n \] \[if (btopt ^"s^") \[^n defpixelparam ^"specscale^" 1 1 1 1 ^n \]\]^n if (|| (btopt ^"p^") (btopt ^"P^")) \[^n defpixelparam ^"parallaxscale^" 2 0.06 -0.03 ^n \]^n if (btopt ^"R^") \[^n defpixelparam ^"envscale^" 3 1 1 1 ^n \] \[if (btopt ^"r^") \[^n defpixelparam ^"envscale^" 3 0.2 0.2 0.2 ^n \]\]^n \] \[^n if (btopt ^"s^") \[stype = (+ $stype 8)\]^n \]^n variantshader $stype $arg1 (if (btopt ^"i^") \[result 4\] \[result -1\]) \[^n @vpstart^n ADD result.texcoord\[0\].xy, vertex.texcoord\[0\], program.env\[0\];^n ^n ^n @(if (|| $minimizetcusage (btopt ^"r^")) \[result \[^n MUL result.texcoord\[0\].zw, vertex.texcoord\[1\].wzyx, @lmcoordscale;^n \]\] \[result \[^n MUL result.texcoord\[1\].xy, vertex.texcoord\[1\], @lmcoordscale;^n \]\])^n @fogcoord^n^n @(if (btopt ^"o^") \[result \[^n ATTRIB normal = vertex.normal;^n TEMP camv, tangent, binormal;^n MAD tangent, vertex.color, 2, -1;^n XPD binormal.xyz, normal, tangent;^n MUL binormal.xyz, binormal, tangent.w;^n^n @@(if (btopt ^"t^") \[result \[^n ^n SUB camv.xyz, program.env\[4\], opos;^n DP3 @(if (btopt ^"r^") \[result ^"result.texcoord\[1\].x^"\] \[result ^"result.texcoord\[2\].x^"\]), camv, tangent;^n DP3 @(if (btopt ^"r^") \[result ^"result.texcoord\[1\].y^"\] \[result ^"result.texcoord\[2\].y^"\]), camv, binormal;^n DP3 @(if (btopt ^"r^") \[result ^"result.texcoord\[1\].z^"\] \[result ^"result.texcoord\[2\].z^"\]), camv, normal;^n \]\])^n @@(if (btopt ^"r^") \[result \[^n @@(if (! (btopt ^"t^")) \[result \[^n SUB result.texcoord\[1\].xyz, program.env\[4\], opos;^n \]\])^n^n ^n MOV result.texcoord\[2\].xyz, tangent;^n MOV result.texcoord\[3\].xyz, binormal;^n MOV result.texcoord\[4\].xyz, normal;^n \]\])^n \]\])^n^n @(if (btopt ^"G^") \[result \[^n TEMP pulse, pulsecol;^n MUL pulse, program.env\[6\], @vertexparam4.x;^n FRC pulse, pulse;^n MAD pulse, pulse, 2, -1;^n ABS result.texcoord\[1\].w, pulse.x;^n \]\])^n^n @(if (|| (! (btopt ^"i^")) (btopt ^"s^")) \[result \[^n \#pragma CUBE2\_dynlight^n \]\])^n @(if (! (btopt ^"i^")) \[result \[^n \#pragma CUBE2\_shadowmap^n \#pragma CUBE2\_water^n \]\])^n^n END^n \] \[^n @fpstart^n OPTION ARB\_fog\_linear;^n ATTRIB @(if (|| (btopt ^"p^") (btopt ^"P^")) \[result ^"htc^"\] \[result ^"dtc^"\]) = fragment.texcoord\[0\];^n ATTRIB lmtc = @(if (|| $minimizetcusage (btopt ^"r^")) \[result ^"fragment.texcoord\[0\]^"\] \[result ^"fragment.texcoord\[1\]^"\]);^n @(if (btopt ^"r^") \[result \[^n ATTRIB cam = fragment.texcoord\[1\];^n \]\] \[if (btopt ^"t^") \[result \[^n ATTRIB cam = fragment.texcoord\[2\];^n \]\]\])^n TEMP diffuse, lmc, lmlv, bump;^n^n @(if (|| (! (btopt ^"i^")) (btopt ^"s^")) \[result \[^n TEX lmc, @(if (|| $minimizetcusage (btopt ^"r^")) \[result ^"lmtc.wzyx^"\] \[result ^"lmtc^"\]), texture\[1\], 2D;^n MUL result.color.a, lmc, program.env\[6\];^n TEX lmlv, @(if (|| $minimizetcusage (btopt ^"r^")) \[result ^"lmtc.wzyx^"\] \[result ^"lmtc^"\]), texture\[2\], 2D;^n MAD lmlv.xyz, lmlv, 2, -1;^n \]\])^n^n @(if (btopt ^"t^") \[result \[^n TEMP camvts;^n @(normalize camvts cam)^n \]\])^n^n @(if (btopt ^"p^") \[result \[^n TEMP height;^n TEX height, htc, @@normtex, 2D;^n MAD height.w, height.w, @pixelparam2.x, @pixelparam2.y;^n TEMP dtc;^n MAD dtc.xy, height.w, camvts, htc;^n \]\])^n^n @(if (btopt ^"P^") \[result \[^n PARAM step = -0.142857142857143; ^n TEMP duv, dtc, cc;^n RCP duv.w, camvts.z;^n MUL duv.xyz, duv.w, camvts;^n MUL duv.xyz, duv, step;^n MUL duv.xy, duv, @pixelparam2.x;^n^n MAD dtc.xy, duv, @pixelparam2.y, htc;^n MOV dtc.z, 1.0;^n TEX bump, dtc, @@normtex, 2D;^n^n @@(loopconcat i 7 \[concatword \[^n SLT cc.x, bump.w, dtc.z;^n MAD dtc.xyz, duv, cc.x, dtc;^n TEX bump, dtc, @@normtex, 2D;^n \]\])^n \]\])^n^n @(if (|| (! (btopt ^"i^")) (btopt ^"S^")) \[result \[^n TEX @(if (btopt ^"i^") \[result ^"diffuse.a^"\] \[result ^"diffuse^"\]), dtc, texture\[0\], 2D;^n \]\])^n @(if (! (btopt ^"i^")) \[result \[^n MUL diffuse.rgb, diffuse, program.env\[6\];^n \]\])^n^n @(if (|| (! (btopt ^"i^")) (btopt ^"s^")) \[result \[^n @(if (! (btopt ^"P^")) \[result \[TEX bump, dtc, @normtex, 2D;\]\])^n MAD bump.xyz, bump, 2, -1;^n \]\])^n^n @(if (btopt ^"s^") \[result \[^n PARAM specfactor = @(if (btopt ^"i^") 128 32);^n TEMP he;^n ADD he.xyz, camvts, lmlv;^n @(normalize he he)^n DP3\_SAT he.w, he, bump;^n POW he.w, he.w, specfactor.x;^n @(if (btopt ^"i^") \[result \[MUL\_SAT he.w, he, 64;\]\])^n @(if (btopt ^"S^") \[result \[MUL he.w, he, diffuse;\]\])^n @(if (btopt ^"i^") \[result \[^n MUL diffuse.rgb, he.w, @pixelparam1;^n \]\] \[result \[^n MAD diffuse.rgb, he.w, @pixelparam1, diffuse;^n \]\])^n \]\])^n^n @(if (|| (! (btopt ^"i^")) (btopt ^"s^")) \[result \[^n DP3\_SAT lmlv.w, bump, lmlv;^n MUL lmc.rgb, lmc, lmlv.w;^n MAX lmc.rgb, lmc, program.env\[5\];^n^n @(if (btopt ^"i^") \[result \[^n \#pragma CUBE2\_dynlight lmc^n^n MUL @(if (btopt ^"g^") \[result ^"diffuse.rgb^"\] \[result ^"result.color.rgb^"\]), diffuse, lmc;^n \]\] \[result \[^n \#pragma CUBE2\_shadowmap lmc^n \#pragma CUBE2\_dynlight lmc^n^n MUL @(if (|| (btopt ^"g^") (btopt ^"r^")) \[result ^"diffuse.rgb^"\] \[result ^"result.color.rgb^"\]), diffuse, lmc;^n \]\])^n \]\])^n^n @(if (btopt ^"r^") \[result \[^n TEMP rvec;^n @(if (btopt ^"t^") \[result \[^n TEMP rvects;^n DP3 rvects.w, cam, bump;^n MUL rvects.xyz, rvects.w, bump;^n MAD rvects.xyz, rvects, 2, -cam;^n^n MUL rvec.xyz, rvects.x, fragment.texcoord\[2\];^n MAD rvec.xyz, rvects.y, fragment.texcoord\[3\], rvec;^n MAD rvec.xyz, rvects.z, fragment.texcoord\[4\], rvec;^n \]\] \[result \[^n TEMP bumpw;^n MUL bumpw.xyz, bump.x, fragment.texcoord\[2\];^n MAD bumpw.xyz, bump.y, fragment.texcoord\[3\], bumpw;^n MAD bumpw.xyz, bump.z, fragment.texcoord\[4\], bumpw;^n^n DP3 rvec.w, cam, bumpw;^n MUL rvec.xyz, rvec.w, bumpw;^n MAD rvec.xyz, rvec, 2, -cam;^n \]\])^n^n TEMP reflect;^n TEX reflect, rvec, texture\[3\], CUBE;^n @@(if (btopt ^"R^") \[result \[^n TEMP rmod;^n MUL rmod.rgb, diffuse.w, @pixelparam3;^n \]\] \[result \[^n PARAM rmod = @pixelparam3;^n \]\])^n LRP @(if (btopt ^"g^") \[result ^"diffuse.rgb^"\] \[result ^"result.color.rgb^"\]), rmod, reflect, diffuse;^n \]\])^n^n @(if (btopt ^"g^") \[result \[^n TEMP glow;^n TEX glow, dtc, @@glowtex, 2D;^n @@(if (btopt ^"G^") \[result \[^n TEMP pulsecol;^n LRP pulsecol.rgb, fragment.texcoord\[1\].w, @pixelparam5, @pixelparam0;^n \]\])^n @@(if (btopt ^"i^") \[result \[^n TEMP k;^n MUL glow.rgb, glow, @(if (btopt ^"G^") \[result ^"pulsecol^"\] \[result $pixelparam0\]);^n MAX k.x, glow.r, glow.g;^n MAX k.x, k.x, glow.b;^n MUL k.x, k.x, k.x;^n MUL\_SAT k.x, k.x, 32;^n @(if (btopt ^"s^") \[result \[^n MAD result.color.rgb, k.x, glow, diffuse;^n \]\] \[result \[^n MUL result.color.rgb, k.x, glow;^n \#pragma CUBE2\_variantoverride TEX result.color.a, @(if $minimizetcusage \[result ^"lmtc.wzyx^"\] \[result ^"lmtc^"\]), texture\[1\], 2D;^n MOV result.color.a, program.env\[6\];^n \]\])^n \]\] \[result \[^n MAD result.color.rgb, glow, @(if (btopt ^"G^") \[result ^"pulsecol^"\] \[result $pixelparam0\]), diffuse;^n \]\])^n \]\])^n^n @(if (! (btopt ^"i^")) \[result \[^n \#pragma CUBE2\_water^n \]\])^n^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>bv</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0 0 1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>campaign</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>capture</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to capture-the-flag on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: capture bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxcapture (+ 0 $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>causticshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n lazyshader 0 $arg1 \[^n @vpstart^n DP3 result.texcoord\[0\].x, opos, program.env\[0\];^n DP3 result.texcoord\[0\].y, opos, program.env\[1\];^n @fogcoord^n END^n \] \[^n @fpstart^n OPTION ARB\_fog\_linear;^n @arg2^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>cdm</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to coop deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: cdm bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
coop $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>changeoutline</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n outlinestatus = (mod (+ $arg1 $outlinestatus) (listlen $outlinecolours))^n if (&lt; $outlinestatus 0) \[^n outlinestatus = (+ (listlen $outlinecolours) $outlinestatus ) ^n \]^n^n if (=s (at $outlinecolours $outlinestatus) ^"OFF^") \[^n echo ^"Outline OFF^"^n outline 0^n \] \[^n echo (concat ^"Outline^" (at $outlinecolours $outlinestatus))^n outline 1^n outlinecolour @(at $outlinecolours $outlinestatus)^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>chatconblendstorage</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>checkboxdesc</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if (= $arg2 1) \[^n guitext (format ^"^^fa^^f(textures/checkboxtwo) %1^" $arg1)^n \] \[^n guitext (format ^"^^fa^^f(textures/checkboxon) %1 ^^f(textures/checkboxtwo) %2^" $arg1 $arg2)^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>classic</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to classic deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to a bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: classic bath (+ $mutsbitinstagib $mutsbitduel)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxdeathmatch (+ $mutsbitclassic $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>clearents</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if $editing \[^n entcancel^n entselect \[ =enttype $arg1 \];^n echo Deleted (enthavesel) $arg1 entities;^n delent^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>clip</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmat clip $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>cloudalpha</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
cloudblend $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>colour</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
playercolour $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>colrval</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>combine</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n MAD invfresnel.x, invfresnel.x, 0.5, 0.5;^n LRP result.color.rgb, invfresnel.x, refract, reflect;^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>conblendstorage</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>coop</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to coop deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: coop bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxdeathmatch (+ $mutsbitcoop $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>corners</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
selectcorners 1; dragging 1; onrelease \[ selectcorners 0; dragging 0 \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>crosshairindex</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>crosshairlist</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>crosshairname</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>crosshairs</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>crosshairsboxlen</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>ctf</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to capture-the-flag on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: ctf bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
capture $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>curbrush</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>curcrosshair</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>curtip</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
press ^fs^fcSPACE^fS to ^fs^fyjump^fS and again in mid-air to ^fs^fypropel^fS yourself

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>death</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editmat death $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>deathmatch</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: deathmatch bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxdeathmatch (+ 0 $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>defaultmodifier</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>defend</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to defend-the-flag on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: defend bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxdefend (+ 0 $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delbot</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
botoffset (- $botoffset 1)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_edit\_0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n if $blendpaintmode \[^n nextblendbrush $arg1^n echo (concatword ^"^^fgblend brush:^^fw ^" (getblendbrushname (curblendbrush)))^n \] \[^n editfacewentpush $arg1 1^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delta\_edit\_1</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
nodebug \[ gridpower (+ $arg1 $gridpower) \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_edit\_10</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
entautoview $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delta\_edit\_11</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
entproperty 0 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_edit\_12</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
entproperty 1 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delta\_edit\_13</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
entproperty 2 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_edit\_14</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
entproperty 3 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delta\_edit\_15</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
entproperty 4 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_edit\_16</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
entproperty 5 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delta\_edit\_17</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
entproperty 6 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_edit\_18</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
entproperty 7 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delta\_edit\_19</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
entproperty 8 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_edit\_2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editfacewentpush $arg1 0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delta\_edit\_3</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editfacewentpush $arg1 2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_edit\_4</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editrotate $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delta\_edit\_5</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
entproperty 0 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_edit\_6</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
edittex $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delta\_edit\_9</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
selectbrush $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_game\_0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
if (iszooming) \[ setzoom $arg1 \] \[ weapon -1 $arg1 \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>delta\_spec\_0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
followdelta $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>delta\_wait\_0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
followdelta $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>deltastates</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^"game^" ^"dead^" ^"edit^" ^"spec^" ^"wait^"

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>demo</b> <i>&lt;demo&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
starts playback of a given demo

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
stopdemo; start $arg1 0 0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>demofavs</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_PERSIST

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>distort</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n TEMP reflect, refract, fade;^n^n MAD temp.xy, dudv, 0.4, projtc;^n MOV temp.zw, projtc;^n TXP refract, temp, texture\[3\], 2D;^n TXP fade.a, projtc, texture\[3\], 2D;^n MAD result.color.a, fade.a, 4, projtc.z;^n^n MAD temp.xy, dudv, 0.025, tc2;^n TEX bump, temp, texture\[1\], 2D;^n MAD bump.xyz, bump, 2, -1;^n^n TEMP rvec;^n DP3\_SAT invfresnel.x, cam, bump;^n MUL rvec.xyz, invfresnel.x, bump;^n MAD rvec.xyz, rvec, 2, -cam;^n TEX reflect, rvec, texture\[0\], CUBE;^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>dm</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: dm bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
deathmatch $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>domodifier</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifier = $arg1; onrelease \[ modifier = $defaultmodifier \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>drag</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
dragging 1; onrelease \[ dragging 0 \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>dtf</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to defend-the-flag on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: defend bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
defend $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>duel</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to duel deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to a bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: duel bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
start $arg1 $modeidxdeathmatch (+ $mutsbitduel $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>edit</b> <i>&lt;map&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
starts editing on a new map file named "mapname.mpz" or loads mapname.mpz if it already exists

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxediting (+ $mutsbitffa $mutsbitclassic $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>editbindmod</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n editbind $arg1 \[@arg2 1; onrelease \[@@arg2 0\]\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>editbindvar</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n editbind $arg1 \[@arg2 (= $@arg2 0); if (= $@arg2 0) \[echo @@arg2 OFF\] \[ echo @@arg2 ON\]\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>editcopy</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if (|| \[havesel\] \[! (enthavesel)\]) \[^n entcopybuf = ^"^"^n entcopy^n copy^n \] \[^n entcopybuf = (entget)^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>editcut</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n hadselection = (havesel)^n moving 1^n if $moving \[^n copy; entcopy^n delcube; delent^n onrelease \[^n moving 0^n paste^n entpaste^n if ( ! $hadselection ) \[ cancelsel \]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>editdel</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
if (= (enthavesel) 0) \[ delcube \] \[ delent \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>editdrag</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
cancelsel; || \[entdrag\] \[ drag \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>editextend</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
|| \[entdrag\] \[ selextend; reorient; editmove \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>editfacewentpush</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n if (|| \[havesel\] \[! (enthavesel)\] ) \[^n if $moving \[^n pushsel $arg1^n \] \[^n entcancel^n editface $arg1 $arg2^n \]^n \] \[^n if $entmoving \[ entpush $arg1 \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>editflip</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
if (= (enthavesel) 0) \[ flip \] \[ entflip \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>editmove</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
moving 1; onrelease \[ moving 0 \]; result $moving

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>editmovecorner</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editmovewith selcorners

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>editmovedrag</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmovewith editdrag

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>editmovewith</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if (havesel) \[^n || \[editmove\] \[ @arg1 \]^n onrelease \[ moving 0; dragging 0 \]^n \] \[^n @arg1^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>editpaste</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n cancelpaste = (! (|| \[enthavesel\] \[havesel\]));^n if (strcmp ^"^" $entcopybuf) \[^n pastehilight^n onrelease \[^n if $opaquepaste delcube^n paste^n entpaste^n if $cancelpaste \[ cancelsel \]^n \]^n \] \[^n entreplace^n if $cancelpaste \[ cancelsel \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>editrotate</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n rotate $arg1^n entrotate $arg1^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>efuiattr0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>efuiattr1</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>efuiattr2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>efuiattr3</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>efuiattr4</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>efuidoattr0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>efuidoattr1</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>efuidoattr2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>efuidoattr3</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>efuidoattr4</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>efuidotype</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>efuiinsel</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>efuimatch</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n match = 1^n if (&& $efuiinsel $match) \[^n if (= $efuiinsel 1) \[^n match = (insel)^n \] \[^n match = (! (insel))^n \]^n \]^n if (&& $efuidotype $match) \[^n match = (strcmp (enttype) (at $enttypelist $efuitype))^n \]^n loop i 5 \[^n if (&& $\[efuidoattr@i\] $match) \[^n match = (= (entattr $i) $\[efuiattr@i\])^n \]^n \]^n result $match^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>efuitype</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>efuitypename</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>entadd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
entaddmove; entmoving 0;

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>entaddmove</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
entmoving 2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>entattributes</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guitext type^n guislider tmp0 0 3 entupdate^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>entcomplete</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
listcomplete $arg1 $enttypelist

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>entcopybuf</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>entdrag</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
entaddmove; onrelease \[entmoving 0\]; result $entmoving

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>entfind</b> <i>&lt;type&gt; &lt;properties...&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
selects all entities of a specific type and optionally with specific properties, using "1" as type selects all entities

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if (= $numargs 0) \[^n entselect 1^n \] \[^n entselect (concat \[ && \[=enttype @@arg1\] \] (loopconcat i (- $numargs 1) \[^n result \[ \[=entattr @@i @@\[arg@(+ $i 2)\]\] \]^n \]))^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>entfindinsel</b> <i>&lt;type&gt; &lt;properties...&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
selects all entities, within the selected area, of a specific type and optionally with specific properties, using "1" as type selects all entities

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n if (= $numargs 0) \[^n entselect \[ insel \]^n \] \[^n entselect (concat \[ && \[insel\] \[=enttype @@arg1\] \] (loopconcat i (- $numargs 1) \[^n result \[ \[=entattr @@i @@\[arg@(+ $i 2)\]\] \]^n \]))^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>entmodify</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n entattr $arg1 (+ (entattr $arg1) $arg2)^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>entproperty</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n entprop $arg1 $arg2^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>entreplace</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n do \[^n if (enthavesel) \[\] \[ newent @entcopybuf \]^n entset @entcopybuf^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>entswithdirection</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^"playerstart 0^" ^"mapmodel 1^" ^"teledest 0^" ^"camera 0^"

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>enttoggle</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
entmoving 1; entmoving 0;

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>enttypelist</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n light^n mapmodel^n playerstart^n envmap^n particles^n sound^n lightfx^n sunlight^n weapon^n teleport^n actor^n trigger^n pusher^n affinity^n checkpoint^n dummy1^n dummy2^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>enttypeselect</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n enttypelength = (listlen $enttypelist)^n next = (mod (+ (indexof $enttypelist (enttype)) $arg1) $enttypelength)^n if (&lt; $next 0) \[ next = (+ $next $enttypelength) \]^n do \[entset @(listsplice (entget) (at $enttypelist $next) 0 1)\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>entupdate</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
entset $tmpt $tmp0 $tmp1 $tmp2 $tmp3

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>explosionshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n shader 0 $arg1 \[^n !!ARBvp1.0^n ATTRIB opos = vertex.position;^n OUTPUT spos = result.position;^n^n TEMP wobble; ^n DP3 wobble.w, opos, program.env\[0\]; ^n MAD wobble.w, program.env\[1\].w, 0.002, wobble.w; ^n FRC wobble.w, wobble.w; ^n SUB wobble.w, wobble.w, 0.5; ^n ABS wobble.w, wobble.w; ^n MUL wobble.w, wobble.w, 0.5; ^n^n MAD wobble.xyz, wobble.w, opos, opos;^n MOV wobble.w, opos.w;^n^n @(if (&gt;= (strstr $arg1 ^"soft^") 0) \[result \[^n TEMP projtc;^n DP4 projtc.x, state.matrix.mvp.row\[0\], wobble;^n DP4 projtc.y, state.matrix.mvp.row\[1\], wobble;^n DP4 projtc.z, state.matrix.mvp.row\[2\], wobble;^n DP4 projtc.w, state.matrix.mvp.row\[3\], wobble;^n MOV spos, projtc;^n^n DP4 projtc.z, state.matrix.modelview.row\[2\], -wobble;^n MAD projtc.z, projtc, program.env\[5\].x, program.env\[5\].y;^n ADD projtc.xy, projtc, projtc.w;^n MUL projtc.xy, projtc, program.env\[6\];^n MOV result.texcoord\[3\], projtc;^n \]\] \[result \[^n DP4 spos.x, state.matrix.mvp.row\[0\], wobble;^n DP4 spos.y, state.matrix.mvp.row\[1\], wobble;^n DP4 spos.z, state.matrix.mvp.row\[2\], wobble;^n DP4 spos.w, state.matrix.mvp.row\[3\], wobble;^n \]\])^n^n MOV result.color, vertex.color;^n^n @arg2^n^n @fogcoord^n END^n \] \[^n @fpstart^n OPTION ARB\_fog\_linear;^n TEMP dtc, diffuse, blend;^n^n TEX dtc, @arg3, texture\[0\], 2D;^n MAD dtc.xy, dtc, 0.1, fragment.texcoord\[0\]; ^n TEX diffuse, dtc, texture\[0\], 2D;^n^n TEX blend, fragment.texcoord\[1\], texture\[1\], 2D; ^n^n @(if (&gt;= (strstr $arg1 ^"glare^") 0) \[result \[^n TEMP k;^n MUL k.x, blend.a, blend.a;^n MUL diffuse.rgb, diffuse, 8;^n ADD diffuse.b, diffuse, k.x;^n MUL diffuse, diffuse, k.x;^n \]\] \[result \[^n MAD diffuse, diffuse, 4, { 0, 0, -0.5, 0 }; ^n MAD diffuse, diffuse, blend.a, { 0, 0, 0.5, 0 }; ^n \]\])^n^n @(if (&gt;= (strstr $arg1 ^"soft^") 0) \[result \[^n MUL result.color.rgb, diffuse, fragment.color;^n^n TEMP depth;^n TXP depth, fragment.texcoord\[3\], texture\[2\], @(if (&gt;= (strstr $arg1 ^"rect^") 0) \[result ^"RECT^"\] \[result ^"2D^"\]);^n @(if (&gt;= (strstr $arg1 ^"soft8^") 0) \[result \[^n DP4 depth.x, depth, program.env\[6\];^n SUB\_SAT depth.x, depth.x, fragment.texcoord\[3\].z;^n \]\] \[result \[^n MAD\_SAT depth.x, depth.x, program.env\[5\].z, -fragment.texcoord\[3\].z;^n \]\])^n MUL depth.x, depth.x, fragment.color.a;^n MAX depth.x, depth.x, program.env\[5\].w;^n MUL result.color.a, diffuse.a, depth.x;^n \]\] \[result \[^n MUL result.color, diffuse, fragment.color;^n \]\])^n^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>fdm</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
ffa $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>ffa</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
start $arg1 $modeidxdeathmatch (+ $mutsbitffa $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>fogcoord</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n DP4 result.fogcoord, -opos, state.matrix.modelview.row\[2\];^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>fov</b> <i>&lt;angle&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
determines the size of the field of view in first or third person mode, depending on the current camera mode

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
do \[ @(? (isthirdperson) third first)personfov @arg1 \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>fpopts</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n OPTION ARB\_precision\_hint\_fastest;^n ^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>fpstart</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n !!ARBfp1.0^n ^n OPTION ARB\_precision\_hint\_fastest;^n ^n^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>fsps</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n ^n !!ARBfp1.0^n ^n OPTION ARB\_precision\_hint\_fastest;^n ^n^n^n TEMP sample;^n TEX sample, fragment.texcoord\[0\], texture\[0\], RECT;^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>fsvs</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n !!ARBvp1.0^n MOV result.position, vertex.position; ^n MOV result.texcoord\[0\], vertex.texcoord\[0\];^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>gauntlet</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to gauntlet on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: gauntlet bath (+ $mutsbitjetpack $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxgauntlet (+ 0 $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>genentattributes</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n entattributes = ^"^"^n n = (listlen $arg2)^n loop i $n \[^n entattributes = (concat $entattributes \[^n guitext @(at $arg2 $i)^n guislider tmp@i @(at $arg3 (\* 2 $i)) @(at $arg3 (+ 1 (\* 2 $i))) entupdate^n \])^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>glarepreset</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>glareworldshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n variantshader (if (&lt; (strstr $arg1 ^"env^") 0) 0 2) $arg1 4 \[^n @vpstart^n ADD result.texcoord\[0\].xy, vertex.texcoord\[0\], program.env\[0\];^n MUL result.texcoord\[1\].xy, vertex.texcoord\[1\], @lmcoordscale;^n^n @arg2^n^n @fogcoord^n^n END^n \] \[^n @fpstart^n OPTION ARB\_fog\_linear;^n^n @arg3^n^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>glass</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmat glass $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>glass2</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editmat glass2 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>glass3</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmat glass3 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>glass4</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editmat glass4 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>grabbing</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>gridbindswitch</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>guiarea</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n guilist \[^n if (&gt; $numargs 9) arg10^n guilist \[^n \[@\[arg1\]count\] = $arg2^n \[@\[arg1\]disp\] = 0^n \[@\[arg1\]list\] = 0^n guilist \[^n guistrut 0.5^n guistrut $arg3 1^n if (arg5) \[^n \[@\[arg1\]num\] = $arg6^n if (&gt; $\[@\[arg1\]num\] 0) \[^n \[@\[arg1\]index\] = (min (max 0 (- $\[@\[arg1\]num\] $\[@\[arg1\]count\])) $\[@\[arg1\]index\]) ^n loop i $\[@\[arg1\]num\] \[^n arg7^n if (arg8) \[^n if (&& (&gt;= $i $\[@\[arg1\]index\]) (&lt; $\[@\[arg1\]list\] $\[@\[arg1\]count\])) \[^n if (&gt; $numargs 10) arg11^n \[@\[arg1\]list\] = (+ $\[@\[arg1\]list\] 1)^n \]^n \[@\[arg1\]disp\] = (+ $\[@\[arg1\]disp\] 1)^n \]^n \]^n \] \[guistrut (-f (\*f $arg4 $arg2) 1); arg9; \[@\[arg1\]list\] = $arg2\]^n \] \[guistrut (-f (\*f $arg4 $arg2) 1); arg9; \[@\[arg1\]list\] = $arg2\]^n \[@\[arg1\]alts\] = (- $\[@\[arg1\]count\] $\[@\[arg1\]list\])^n if (&gt; $\[@\[arg1\]alts\] 0) \[guistrut (\*f $\[@\[arg1\]alts\] $arg4)\]^n \]^n guistrut 2^n guislider \[@\[arg1\]index\] 0 (max (- $\[@\[arg1\]disp\] $\[@\[arg1\]count\]) 0) \[\] 1 1^n \]^n arg12^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>guibox</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guispring 1^n guilist \[^n guilist \[^n guispring 1^n guilist \[^n guispring 1^n arg1^n guispring 1^n \]^n guispring 1^n \]^n guistrut 2^n guilist \[^n guispring 1^n guistrut 50 1^n arg2^n guispring 1^n arg3^n \]^n \]^n guispring 1^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>guicenter</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
guilist \[ guispring 1; arg1; guispring 1 \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>guicheckbox2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guistayopen \[ guibutton $arg1 \[case $@arg2 0 \[@@arg2 1\] 1 (? @arg3 \[@@arg2 2\] \[@@arg2 0\]) 2 \[@@arg2 0\]\] \[\] (case $$arg2 0 \[result ^"checkbox^"\] 1 \[result ^"checkboxon^"\] 2 \[result ^"checkboxtwo^"\]) \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>guicontainer</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
guilist \[ guilist \[ if (arg1) \[arg2\] \[arg3\] \] \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>guilistloop</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n i = 0^n j = (+ (div $arg3 (\* $arg1 $arg2)) 1)^n loop a $j \[^n if (&gt; $a 0) \[ guitab $a \]^n guilist \[^n loop b $arg1 \[^n guilist \[^n loop c $arg2 \[^n if (&lt; $i $arg3) \[^n arg4^n i = (+ $i 1)^n if (&lt; $c (- $arg2 1)) \[ guibar \]^n \]^n \]^n \]^n if (&& (&lt; $i $arg3) (&lt; $b (- $arg1 1))) \[ guibar \]^n \]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>guilistsplit</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n guilist \[^n gli = 0^n gll = (listlen $arg3)^n glz = (div (+ $gll (- $arg2 1)) $arg2)^n loop gla $arg2 \[^n guilist \[^n glt = (min (+ $gli $glz) $gll)^n while \[&lt; $gli $glt\] \[^n $arg1 = (at $arg3 $gli)^n arg4^n gli = (+ $gli 1)^n \]^n \]^n if (&lt; (+ $gla 1) $arg2) \[arg5\]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>guiloopsplit</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guilist \[^n gli = 0^n glz = (div (+ $arg3 (- $arg2 1)) $arg2)^n loop gla $arg2 \[^n guilist \[^n glt = (min (+ $gli $glz) $arg3)^n while \[&lt; $gli $glt\] \[^n $arg1 = $gli^n arg4^n gli = (+ $gli 1)^n \]^n \]^n if (&lt; (+ $gla 1) $arg2) \[arg5\]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>guimerge</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
guibody \[guilist \[guilist \[guistrut $arg1\]; guilist \[arg2\]\]\] $arg3 $arg4

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>guimodes</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guicenter \[ guitext (modedesc @arg1 @arg2 5) \]^n if (&gt; $arg2 0) \[^n loop i $mutsidxnum \[^n mut = (&lt;&lt; 1 $i)^n if (&& \[& $arg2 $mut\] \[! (& (mutsimplied $arg1) $mut)\]) \[^n muttxt = (mutsdesc $arg1 $mut 4)^n if (strlen $muttxt) \[ guicenter \[ guitext (concatword ^"^^fa^" $muttxt) \] \]^n \]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>guipage</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
guistayopen \[guiarea $arg1 $arg2 $arg3 $arg4 $arg5 $arg6 $arg7 $arg8 $arg9 $arg10 $arg11 $arg12\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>guiradio2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guistayopen \[ guibutton $arg1 \[@arg2 @arg3\] \[\] (? (= $$arg2 $arg3) ^"radioboxon^" ^"radiobox^") \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>guiright</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
guilist \[ guispring 1; arg1 \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>guitip</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n nonworld \[^n guistayopen \[^n guicenter \[^n guibody \[^n guilist \[^n guifont ^"reduced^" \[ guitext ^"TIP: ^" \]^n guifont ^"little^" \[ guitext (format ^"^^fa%1^" (? (&gt; @@@@@numargs 0) \[@@@@@arg1\] (showtip))) \]^n \]^n \] \[lasttip = 0\] \[lasttip = 0\]^n \]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>i</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>initentgui</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n tmpt = (enttype)^n ^n tmp0 = (entattr 0)^n ^n tmp1 = (entattr 1)^n ^n tmp2 = (entattr 2)^n ^n tmp3 = (entattr 3)^n ^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>insta</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to instagib deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: insta bath (+ $mutsbitduel $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
instagib $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>instagib</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to instagib deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: instagib bath (+ $mutsbitduel $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
start $arg1 $modeidxdeathmatch (+ $mutsbitinstagib $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>ircchan0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>irchost0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>ircident</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>ircname0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>ircnick0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>ircport0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>j</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>kaboom</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to kaboom deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to a bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: kaboom bath (+ $mutsbitinstagib $mutsbitjetpack)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
start $arg1 $modeidxdeathmatch (+ $mutsbitkaboom $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>ladder</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmat ladder $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>lastmode</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
-1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>lastmuts</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>lasttip</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>lava</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmat lava $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>lava2</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editmat lava2 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>lava3</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmat lava3 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>lava4</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editmat lava4 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>lazyshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n defershader $arg1 $arg2 \[^n shader @arg1 @arg2 \[@@arg3\] \[@@arg4\]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>lightcmd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n lightr = (at $lightrgb 0)^n lightg = (at $lightrgb 1)^n lightb = (at $lightrgb 2)^n if (! $lightbright) \[^n if (=s $lightrgb ^"255 255 255^") \[^n lightr = 192; lightg = 192; lightb = 192^n \] \[^n lightr = (div $lightr 2); lightg = (div $lightg 2); lightb = (div $lightb 2)^n \]^n \]^n result (concat newent light $lightradius $lightr $lightg $lightb)^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>lmcoordscale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
float alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
3.051851e-05

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>lms</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to survivor deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to a bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: lms bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
survivor $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>loadsky</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n skybox $arg1^n if (&gt; $numargs 1) \[spinsky $arg2\]^n if (&gt; $numargs 2) \[yawsky $arg3\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>loadweapall</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_PERSIST

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>loadweaplist</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>loadweaprespawn</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_PERSIST

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>loadweaps</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n lwa = ^"^"^n lwo = (? (&gt; (listlen $loadweaplist) $arg1) (at $loadweaplist $arg1) 0)^n loop w2 (min (listlen $loadweaplist) $weapidxloadout) \[^n if (= $w2 $arg1) \[^n lwa = (? $w2 (concat $lwa $arg2) $arg2)^n \] \[^n w3 = (? (&gt; (listlen $loadweaplist) $w2) (at $loadweaplist $w2) 0)^n if (&& $w3 (= $arg2 $w3)) \[ w3 = $lwo \]^n lwa = (? $w2 (concat $lwa $w3) $w3)^n \]^n \]^n if (listlen $lwa) \[ loadweaplist = $lwa \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>loadweapsave</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>lse</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n line = ^"^"^n count = 0^n entloop \[^n line = ( concatword $line (entget) ^" ^" )^n count = ( + $count 1 )^n if (&gt; $count 4) \[^n echo $line^n line = ^"^"^n count = 0^n \]^n \]^n if (&gt; $count 0 ) \[ echo $line \]^n echo (enthavesel) entities selected^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>m</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>macro</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
$arg1 = (concat \[format \[@@arg2\]\] (loopconcat i $numargs \[result \[$arg@(+ $i 1)\]\]))

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mapcomplete</b> <i>&lt;command&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
enables map completion for a given command or alias; this enables tab-completion for the first argument of an already existing command or alias, the completion uses files that ends with 'mpz' in the 'maps' folders of the game's homedir, and its data dir(s)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
setcomplete $arg1 1; complete $arg1 maps mpz

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mapcur</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mapextra</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mapfavs</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_PERSIST

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mapimg</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mapindex</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>maplist</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>maplists</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
campaignmaps mainmaps capturemaps defendmaps bombermaps trialmaps

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mapmodelnum</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mapmsg</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
maptitle $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mapnum</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
-1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mapocta</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mappath</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mappth</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mapselected</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mapsexec</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n sleep 1 \[^n if (isconnected) \[ showgui maps 2 \]^n start @arg1 @arg2 @arg3^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mapsmenu</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guilist \[^n guistrut 74 1^n guitip (format ^"press ^^fs^^fc%1^^fS to open this menu at any time^" (searchbinds ^"showgui maps 1^" 5 ^"or^" ^"^^fw^"))^n guistrut 0.5^n guilist \[^n guilist \[^n guilist \[^n guistrut 3 1^n guilist \[^n if (&lt; $lastmode 0) \[^n guitext ^"game select^"^n guifont ^"little^" \[ guitext ^"please select a mode and map to continue^" \]^n \] \[^n gname = (gamename $modeselected $mutsselected 0 32)^n guilist \[^n guitext $gname^n if (= $modeselected $modeidxdemo) \[^n dinfo = (demoscan (format ^"%1.dmo^" $mappth))^n dmode = (demoinfo $dinfo 3)^n dmuts = (demoinfo $dinfo 4)^n dname = (gamename $dmode $dmuts 0 32)^n \]^n \]^n guilist \[^n guitext ^" ^^faselected on ^";^n guitext $mapcur^n if (= $modeselected $modeidxdemo) \[^n dinfo = (demoscan (format ^"%1.dmo^" $mappth))^n dmapname = (demoinfo $dinfo 2)^n guifont ^"little^" \[ guitext (format ^" (%1)^" $dmapname) \]^n \]^n \]^n \]^n \]^n \]^n guilist \[^n guilist \[^n guitext ^"mode^"^n guistrut 0.5^n guifont ^"little^" \[^n loop z $modeidxnum \[^n modevar (at $modename $z) modeselected mutsselected $z mapcur^n \]^n \]^n \]^n guistrut 3^n guilist \[^n guistayopen \[^n guiimage $mapimg \[if (&gt;= @lastmode 0) \[ mapsexec @mapcur @modeselected @mutsselected \]\] 5 1 ^"textures/emblem^"^n \]^n \]^n \]^n guistrut 0.5^n guifont ^"reduced^" \[^n guilist \[^n guitext ^"mutators^"^n guispring^n guistayopen \[ guibutton ^"^^fyreset selection^" \[ mutsselected = (mutscheck $modeselected 0) \] \]^n guispring^n \]^n \]^n guistrut 0.5^n guifont ^"little^" \[^n cnt = (- $mutsidxnum $mutsidxgsn)^n guiloopsplit n 3 $cnt \[^n mutsvar (at $mutsname $n) modeselected mutsselected (&lt;&lt; 1 $n) mapcur^n \] \[ guistrut 3 \]^n \]^n if (&gt; (strlen (gspmutname $modeselected 0)) 0) \[^n guistrut 0.5^n guifont ^"little^" \[ guitext ^"mode specific^" \]^n guistrut 0.5^n guifont ^"little^" \[^n guiloopsplit n 3 $mutsidxgsn \[^n mut = (gspmutname $modeselected $n)^n if (strlen $mut) \[^n mutsvar $mut modeselected mutsselected (&lt;&lt; 1 (+ $mutsidxgsp $n)) mapcur^n \]^n \] \[ guistrut 3 \]^n \]^n \]^n \]^n guistrut 1^n mapscount = 21^n guilist \[^n guilist \[^n guitext ^"available maps^"^n if (&gt; $hasoctapaks 0) \[^n guispring^n guistayopen \[^n guibutton ^"show sauer maps^" \[^n mapocta = (! $mapocta)^n resetmapgui = 1^n \] \[\] (? (&gt; $mapocta 0) ^"checkboxon^" ^"checkbox^")^n \]^n guispring 1^n guitext ^"fav^"^n guistrut 3^n \]^n \]^n guistrut 0.25^n guilist \[^n guifont ^"little^" \[^n guicontainer \[&gt;= $lastmode 0\] \[^n nummaps = (- (listlen $maplist) 1)^n guilist \[^n guilist \[^n guistrut $mapscount 1^n mapindex = (min (max 0 (- $nummaps $mapscount)) $mapindex) ^n mapnum = (min $mapnum $nummaps)^n guilist \[^n guistrut 37 1^n break = 0^n loopwhile i $mapscount \[= $break 0\] \[^n q = (+ $mapindex $i)^n curmap = (at $maplist $q)^n cases $curmap ^"\*^" \[^n guifont ^"little^" \[ guitext ^"maps not in the rotation^" \]^n \] ^"~^" \[^n guifont ^"little^" \[ guitext ^"maps played recently^" \]^n \] ^".^" \[^n guifont ^"little^" \[ guitext ^"maps from sauerbraten^" \]^n \] ^"?^" \[^n break = 1^n \] () \[^n guilist \[^n guiradio $curmap mapnum $q^n guispring 1^n guistayopen \[^n hasmap = (&gt;= (indexof (? (= $modeselected $modeidxdemo) $demofavs $mapfavs) $curmap) 0)^n guiimage (? $hasmap ^"textures/checkboxon^" ^"textures/checkbox^") \[^n if (= $modeselected $modeidxdemo) \[^n demofavs = (? @@hasmap (listdel $demofavs @@curmap) (concat (listdel $demofavs @@curmap) @@curmap))^n \] \[^n mapfavs = (? @@hasmap (listdel $mapfavs @@curmap) (concat (listdel $mapfavs @@curmap) @@curmap))^n \]^n resetmapgui = 1^n \] 0.5 0 ^"textures/blank^"^n \]^n \]^n \]^n \]^n \]^n \]^n guilist \[ guifont ^"little^" \[ guitext ^"^^custom map^" \] \]^n guilist \[^n guiradio ^"^" mapnum $nummaps^n mapextraval = $mapextra^n guifield mapextraval 36 \[mapextra = $mapextraval\]^n \]^n \]^n guislider mapindex 0 (max (- $nummaps $mapscount) 0) \[\] 1 1^n \] \[^n guistrut 40^n guistrut (+f $mapscount 3.5) 1^n \]^n \]^n \]^n \]^n \]^n guistrut 0.25^n guilist \[^n if (&gt;= $lastmode 0) \[^n guispring 1^n guifont ^"super^" \[^n guistayopen \[ guibutton (? (isonline) ^"^^fgsubmit vote^" ^"^^fgstart game^") \[ mapsexec $mapcur $modeselected $mutsselected \] \]^n \]^n guistrut 15^n \] \[guistrut 1\]^n \]^n guistrut 0.25^n guilist \[^n guistrut 0.5^n guilist \[^n guifont ^"small^" \[^n act = (? (strlen $guirolloverimgaction) $guirolloverimgaction $guirolloveraction)^n cases (at $act 0) ^"modeselected^" \[^n guitext (format ^"%1^" (modedesc (at $act 2) $mutsselected 3))^n \] ^"mutate^" \[^n guitext (format ^"%1^" (mutsdesc $modeselected (at $act 2) 3))^n \] ^"implied^" \[^n guitext ^"this mutator is implied in the current configuration^"^n \] ^"disabled^" \[^n guitext ^"this mutator is disabled in the current configuration^"^n \] () \[guitext ^"hover over a mode or mutator to see its description^"\]^n \]^n \]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mapsmenuinit</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n if (isconnected) \[^n modeselected = (gamemode)^n if (&lt; (mutators) 0) \[ mutsselected = 0 \] \[ mutsselected = (mutscheck $modeselected (mutators)) \]^n \] \[^n modeselected = -1^n mutsselected = 0^n \]^n mapindex = 0^n lastmode = -1^n lastmuts = 0^n mapnum = -1^n mapcur = ^"^"^n mappth = ^"^"^n maplist = ^"^"^n mappath = ^"^"^n mapextra = ^"^"^n mapimg = ^"^"^n mapocta = 0^n resetmapgui = 1^n mutsbefore = $mutsselected^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mapsmenuiter</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if (|| \[!= $lastmode $modeselected\] \[!= $lastmuts $mutsselected\]) \[ resetmapgui = 1 \]^n if (= $resetmapgui 1) \[^n maprot = 0^n maplist = ^"^"^n mappath = ^"^"^n if (= $modeselected $modeidxdemo) \[^n mutsselected = 0^n loop q 2 \[^n loopfiles lcurmap demos dmo \[^n if (? $q (&lt; (listfind xcurmap $demofavs \[strcmp $xcurmap $lcurmap\]) 0) (&gt;= (listfind xcurmap $demofavs \[strcmp $xcurmap $lcurmap\]) 0)) \[^n append maplist $lcurmap^n append mappath \[demos/@lcurmap\]^n \]^n \]^n \]^n maprot = (listlen $maplist)^n append maplist ^"?^"^n append mappath ^"?^"^n \] \[^n mutsselected = (mutscheck $modeselected $mutsselected)^n if (&gt;= $modeselected $modeidxplay) \[^n curlist = (getmaplist $modeselected $mutsselected (? (isonline) (listlen (listclients 1)) 0))^n curprev = (sublist $previousmaps 0 $maphistory)^n loop q 2 \[^n looplist lcurmap $curlist \[^n if (&lt; (listfind pcurmap $curprev \[strcmp $pcurmap $lcurmap\]) 0) \[^n if (? $q (&lt; (listfind xcurmap $mapfavs \[strcmp $xcurmap $lcurmap\]) 0) (&gt;= (listfind xcurmap $mapfavs \[strcmp $xcurmap $lcurmap\]) 0)) \[^n append maplist $lcurmap^n append mappath \[maps/@lcurmap\]^n \]^n \]^n \]^n \]^n maprot = (listlen $maplist)^n wantlist = 1^n looplist lcurmap $curprev \[^n if $wantlist \[^n append maplist ^"~^"^n append mappath ^"~^"^n wantlist = 0^n \]^n append maplist $lcurmap^n append mappath \[maps/@lcurmap\]^n \]^n \] \[ maprot = 0 \]^n wantlist = 1^n loop q 2 \[^n loopfiles lcurmap maps mpz \[^n if (&lt; (listfind mcurmap $maplist \[strcmp $mcurmap $lcurmap\]) 0) \[^n if (? $q (&lt; (listfind xcurmap $mapfavs \[strcmp $xcurmap $lcurmap\]) 0) (&gt;= (listfind xcurmap $mapfavs \[strcmp $xcurmap $lcurmap\]) 0)) \[^n if $wantlist \[^n append maplist ^"\*^"^n append mappath ^"\*^"^n wantlist = 0^n \]^n append maplist $lcurmap^n append mappath \[maps/@lcurmap\]^n \]^n \]^n \]^n \]^n if (&& \[&gt; $mapocta 0\] \[&gt; $hasoctapaks 0\]) \[^n wantlist = 1^n loop q 2 \[^n loopfiles lcurmap base ogz \[^n if (? $q (&lt; (listfind xcurmap $mapfavs \[strcmp $xcurmap $lcurmap\]) 0) (&gt;= (listfind xcurmap $mapfavs \[strcmp $xcurmap $lcurmap\]) 0)) \[^n if $wantlist \[^n append maplist ^".^"^n append mappath ^".^"^n wantlist = 0^n \]^n append maplist $lcurmap^n append mappath \[base/@lcurmap\]^n \]^n \]^n \]^n \]^n append maplist ^"?^"^n append mappath ^"?^"^n mapnum = (listfind curmap $maplist \[^n || \[=s $curmap $mapcur\] \[=s \[maps/@curmap\] $mapcur\] \[^n && \[&gt; $hasoctapaks 0\] \[&gt; $mapocta 0\] \[=s \[base/@curmap\] $mapcur\]^n \]^n \])^n \]^n mapcount = (listlen $maplist)^n if (! $maprot) \[ maprot = $mapcount \]^n if (|| \[&lt; $mapnum 0\] \[&gt;= $mapnum $maprot\]) \[ mapnum = (rnd $maprot) \]^n lastmode = $modeselected^n lastmuts = $mutsselected^n mapindex = 0^n resetmapgui = 0^n \]^n if (=s (at $maplist $mapnum) ^"?^") \[^n mapcur = $mapextra^n if (= $modeselected $modeidxdemo) \[^n mappth = \[demos/@mapcur\]^n mapdmo = (demoscan (format ^"%1.dmo^" $mappth))^n mapimg = (? (&gt;= $mapdmo 0) (format ^"maps/%1^" (demoinfo $mapdmo 2)) ^"textures/emblem^")^n \] \[^n mappth = $mapextra^n mapimg = $mapextra^n \]^n \] \[^n mapcur = (at $maplist $mapnum)^n mappth = (at $mappath $mapnum)^n if (= $modeselected $modeidxdemo) \[^n mapdmo = (demoscan (format ^"%1.dmo^" $mappth))^n mapimg = (? (&gt;= $mapdmo 0) (format ^"maps/%1^" (demoinfo $mapdmo 2)) ^"textures/emblem^")^n \] \[^n mapimg = (at $mappath $mapnum)^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>matmenu</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n guicheckbox^t^t^"show material volumes^t^t key M^"^t^t^t^"showmat^"^n guitext^n guibutton^t^"air^t^t^t^t^t^t^tkey Numpad 1^"^t^t^t^t^t^"editmat air^"^n guibutton^t^"alpha^t^t^t^t^t^tkey Numpad 2^"^t^t^t^t^t^t^"editmat alpha^"^n guibutton^t^"water^t^t^t^t^t^tkey Numpad 3^"^t^t^t^t^t^t^"editmat water^"^n guibutton^t^"lava^t^t^t^t^t^t^tkey Numpad 4^"^t^t^t^t^t^"editmat lava^"^n guibutton^t^"clip^t^t^t^t^t^t^tkey Numpad 5^"^t^t^t^t^t^"editmat clip^"^n guibutton^t^"noclip^t^t^t^t^t^tkey Numpad 6^"^t^t^t^t^t^t^"editmat noclip^"^n guibutton^t^"aiclip^t^t^t^t^t^tkey Numpad 7^"^t^t^t^t^t^t^"editmat aiclip^"^n guibutton^t^"death^t^t^t^t^t^tkey Numpad 8^"^t^t^t^t^t^t^"editmat death^"^n guibutton^t^"ladder^t^t^t^t^t^tkey Numpad 9^"^t^t^t^t^t^t^"editmat ladder^"^n^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mcurcrosshair</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mdlopt</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
&gt;= (strstr $modeltype $arg1) 0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mdm</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to multi deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: mdm bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
multidm $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>medieval</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to medieval deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: medieval bath (+ $mutsbitinstagib $mutsbitjetpack)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxdeathmatch (+ $mutsbitmedieval $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>modelfragmentshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n modeltype = $arg1^n result \[^n @fpstart^n OPTION ARB\_fog\_linear;^n ATTRIB dtc = fragment.texcoord\[0\];^n @(if (mdlopt ^"n^") \[if (mdlopt ^"e^") \[result \[^n PARAM lightdir = program.env\[1\];^n \]\] \[result \[^n ATTRIB lightdir = fragment.texcoord\[1\];^n \]\]\])^n @(if (mdlopt ^"s^") \[result \[^n @(if (&& (! (mdlopt ^"n^")) (! (mdlopt ^"i^"))) \[result \[^n PARAM lightdir = program.env\[0\];^n \]\])^n PARAM specfactor = @(if (mdlopt ^"i^") 256 128);^n \]\])^n @(if (&& (|| (mdlopt ^"s^") (mdlopt ^"n^")) (! (mdlopt ^"i^"))) \[result ^"PARAM lightscale = program.env\[2\];^"\])^n @(if (|| (mdlopt ^"s^") (mdlopt ^"m^")) \[result ^"PARAM maskscale = program.env\[4\];^"\])^n PARAM lightmaterial = program.env\[6\];^n^n TEMP light;^n TEX light, dtc, texture\[0\], 2D;^n^n @(if (mdlopt ^"m^") \[result \[^n PARAM lightmaterial2 = program.env\[7\];^n TEMP masks, mat, glow;^n TEX masks, dtc, texture\[1\], 2D;^n LRP mat.rgb, masks.a, lightmaterial, lightmaterial2; ^n MUL light.rgb, light, mat;^n MUL glow.rgb, light, maskscale.y;^n \]\] \[result \[^n MUL light.rgb, light, lightmaterial;^n \]\])^n^n @(if (mdlopt ^"n^") \[if (mdlopt ^"e^") \[result \[^n TEMP normal, normts;^n TEX normts, dtc, texture\[3\], 2D;^n SUB normts.xyz, normts, 0.5;^n MUL normal.xyz, normts.x, fragment.texcoord\[2\];^n MAD normal.xyz, normts.y, fragment.texcoord\[3\], normal;^n MAD normal.xyz, normts.z, fragment.texcoord\[4\], normal;^n @(normalize normal normal)^n \]\] \[result \[^n TEMP normal;^n TEX normal, dtc, texture\[3\], 2D;^n SUB normal.xyz, normal, 0.5;^n @(normalize normal normal)^n \]\]\])^n^n @(if (mdlopt ^"s^") \[result \[^n TEMP spec, halfangle;^n @(if (mdlopt ^"n^") \[^n if (mdlopt ^"e^") \[result \[^n ADD halfangle, lightdir, fragment.texcoord\[1\];^n @(normalize halfangle halfangle)^n \]\] \[result \[^n @(normalize halfangle fragment.texcoord\[2\])^n \]\]^n \] \[result \[^n TEMP normal;^n @(normalize normal fragment.texcoord\[1\])^n @(normalize halfangle fragment.texcoord\[2\])^n \]\])^n DP3\_SAT spec.x, halfangle, normal;^n POW spec.x, spec.x, specfactor.x;^n MUL spec.x, spec.x, maskscale.x;^n @(if (mdlopt ^"m^") \[result ^"MUL spec.x, spec.x, masks.r;^"\]) ^n \]\])^n^n @(if (mdlopt ^"i^") \[^n if (mdlopt ^"s^") \[result \[^n MUL spec.x, spec.x, maskscale.z;^n MUL @(if (mdlopt ^"m^") \[result ^"light.rgb^"\] \[result ^"result.color.rgb^"\]), spec.x, fragment.color;^n \]\] \[^n if (! (mdlopt ^"m^")) \[result ^"MOV result.color.rgb, 0;^"\]^n \]^n \] \[result \[^n @(if (|| (mdlopt ^"s^") (mdlopt ^"n^")) \[result \[^n TEMP intensity;^n DP3 intensity.y, normal, lightdir;^n MAD intensity.x, intensity.y, lightscale.x, lightscale.y;^n MAD\_SAT intensity.x, intensity.y, intensity.x, lightscale.z;^n \]\])^n @(if (mdlopt ^"s^") \[result \[^n MAD light.rgb, intensity.x, light, spec.x;^n \]\] \[if (mdlopt ^"n^") \[result \[^n MUL light.rgb, intensity.x, light;^n \]\]\])^n MUL @(if (mdlopt ^"m^") \[result ^"light.rgb^"\] \[result ^"result.color^"\]), light, fragment.color;^n \]\])^n^n @(if (mdlopt ^"m^") \[result \[^n @(if (mdlopt ^"e^") \[result \[^n LRP light.rgb, masks.g, glow, light;^n^n TEMP reflect;^n @(if (mdlopt ^"n^") \[result \[^n TEMP camvec, invfresnel, rvec;^n @(normalize camvec fragment.texcoord\[1\])^n DP3 invfresnel.x, camvec, normal;^n MUL rvec.xyz, invfresnel.x, normal;^n MAD rvec.xyz, rvec, 2, -camvec;^n^n MAX invfresnel.x, invfresnel, 0;^n MAD invfresnel.x, program.env\[3\].x, invfresnel.x, program.env\[3\].y;^n^n TEX reflect, rvec, texture\[2\], CUBE;^n MUL masks.b, masks.b, invfresnel.x; ^n \]\] \[result \[^n TEX reflect, fragment.texcoord\[3\], texture\[2\], CUBE;^n MUL masks.b, masks.b, fragment.texcoord\[3\].w; ^n \]\])^n LRP result.color.rgb, masks.b, reflect, light;^n \]\] \[if (mdlopt ^"i^") \[result \[^n TEMP k;^n MUL k.x, masks.g, masks.g;^n MUL\_SAT k.x, k.x, maskscale.w;^n @(if (mdlopt ^"s^") \[result \[^n MAD result.color.rgb, k.x, glow, light;^n \]\] \[result \[^n MUL result.color.rgb, k.x, glow;^n \]\])^n \]\] \[result \[^n LRP result.color.rgb, masks.g, glow, light;^n \]\]\])^n \]\])^n^n @(if (|| (mdlopt ^"m^") || (mdlopt ^"i^")) \[result \[^n MUL result.color.a, light.a, fragment.color.a;^n \]\])^n^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>modelshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n defershader 0 $arg1 \[^n basemodeltype = \[@@arg2\]^n shader 0 @arg1 (modelvertexshader $basemodeltype) (modelfragmentshader $basemodeltype)^n loop i 4 \[^n variantshader 0 @@arg1 0 (modelvertexshader (concatword ^"B^" $basemodeltype) (+ $i 1)) \[\]^n variantshader 0 @@arg1 1 (modelvertexshader (concatword ^"b^" $basemodeltype) (+ $i 1)) \[\]^n \]^n glaremodeltype = (strreplace (concatword $basemodeltype ^"i^") ^"e^")^n if (&lt; (strstr $glaremodeltype ^"s^") 0) \[glaremodeltype = (strreplace $glaremodeltype ^"n^")\]^n variantshader 0 @arg1 2 (modelvertexshader $glaremodeltype) (modelfragmentshader $glaremodeltype)^n loop i 4 \[^n variantshader 0 @@arg1 2 (modelvertexshader (concatword ^"B^" $glaremodeltype) (+ $i 1)) 2^n variantshader 0 @@arg1 3 (modelvertexshader (concatword ^"b^" $glaremodeltype) (+ $i 1)) 2^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>modelvertexshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n modeltype = $arg1^n result \[^n @(if (|| (mdlopt ^"b^") (mdlopt ^"B^")) \[result \[^n !!ARBvp1.0^n ATTRIB spos = vertex.position;^n ATTRIB snormal = vertex.normal;^n @(if (mdlopt ^"n^") \[result ^"ATTRIB stangent = vertex.attrib\[1\];^"\])^n \]\] \[result \[^n @vpstart^n ATTRIB onormal = vertex.normal;^n @(if (mdlopt ^"n^") \[result ^"ATTRIB otangent = vertex.attrib\[1\];^"\])^n \]\])^n PARAM ocampos = program.env\[1\];^n PARAM lightdir = program.env\[0\];^n PARAM lightscale = program.env\[2\];^n^n @(if (mdlopt ^"B^") \[skelmatanim $arg2 1 (mdlopt ^"n^")\])^n @(if (mdlopt ^"b^") \[skelquatanim $arg2 1 (mdlopt ^"n^")\])^n @(if (|| (mdlopt ^"b^") (mdlopt ^"B^")) \[result \[^n DP4 result.position.x, opos, state.matrix.mvp.row\[0\];^n DP4 result.position.y, opos, state.matrix.mvp.row\[1\];^n DP4 result.position.z, opos, state.matrix.mvp.row\[2\];^n DP4 result.position.w, opos, state.matrix.mvp.row\[3\];^n \]\])^n^n @(if (|| (mdlopt ^"n^") (mdlopt ^"s^") (mdlopt ^"i^")) \[result \[^n MOV result.color, vertex.color;^n \]\])^n ADD result.texcoord\[0\].xy, vertex.texcoord\[0\], program.env\[5\].yzww;^n^n @(if (|| (mdlopt ^"e^") (mdlopt ^"s^")) \[result \[^n TEMP camvec;^n SUB camvec, ocampos, opos;^n @(normalize camvec camvec)^n \]\])^n^n @(if (mdlopt ^"n^") \[^n if (mdlopt ^"e^") \[result \[^n DP3 result.texcoord\[1\].x, state.matrix.texture.row\[0\], camvec;^n DP3 result.texcoord\[1\].y, state.matrix.texture.row\[1\], camvec;^n DP3 result.texcoord\[1\].z, state.matrix.texture.row\[2\], camvec;^n^n ^n ^n TEMP wnormal, wtangent, wbitangent;^n DP3 wnormal.x, state.matrix.texture.row\[0\], onormal;^n DP3 wnormal.y, state.matrix.texture.row\[1\], onormal;^n DP3 wnormal.z, state.matrix.texture.row\[2\], onormal;^n MOV result.texcoord\[4\].xyz, wnormal;^n DP3 wtangent.x, state.matrix.texture.row\[0\], otangent;^n DP3 wtangent.y, state.matrix.texture.row\[1\], otangent;^n DP3 wtangent.z, state.matrix.texture.row\[2\], otangent;^n MOV result.texcoord\[2\].xyz, wtangent;^n XPD wbitangent.xyz, wnormal, wtangent;^n MUL result.texcoord\[3\].xyz, wbitangent, @(if (|| (mdlopt ^"b^") (mdlopt ^"B^")) \[result ^"stangent.w^"\] \[result ^"otangent.w^"\]);^n \]\] \[result \[^n TEMP obitangent;^n XPD obitangent.xyz, onormal, otangent;^n MUL obitangent.xyz, obitangent, @(if (|| (mdlopt ^"b^") (mdlopt ^"B^")) \[result ^"stangent.w^"\] \[result ^"otangent.w^"\]);^n^n DP3 result.texcoord\[1\].x, lightdir, otangent;^n DP3 result.texcoord\[1\].y, lightdir, obitangent;^n DP3 result.texcoord\[1\].z, lightdir, onormal;^n^n @(if (mdlopt ^"s^") \[result \[^n TEMP halfangle;^n ADD halfangle.xyz, lightdir, camvec;^n DP3 result.texcoord\[2\].x, halfangle, otangent;^n DP3 result.texcoord\[2\].y, halfangle, obitangent;^n DP3 result.texcoord\[2\].z, halfangle, onormal;^n \]\])^n \]\]^n \] \[result \[^n @(if (mdlopt ^"s^") \[result \[^n MOV result.texcoord\[1\].xyz, onormal;^n ADD result.texcoord\[2\].xyz, lightdir, camvec;^n \]\] \[if (! (mdlopt ^"i^")) \[result \[^n TEMP light;^n DP3 light.y, onormal, lightdir;^n MAD light.x, light.y, lightscale.x, lightscale.y;^n MAD light.x, light.y, light.x, lightscale.z;^n MIN light.x, light.x, 1;^n MUL result.color.xyz, light.x, vertex.color;^n MOV result.color.w, vertex.color.w;^n \]\]\])^n @(if (mdlopt ^"e^") \[result \[^n TEMP rvec, invfresnel;^n DP3 invfresnel.x, camvec, onormal;^n MUL rvec.xyz, invfresnel.x, onormal;^n MAD rvec.xyz, rvec, 2, -camvec;^n DP3 result.texcoord\[3\].x, state.matrix.texture.row\[0\], rvec;^n DP3 result.texcoord\[3\].y, state.matrix.texture.row\[1\], rvec;^n DP3 result.texcoord\[3\].z, state.matrix.texture.row\[2\], rvec;^n MAX invfresnel.x, invfresnel.x, 0;^n MAD result.texcoord\[3\].w, program.env\[3\].x, invfresnel.x, program.env\[3\].y;^n \]\])^n \]\])^n^n @fogcoord^n^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>modeselected</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>modevar</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n local g m s^n guistayopen \[ guilist \[^n g = $arg4^n m = $$arg3^n s = $$arg5^n if (ismodelocked $g $m 0 $s) \[ guibutton $arg1 \[ disabled = @arg4 \] \[\] ^"checkdisable^" \] \[^n guibutton $arg1 \[@arg2 = @arg4\] \[\] (? (= $$arg2 $arg4) ^"checkboxon^" ^"checkbox^")^n \]^n \] \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>modifier</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>modlval</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>multidm</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to multi deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: multidm bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxdeathmatch (+ $mutsbitmulti $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mutsbefore</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>mutsselected</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>mutsvar</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n local g m s t^n guistayopen \[ guilist \[^n g = $$arg2^n m = $$arg3^n s = $$arg5^n if (& (mutsimplied $g $m) $arg4) \[^n guibutton $arg1 \[ implied = @arg4 \] \[\] ^"checkboxtwo^"^n \] \[^n if (|| (& (mutscheck $g (| $m $arg4) $arg4) $arg4) (! (ismodelocked $g $m $arg4 $s))) \[^n t = (& $m $arg4)^n guibutton $arg1 \[^n mutate = @arg4^n if @t \[@@arg3 = @@(mutscheck $g (- $m $arg4))\] \[^n @@arg3 = @@(mutscheck $g (| $m $arg4) $arg4)^n \]^n \] \[\] (? $t ^"checkboxon^" ^"checkbox^")^n \] \[ guibutton $arg1 \[ disabled = @arg4 \] \[\] ^"checkdisable^" \]^n \]^n \] \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>n</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>name</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
playername $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>nameval</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>newbrush</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n brushmax = (+ $brushmax 1)^n do \[^n brush\_@brushmax = \[^n brushname = \[@@@arg1\]^n clearbrush^n @@(if (&gt; $numargs 1) \[result \[brushhandle @arg2 @arg3; brushverts \[@@arg4\]\]\])^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>newentgui</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n genentattributes \[@arg1\] \[@arg2\] \[@arg3\]^n newgui $arg1 \[^n guitext $tmpt^n guibar^n @entattributes^n guitab type^n guilistsplit n 2 $enttypelist \[^n guibutton $n \[ entset @n \]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>newmapsize</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
12

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>noautosave</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>noclip</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editmat noclip $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>normalize</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
format \[^n DP3 %1.w, %2, %2;^n RSQ %1.w, %1.w;^n MUL %1.xyz, %1.w, %2;^n\] $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>notepad</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if (&gt; $numargs 0) \[notepadfile = $arg1\]^n showgui notepad^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>notepadfile</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
untitled.txt

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>notexturemodelvertexshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n result \[^n @(if (&lt; $numargs 1) \[result $vpstart\] \[result \[^n !!ARBvp1.0^n ATTRIB spos = vertex.position;^n @arg1^n DP4 result.position.x, opos, state.matrix.mvp.row\[0\];^n DP4 result.position.y, opos, state.matrix.mvp.row\[1\];^n DP4 result.position.z, opos, state.matrix.mvp.row\[2\];^n DP4 result.position.w, opos, state.matrix.mvp.row\[3\];^n \]\])^n^n MOV result.color, vertex.color;^n @fogcoord^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>numcrosshairs</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>octamaps</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n allowmaps ^"complex douze ot academy metl2 metl3 nmp8 refuge tartech kalking1 dock turbine fanatic\_quake oddworld wake5 aard3c curvedm fragplaza pgdm kffa neondevastation hog2 memento neonpanic lostinspace DM\_BS1 shindou sdm1 shinmei1 stemple powerplant phosgene oasis island metl4 ruby frozen ksauer1 killfactory corruption deathtek aqueducts orbe roughinery shadowed torment moonlite darkdeath orion nmp10 katrez\_d thor frostbyte ogrosupply kmap5 thetowers guacamole tejen hades paradigm mechanic wdcd^"^n mainmaps ^"complex douze ot academy metl2 metl3 nmp8 refuge tartech kalking1 dock turbine fanatic\_quake oddworld wake5 aard3c curvedm fragplaza pgdm kffa neondevastation hog2 memento neonpanic lostinspace DM\_BS1 shindou sdm1 shinmei1 stemple powerplant phosgene oasis island metl4 ruby frozen ksauer1 killfactory corruption deathtek aqueducts orbe roughinery shadowed torment moonlite darkdeath orion nmp10 katrez\_d thor frostbyte ogrosupply kmap5 thetowers guacamole tejen hades paradigm mechanic wdcd^"^n capturemaps ^"hallo reissen flagstone face-capture shipwreck dust2 urban\_c berlin\_wall akroseum valhalla damnation mach2 redemption tejen europium capture\_night l\_ctf forge campo wdcd sacrifice core\_transfer recovery^"^n defendmaps ^"urban\_c nevil\_c fb\_capture nmp9 c\_valley lostinspace fc3 face-capture nmp4 nmp8 hallo monastery ph-capture hades fc4 relic frostbyte venice paradigm corruption asteroids ogrosupply reissen akroseum duomo capture\_night c\_egypt tejen dust2 campo killcore3 damnation arabic cwcastle river\_c serenity^"^n bombermaps ^"hallo reissen flagstone face-capture shipwreck dust2 urban\_c berlin\_wall akroseum valhalla damnation mach2 redemption tejen europium capture\_night l\_ctf forge campo wdcd sacrifice core\_transfer recovery^"^n holdmaps ^"complex douze ot academy metl2 metl3 nmp8 refuge tartech kalking1 dock turbine fanatic\_quake oddworld wake5 aard3c curvedm fragplaza pgdm kffa neondevastation hog2 memento neonpanic lostinspace DM\_BS1 shindou sdm1 shinmei1 stemple powerplant phosgene oasis island metl4 ruby frozen ksauer1 killfactory corruption deathtek aqueducts orbe roughinery shadowed torment moonlite darkdeath orion nmp10 katrez\_d thor frostbyte ogrosupply kmap5 thetowers guacamole tejen hades paradigm mechanic wdcd^"^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>okprofile</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
setinfo $nameval $colrval $modlval $vntyval; cleargui 1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>oldfloatspeed</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
float alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
200.0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>oldpassthroughcube</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>oldpassthroughsel</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>oldscreenshot</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n if (= $arg1 1) \[^n oldshowhud = $showhud; oldshowconsole = $showconsole; showhud 0; showconsole 0^n \] \[showhud $oldshowhud; showconsole $oldshowconsole\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>oldshowconsole</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>oldshowhud</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>on\_text</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n id = 0^n reg = \[@(filter $arg4)~\] ^n loopwhile i $voices \[= $id 0\] \[^n str = $\[voice@(+ $i 1)str\]^n if (strncasecmp $str $reg (strlen $str)) \[ id = (+ $i 1) \]^n \]^n result (getalias \[voice@\[id\]snd\])^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>opaquepaste</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>outlinecolours</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^"255 0 0^" ^"0 255 0^" ^"255 255 255^" ^"0 0 0^" ^"255 255 0^" ^"255 0 255^" ^"0 255 255^" ^"0 255 127^" ^"255 127 0^" ^"127 0 255^" ^"255 0 127^" ^"0 127 255^" ^"OFF^"

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>outlinestatus</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>paintmodes</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^"off^" ^"overwrite blendmap^" ^"merge blendmap^" ^"max opacity to brush's^" ^"inverted merge^" ^"opacity multiplier (erasing)^"

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>particleshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n shader 0 $arg1 \[^n @vpstart^n MOV result.texcoord\[0\], vertex.texcoord\[0\];^n MUL result.texcoord\[1\], vertex.color, program.env\[4\];^n^n @(if (&gt;= (strstr $arg1 ^"soft^") 0) \[result \[^n TEMP projtc;^n DP4 projtc.x, state.matrix.mvp.row\[0\], opos;^n DP4 projtc.y, state.matrix.mvp.row\[1\], opos;^n DP4 projtc.w, state.matrix.mvp.row\[3\], opos;^n^n ADD projtc.xy, projtc, projtc.w;^n MUL projtc.xy, projtc, program.env\[6\];^n MOV result.texcoord\[2\].xyw, projtc;^n^n TEMP offset;^n MAD offset.xyz, vertex.texcoord\[0\], { 2.82842712474619, 2.82842712474619, 0, 0 }, { -1.4142135623731, -1.4142135623731, 1, 0 };^n MOV result.texcoord\[3\].xyz, offset;^n^n DP4 offset.z, state.matrix.modelview.row\[2\], -opos;^n MAD offset.z, offset.z, program.env\[5\].x, program.env\[5\].y;^n MOV result.texcoord\[4\].xyz, offset;^n \]\])^n^n @fogcoord^n END^n \] \[^n @fpstart^n OPTION ARB\_fog\_linear;^n TEMP diffuse;^n TEX diffuse, fragment.texcoord\[0\], texture\[0\], 2D;^n @(if (&gt;= (strstr $arg1 ^"soft^") 0) \[result \[^n TEMP depth, offset;^n TXP depth, fragment.texcoord\[2\], texture\[2\], @(if (&gt;= (strstr $arg1 ^"rect^") 0) \[result ^"RECT^"\] \[result ^"2D^"\]);^n DP3 offset.x, fragment.texcoord\[3\], fragment.texcoord\[4\];^n @(if (&gt;= (strstr $arg1 ^"soft8^") 0) \[result \[^n DP4 depth.x, depth, program.env\[6\];^n SUB\_SAT depth.x, depth.x, offset.x;^n \]\] \[result \[^n MAD\_SAT depth.x, depth.x, program.env\[5\].z, -offset.x;^n \]\])^n MUL diffuse.a, diffuse.a, depth.x;^n \]\])^n MUL result.color, fragment.texcoord\[1\], diffuse;^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>passthrough</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if (= $arg1 1) \[^n oldpassthroughsel = $passthroughsel^n oldpassthroughcube = $passthroughcube^n passthroughsel 1; passthroughcube 1^n \] \[^n passthroughsel $oldpassthroughsel^n passthroughcube $oldpassthroughcube^n \]^n entcancel^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>pastebuffer</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
showgui pastebuffer

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>pixelparam0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
program.env\[16\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>pixelparam1</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
program.env\[17\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>pixelparam2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
program.env\[18\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>pixelparam3</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
program.env\[19\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>pixelparam4</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
program.env\[20\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>pixelparam5</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
program.env\[21\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>pixelparam6</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
program.env\[22\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>pixelparam7</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
program.env\[23\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>q</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>quickeditmenu</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n guitext ^"Quick Commands:^"^n guibar^n guifield savemap\_name 10 \[ savemap $savemap\_name \]^n guibutton quicklight ^"calclight -1^"^n guibutton ^"optimize map^" ^"remip^"^n guibutton ^"new entity^" ^"newent light^"^n guibar^n guibutton newmap^n guibar^n guibutton help ^"showgui editing^"^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>quine</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
echo (format ^"quine = \[%1\]^" $quine)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>radarblendstorage</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>replaceents</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if $editing \[^n do \[^n entfind @(entget)^n entset @(loopconcat i $numargs \[result $\[arg@(+ $i 1)\]\])^n \]^n echo Replaced (enthavesel) entities^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>resbutton</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
format \[^n guibutton ^"%1x%2^" ^"screenres %1 %2^" \[\] (? (&& \[= $scr\_w %1\] \[= $scr\_h %2\]) ^"radioboxon^" ^"radiobox^")^n\] $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>resetlight</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n lightcolour = 0^n lightrgb = ^"255 255 255^"^n lightbright = 1^n lightradius = 128^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>resetmapgui</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>resettips</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n tips = 0^n addtip (format ^"press ^^fs^^fc%1^^fS to ^^fs^^fyjump^^fS and again in mid-air to ^^fs^^fypropel^^fS yourself^" (searchbinds ^"jump^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS to ^^fs^^fycrouch^^fS, doing so while landing will perform a ^^fs^^fyimpulse slide^^fS^" (searchbinds ^"crouch^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS and ^^fs^^fc%2^^fS to fire your weapon^" (searchbinds ^"primary^" 0 ^"or^" ^"^^fw^") (searchbinds ^"secondary^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS to ^^fs^^fyreload^^fS your weapon, timing this can be crucial to survival^" (searchbinds ^"reload^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS to ^^fs^^fyuse items^^fS and ^^fs^^fytriggers^^fS^" (searchbinds ^"use^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS to ^^fs^^fywalk^^fS for better traction and accuracy^" (searchbinds ^"pacing^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS to ^^fs^^fywall run^^fS, ^^fs^^fywall kick^^fS, or ^^fs^^fymelee^^fS^" (searchbinds ^"special^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS to ^^fs^^fytalk^^fS and ^^fs^^fc%2^^fS to only speak to ^^fs^^fyteammates^^fS^" (searchbinds ^"saytextcommand^" 0 ^"or^" ^"^^fw^") (searchbinds ^"sayteamcommand^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS while in the air to ^^fs^^fyfly-kick^^fS enemies^" (searchbinds ^"special^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS to ^^fs^^fysuicide^^fS, this will reset you in ^^fs^^fytime-trial^^fS and ^^fs^^fygauntlet^^fS^" (searchbinds ^"kill^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS to crouch while landing to ^^fs^^fyimpulse slide^^fS^" (searchbinds ^"crouch^" 0 ^"or^" ^"^^fw^"))^n addtip (format ^"press ^^fs^^fc%1^^fS during an ^^fs^^fyimpulse slide^^fS to perform a ^^fs^^fyimpulse launch^^fS^" (searchbinds ^"jump^" 0 ^"or^" ^"^^fw^"))^n addtip ^"when you're ^^fs^^foon fire^^fS you can ^^fs^^fcjump in water^^fS to put yourself out, crouch if necessary^"^n addtip ^"you're ^^fs^^fyless accurate^^fS when ^^fs^^fyjumping^^fS and ^^fs^^fymoving^^fS, stop for a perfect shot^"^n addtip ^"you can ^^fs^^fyclick these tips^^fS to ^^fs^^fcget a new tip^^fS^"^n addtip ^"you can chat with the developers in ^^fs^^fc\#redeclipse^^fS on ^^fs^^fcirc.freenode.net^^fS^"^n addtip ^"share your own tips with the developers in ^^fs^^fc\#redeclipse^^fS on ^^fs^^fcirc.freenode.net^^fS^"^n addtip ^"tips are ^^fs^^fccool^^fS, you should ^^fs^^fyread them more often^^fS^"^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>rgbafog</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
format \[^n TEMP fog;^n SUB fog.x, state.fog.params.z, fragment.fogcoord.x;^n MUL\_SAT fog.x, fog.x, state.fog.params.w;^n LRP result.color, fog.x, %1, %2;^n\] $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>rgbfog</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>rotoscope</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n clearpostfx^n if (&gt;= $numargs 1) \[addpostfx rotoscope 0 0 0 $arg1\]^n if (&gt;= $numargs 2) \[^n if (= $arg2 1) \[addpostfx hblur3; addpostfx vblur3\]^n if (= $arg2 2) \[addpostfx hblur5; addpostfx vblur5\]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>sample4corners</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n TEMP s00, s02, s20, s22;^n TEX s00, fragment.texcoord\[1\], texture\[0\], RECT;^n TEX s02, fragment.texcoord\[2\], texture\[0\], RECT;^n TEX s20, fragment.texcoord\[3\], texture\[0\], RECT;^n TEX s22, fragment.texcoord\[4\], texture\[0\], RECT;^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>savecurrentmap</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
savemap

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>savemap\_name</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
temp

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>sayteamcommand</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
inputcommand $arg1 \[sayteam $commandbuffer\] (getplayerteamicon) (getplayerteamcolour) 0 ^"s^"

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>saytextcommand</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
inputcommand $arg1 \[say $commandbuffer\] ^"textures/chat^" 0 ^"s^"

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>scolb</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>scolg</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>scolr</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>scolrval</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>scratchpad</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
showgui scratchpad

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>selcorners</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
if $hmapedit \[ hmapselect \] \[ cancelsel; || \[entdrag\] \[ corners \] \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>selectbrush</b> <i>&lt;index&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
select a different brush with relative index to the current one; -1 = previous brush, 1 = next brush

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n brushindex = ( + $brushindex $arg1 )^n if (&lt; $brushindex 0) \[ brushindex = $brushmax \]^n if (&gt; $brushindex $brushmax) \[ brushindex = 0 \]^n do \[brush\_@brushindex\]^n echo $brushname^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>selectents</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
entselect \[&& \[insel\] \[=enttype @@arg1\]\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>selentedit</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
saycommand ( concatword ^"/entset ^" (entget) )

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>selentfindall</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
do \[ entfind @(entget) \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>selreplaceents</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
saycommand ( concatword ^"/replaceents ^" (entget) )

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>servermenu</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guipage sinfo 5 88 4.2 \[getserver\] (getserver) \[^n sinfostat = (getserver $i 0 0)^n sinfoname = (getserver $i 0 1)^n sinfoport = (getserver $i 0 2)^n sinfonpid = \[@\[sinfoname\]:\[@@sinfoport\]\]^n sinfodesc = (getserver $i 0 3)^n sinfomapn = (getserver $i 0 4)^n sinfonump = (getserver $i 0 5)^n sinfoplayers = (? $i (+ $sinfoplayers $sinfonump) $sinfonump)^n sinfoping = (getserver $i 0 6)^n sinfolast = (getserver $i 0 7)^n sinfogver = (getserver $i 1 0)^n sinfomode = (getserver $i 1 1)^n sinfomuts = (getserver $i 1 2)^n sinfotime = (getserver $i 1 3)^n sinfomaxp = (getserver $i 1 4)^n sinfomstr = (getserver $i 1 5)^n sinfovars = (getserver $i 1 6)^n sinfomods = (getserver $i 1 7)^n sinfoofft = (? (&gt;= $sinfolast 0) (div (max (- (getmillis 1) (- $sinfolast (div $sinfoping 2))) 0) 1000) 0)^n sinfoactive = (? (&lt; $sinfoping $serverwaiting) 1 0)^n sinfonumsrv = (? $i (+ $sinfonumsrv $sinfoactive) $sinfoactive)^n \] \[1\] \[^n if $updateservergui \[^n guibutton ^"^^fwThere are no servers to display, maybe ^^fgupdate ^^fwthe list?^" updatefrommaster \[\] ^"info^"^n \] \[^n sleep 1 \[ updateservergui = 1; updatefrommaster \]^n \]^n \] \[^n if (getserver) \[ sleep 1 \[ updateservers \] \]^n guilist \[^n guibutton ^"^^fgupdate^"^t^t^tupdatefrommaster;^tguistrut 1.5^n guibutton ^"^^frreset^"^t^t^tclearservers;^t^tguistrut 1.5^n guibutton ^"^^fodisconnect^"^t^tdisconnect;^t^t^tguistrut 1.5^n guibutton ^"^^fmlan connect^"^t^tlanconnect;^t^t^tguistrut 1.5^n guicheckbox ^"^^fcsearch lan^"^t^tsearchlan;^t^t^tguistrut 1.5^n guicheckbox ^"^^fbauto sort^"^t^tautosortservers;^tguistrut 1.5^n guibutton ^"^^fysort now^"^t^t^tsortservers;^t^tguispring^n guitext (format ^"^^fd\[ ^^fc%1 ^^fwplayers on ^^fc%2 ^^fwof ^^fc%3 ^^fwserver%4 ^^fd\]^" $sinfoplayers $sinfonumsrv $sinfonum (? (!= $sinfonum 1) ^"s^"))^n guistrut 1^n \]^n guistrut 0.25^n if (&gt; (getversion 3) (getversion 1)) \[^n guilist \[ guibutton ^"^^fzoynew version released! ^^fwget it now from: ^^fcwww.redeclipse.net^" ^"^" \]^n guistrut 0.25^n \]^n \] \[^n guistrut 0.125^n guimerge 88 \[^n guicenter \[^n guistrut 10 1^n if $sinfoactive \[^n guicenter \[^n guifont ^"huge^" \[ guibutton (format ^"^^fw%1^" $sinfonump) \]^n guifont ^"default^" \[ guibutton (format ^"^^fd / ^^fa%1^" $sinfomaxp) \]^n \]^n guicenter \[^n guifont ^"default^" \[ guibutton (format ^"^^f%1%2^" (? (&lt; $sinfoping 200) ^"g^" (? (&lt; $sinfoping 400) ^"y^" ^"r^")) $sinfoping) \]^n guifont ^"reduced^" \[ guibutton ^" ^^fams^" \]^n \]^n \] \[ guicenter \[ guifont ^"huge^" \[ guispring; guibutton ^"?^"; guispring \] \] \]^n \]^n sinfoimage = ^"textures/emblem^"^n if (&& \[&lt; $sinfoping $serverwaiting\] \[= $sinfogver (getversion 1)\]) \[^n sinfopath = (listfind curmap $maplist \[|| \[=s $curmap $sinfomapn\] \[=s \[base/@curmap\] $sinfomapn\] \[^n && \[&gt; $hasoctapaks 0\] \[=s \[base/@curmap\] $sinfomapn\]^n \]\])^n if (&gt; $sinfopath -1) \[ sinfoimage = (at $mappath $sinfopath) \]^n \]^n guiimage $sinfoimage ^"^" 2 1 ^"textures/emblem^"^n guistrut 1^n guicenter \[^n guilist \[^n guifont ^"reduced^" \[ guibutton (format ^"^^fw%1 ^" $sinfodesc) \]^n guifont ^"little^" \[^n guibutton (format ^"^^fd(^^fa%1^^fd)^" $sinfonpid)^n guibutton (format ^" %1modified^" (? $sinfomods (format ^"^^fc%1%% ^" (precf (\*f (divf $sinfomods $sinfovars) 100) 2)) ^"^^fgun^"))^n \]^n \]^n guispring^n if $sinfoactive \[^n guilist \[^n guistrut 0.25^n if (= $sinfogver (getversion 1)) \[^n guifont ^"default^" \[^n case $sinfostat 0 \[^n guibutton ^"^^fgopen^" \[\] \[\] ^"textures/servers/default^"^n \] 1 \[^n guibutton ^"^^fylock^" \[\] \[\] ^"textures/servers/locked^"^n \] 2 \[^n guibutton ^"^^fmpriv^" \[\] \[\] ^"textures/servers/private^"^n \] 3 \[^n guibutton ^"^^frfull^" \[\] \[\] ^"textures/servers/full^"^n \] () \[^n guibutton ^"^^founknown^" \[\] \[\] ^"textures/servers/unknown^"^n \]^n \]^n if (!= $sinfomode $modeidxediting) \[^n guifont ^"reduced^" \[ guibutton (format ^" ^^fd\[^^fw%1^^fd\]^" (timestr (? $sinfonump (max (- $sinfotime $sinfoofft) 0) $sinfotime) 2)) \]^n \]^n gname = (gamename $sinfomode $sinfomuts 0 32)^n guifont ^"little^" \[ guibutton (format ^" ^^fy%1 ^^faon ^^fo%2^" $gname $sinfomapn) \]^n \] \[^n guifont ^"default^" \[ guibutton ^"^^foincompatible^" \[\] \[\] ^"textures/servers/failed^" \]^n guifont ^"reduced^" \[ guibutton (concat ^" ^^faserver is using^" (? (&gt; $sinfogver (getversion 1)) ^"a ^^fwnewer^" ^"an ^^fdolder^") ^"protocol^") \]^n \]^n \]^n guispring^n guilist \[^n if (=s $sinfonpid $sinforetry) \[^n if (= $sinfostat 3) \[ guibutton ^"^^fd\[ ^^fwwaiting for slot ^^fd\] ^" \]^n guibutton ^"^^fwpassword ^^fd= ^"^n sinfopassval = $sinfopass^n guifield sinfopassval 20 \[sinfopass = $sinfopassval\]^n \] \[^n if (&gt; $sinfonump 0) \[^n guistrut 0.25^n sinfopnum = (getserver $i 2)^n if (&gt; $sinfopnum 0) \[^n guifont ^"reduced^" \[ guibutton (format ^"^^fc%1 ^^fwplayer%2: ^" $sinfopnum (? (&gt; $sinfopnum 1) ^"s^")) \]^n pname = ^"^"^n pmore = 0^n loop j $sinfopnum \[^n if (&gt; (strlen $pname) 86) \[ pmore = (+ $pmore 1) \] \[^n append pname (format \[^"%1^"\] (getserver $i 2 $j))^n \]^n \]^n guifont ^"little^" \[^n guibutton (concat (prettylist $pname) (^n ? $pmore (concat ^"and^^fy^" $pmore ^"^^fwmore^")^n ))^n \]^n \] \[ guifont ^"reduced^" \[ guibutton ^"^^faplayer info not available^" \] \]^n \] \[ guifont ^"reduced^" \[ guibutton ^"^^fano players online^" \] \]^n \]^n \]^n \] \[^n guilist \[^n guistrut 0.25^n guifont ^"default^" \[ guibutton ^"^^founresponsive^" \[\] \[\] ^"textures/servers/failed^" \]^n guifont ^"reduced^" \[ guibutton ^" ^^faserver is not replying to queries^" \]^n \]^n \]^n \]^n \] \[^n sinfopass = ^"^"^n sinforetry = @(escape $sinfonpid)^n sinfowait = (! (|| \[hasauthkey\] \[!= @@sinfomstr 4\]))^n \] \[^n sinfopass = ^"^"^n sinforetry = @(escape $sinfonpid)^n sinfowait = (! (hasauthkey))^n \]^n if (=s $sinfonpid $sinforetry) \[^n if (= $sinfowait 1) \[^n if (strlen $sinfopass) \[^n connect $sinfoname $sinfoport $sinfopass^n sinfopass = ^"^"^n sinforetry = ^"^"^n sinfowait = 0^n \]^n \] \[^n if (|| \[hasauthkey\] \[!= $sinfostat 3\]) \[^n connect $sinfoname $sinfoport^n sinfopass = ^"^"^n sinforetry = ^"^"^n sinfowait = 0^n \]^n \]^n \]^n guistrut 0.125^n \] \[^n guistrut 0.5^n guilist \[^n guifont ^"little^" \[^n guitext ^"sort: ^"^n loop i (listlen $serversort) \[^n sinfostype = (at $serversort $i)^n if $sinfostype \[^n sinfosabsl = (? (&gt; $sinfostype 0) $sinfostype (- 0 $sinfostype))^n sinfosname = (at $sinfotypes $sinfosabsl)^n guistrut 1^n guibutton (? (&gt; $sinfostype 0) $sinfosname \[-@sinfosname\]) \[^n sinfomodify @sinfostype^n \] \[^n sinfomodify (- 0 @sinfostype)^n \] ^"^" 0xFFFFFF^n \]^n \]^n guispring^n loop i (listlen $sinfotypes) \[^n if (&& $i \[&lt; (listfind sinfoctype $serversort \[= $i (? (&gt; $sinfoctype 0) $sinfoctype (- 0 $sinfoctype))\]) 0\]) \[^n sinfosname = (at $sinfotypes $i)^n guistrut 1^n guibutton $sinfosname \[^n sinfomodify @i^n \] \[^n sinfomodify (- 0 @i)^n \] ^"^" 0x666666^n \]^n \]^n guispring^n guibutton ^"reset^" \[serversortreset\] \[serversortreset\] ^"^" 0xFF8888^n guistrut 1^n \]^n \]^n guistrut 0.5^n guilist \[^n guifont ^"little^" \[ guitext ^"update interval:^" \]^n guistrut 2^n guilist \[^n guistrut 80 1^n guilistslider serverupdateinterval ^"1 2 3 4 5 10 15 20 25 30 35 40 45 50 55 60^"^n \]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>servermenuinit</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n sinfoindex = 0^n sinfowait = 0^n sinforetry = ^"^"^n sinfopass = ^"^"^n sinfoplayers = 0^n sinfonumsrv = 0^n shownservergui = 0^n updateservergui = 0^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>servermenuiter</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if (! $shownservergui) \[^n maplist = ^"^"^n mappath = ^"^"^n loopfiles lcurmap maps mpz \[^n if (&lt; (listfind mcurmap $maplist \[=s $mcurmap $lcurmap\]) 0) \[^n append maplist $lcurmap^n append mappath \[maps/@lcurmap\]^n \]^n \]^n if (&gt; $hasoctapaks 0) \[^n loopfiles lcurmap base ogz \[^n append maplist $lcurmap^n append mappath \[base/@lcurmap\]^n \]^n \]^n shownservergui = 1^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>setinfo</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
playername $arg1; playercolour $arg2; playermodel $arg3; if (! (strcmp $versionuname ^"mekarcade^")) \[playervanity $arg4\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>setmaster</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
setpriv $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>setup4corners</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n ADD result.texcoord\[1\], vertex.texcoord\[0\], { -1.5, -1.5, 0, 0 };^n ADD result.texcoord\[2\], vertex.texcoord\[0\], { 1.5, -1.5, 0, 0 };^n ADD result.texcoord\[3\], vertex.texcoord\[0\], { -1.5, 1.5, 0, 0 };^n ADD result.texcoord\[4\], vertex.texcoord\[0\], { 1.5, 1.5, 0, 0 };^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>setupbloom</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n addpostfx bloom\_init 1 1 ^"+0^"^n loop i (- $arg1 1) \[^n addpostfx bloom\_scale (+ $i 2) (+ $i 2) (concatword ^"+^" (+ $i 1))^n \]^n addpostfx (concatword bloom $arg1) 0 0 (loopconcat i (+ $arg1 1) \[result $i\]) $arg2^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>shadowmapcastervertexshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n result \[^n @(if (&lt; $numargs 1) \[result $vpstart\] \[result \[^n !!ARBvp1.0^n ATTRIB spos = vertex.position;^n @arg1^n DP4 result.position.x, opos, state.matrix.mvp.row\[0\];^n DP4 result.position.y, opos, state.matrix.mvp.row\[1\];^n DP4 result.position.w, opos, state.matrix.mvp.row\[3\];^n \]\])^n^n TEMP z;^n DP4 z.x, opos, state.matrix.mvp.row\[2\];^n^n @(if (&gt;= $numargs 1) \[result ^"MOV result.position.z, z.x;^"\])^n^n SUB result.texcoord\[0\].x, 1, z.x;^n MOV result.texcoord\[0\].y, 1;^n MOV result.texcoord\[0\].z, 0;^n MOV result.texcoord\[0\].w, program.env\[1\].x;^n^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>shiftfloatspeed</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
500

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_PERSIST IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>shiftmod</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n if $arg1 \[^n oldfloatspeed = $floatspeed^n floatspeed $shiftfloatspeed^n modscale = $shiftmodscale^n \] \[^n floatspeed $oldfloatspeed^n modscale = 1^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>shiftmodscale</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
10

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_PERSIST IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>showfileeditor</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n guieditor $arg1 $arg2 $arg3^n textinit $arg1 $arg1^n guistayopen \[^n guilist \[^n guibutton ^"load^" \[textfocus @arg1; textload @arg1\]^n guibar^n guibutton ^"save^" \[textfocus @arg1; textsave @arg1\]^n guibar^n guibutton ^"exec^" \[textfocus @arg1; textexec\]^n guibar^n guibutton ^"copy^" \[textfocus @arg1; textcopy\]^n guibar^n guibutton ^"paste^" \[textfocus @arg1; textpaste\]^n guibar^n guibutton ^"select^" \[textfocus @arg1; textselectall\]^n guibar^n guibutton ^"clear^" \[textfocus @arg1; textclear\]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>showmapmodel</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n mapmodelpath = (mapmodelindex $arg1)^n mapmodelshot = (concatword ^"models/^" $mapmodelpath ^"/thumb^")^n mapmodelcmd = (concat newent mapmodel $arg1)^n guilist \[ guilist \[^n guiimage $mapmodelshot $mapmodelcmd 2 1 ^"textures/nothumb^"^n guibutton $mapmodelpath $mapmodelcmd^n \] \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>shownservergui</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>showtip</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n if (|| \[= $lasttip 0\] \[&gt; (- (getmillis) $lasttip) 30000\]) \[^n resettips^n curtip = $\[tip@(+ (rnd $tips) 1)\]^n lasttip = (getmillis)^n \]^n result $curtip^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>sinfodisp</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>sinfoindex</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>sinfomodify</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n sinfotlist = $arg1^n sinfotabsl = (? (&gt; $sinfotlist 0) $sinfotlist (- 0 $sinfotlist))^n loop i (listlen $serversort) \[^n sinfostype = (at $serversort $i)^n if $sinfostype \[^n sinfosabsl = (? (&gt; $sinfostype 0) $sinfostype (- 0 $sinfostype))^n if (!= $sinfotabsl $sinfosabsl) \[ append sinfotlist $sinfostype \]^n \]^n \]^n serversort $sinfotlist^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>sinfonum</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>sinfonumsrv</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>sinfopass</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>sinfoplayers</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>sinforetry</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>sinfotypes</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^"^" ^"status^" ^"name^" ^"port^" ^"qport^" ^"desc^" ^"mode^" ^"muts^" ^"map^" ^"time^" ^"players^" ^"maxplayers^" ^"ping^"

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>sinfowait</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>skelanimlength</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
-30

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>skelmatanim</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n skelanimlength = (min (- $maxvpenvparams (+ $reservevpparams 10)) $maxskelanimdata)^n result \[^n PARAM mats\[\] = { program.env\[ 10 .. @@(- (+ 10 $skelanimlength) 1) \] };^n @(if (&gt; $arg1 1) \[result ^"ATTRIB weights = vertex.attrib\[6\];^"\])^n ATTRIB bones = vertex.attrib\[7\];^n ADDRESS bone;^n TEMP mx, my, mz;^n^n ARL bone.x, bones.x;^n @(if (= $arg1 1) \[result \[^n MOV mx, mats\[bone.x\];^n MOV my, mats\[bone.x+1\];^n MOV mz, mats\[bone.x+2\];^n \]\] \[result \[^n MUL mx, weights.x, mats\[bone.x\];^n MUL my, weights.x, mats\[bone.x+1\];^n MUL mz, weights.x, mats\[bone.x+2\];^n ARL bone.x, bones.y;^n MAD mx, weights.y, mats\[bone.x\], mx;^n MAD my, weights.y, mats\[bone.x+1\], my;^n MAD mz, weights.y, mats\[bone.x+2\], mz;^n \]\])^n @(if (&gt;= $arg1 3) \[result \[^n ARL bone.x, bones.z;^n MAD mx, weights.z, mats\[bone.x\], mx;^n MAD my, weights.z, mats\[bone.x+1\], my;^n MAD mz, weights.z, mats\[bone.x+2\], mz;^n \]\])^n @(if (&gt;= $arg1 4) \[result \[^n ARL bone.x, bones.w;^n MAD mx, weights.w, mats\[bone.x\], mx;^n MAD my, weights.w, mats\[bone.x+1\], my;^n MAD mz, weights.w, mats\[bone.x+2\], mz;^n \]\])^n^n TEMP opos;^n DP4 opos.x, mx, spos;^n DP4 opos.y, my, spos;^n DP4 opos.z, mz, spos;^n MOV opos.w, spos.w;^n^n @(if $arg2 \[result \[^n TEMP onormal;^n DP3 onormal.x, mx, snormal;^n DP3 onormal.y, my, snormal;^n DP3 onormal.z, mz, snormal;^n \]\])^n^n @(if $arg3 \[result \[^n TEMP otangent;^n DP3 otangent.x, mx, stangent;^n DP3 otangent.y, my, stangent;^n DP3 otangent.z, mz, stangent;^n \]\])^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>skelquatanim</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n skelanimlength = (min (- $maxvpenvparams (+ $reservevpparams 10)) $maxskelanimdata)^n result \[^n PARAM quats\[\] = { program.env\[ 10 .. @@(- (+ 10 $skelanimlength) 1) \] };^n @(if (&gt; $arg1 1) \[result ^"ATTRIB weights = vertex.attrib\[6\];^"\])^n ATTRIB bones = vertex.attrib\[7\];^n ADDRESS bone;^n TEMP dqreal, dqdual, dir;^n^n ARL bone.x, bones.x;^n @(if (= $arg1 1) \[result \[^n MOV dqreal, quats\[bone.x\];^n MOV dqdual, quats\[bone.x+1\];^n \]\] \[result \[^n MUL dqreal, weights.x, quats\[bone.x\];^n MUL dqdual, weights.x, quats\[bone.x+1\];^n ARL bone.x, bones.y;^n MAD dqreal, weights.y, quats\[bone.x\], dqreal;^n MAD dqdual, weights.y, quats\[bone.x+1\], dqdual;^n @(if (&gt;= $arg1 3) \[result \[^n ARL bone.x, bones.z;^n MAD dqreal, weights.z, quats\[bone.x\], dqreal;^n MAD dqdual, weights.z, quats\[bone.x+1\], dqdual;^n \]\])^n @(if (&gt;= $arg1 4) \[result \[^n ARL bone.x, bones.w;^n MAD dqreal, weights.w, quats\[bone.x\], dqreal;^n MAD dqdual, weights.w, quats\[bone.x+1\], dqdual;^n \]\])^n^n TEMP len;^n DP4 len.x, dqreal, dqreal;^n RSQ len.x, len.x;^n MUL dqreal, dqreal, len.x;^n MUL dqdual, dqdual, len.x;^n \]\])^n^n TEMP opos;^n XPD opos.xyz, dqreal, spos;^n MAD opos.xyz, spos, dqreal.w, opos;^n ADD opos.xyz, opos, dqdual;^n XPD opos.xyz, dqreal, opos;^n MAD opos.xyz, dqdual, dqreal.w, opos;^n MAD opos.xyz, dqreal, -dqdual.w, opos;^n MAD opos.xyz, 2, opos, spos;^n MOV opos.w, spos.w;^n^n @(if $arg2 \[result \[^n TEMP onormal;^n XPD onormal.xyz, dqreal, snormal;^n MAD onormal.xyz, dqreal.w, snormal, onormal;^n XPD onormal.xyz, dqreal, onormal;^n MAD onormal.xyz, 2, onormal, snormal;^n \]\])^n^n @(if $arg3 \[result \[^n TEMP otangent;^n XPD otangent.xyz, dqreal, stangent;^n MAD otangent.xyz, dqreal.w, stangent, otangent;^n XPD otangent.xyz, dqreal, otangent;^n MAD otangent.xyz, 2, otangent, stangent;^n \]\])^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>slime</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n editmat water^n editmat death^n obitwater ^"sucked on slime^"^n watercolour 0x182200^n waterfallcolour 0x002200^n waterfog 0^n waterspec 10^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>specular</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>start</b> <i>&lt;map&gt; &lt;mode&gt; &lt;muts&gt;</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to a given map with a specific mode and mutators; depending on privileges, this will force or vote for the map change, &lt;mode&gt; sets the mode type, &lt;muts&gt; sets the mutators according to a bitwise sum of mutator values, conveniently set using $modeidx\* vars and sums of $mutsbit\* vars, example: start bath $modeidxdeathmatch (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
mode $arg2 $arg3; map $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>stopautosave</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
noautosave = 1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>stype</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>survivor</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to survivor deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to a bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: survivor bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxdeathmatch (+ $mutsbitsurvivor $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>swapval</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n local tmp^n tmp = $$arg1^n $arg1 = $$arg2^n $arg2 = $tmp^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>takescreenshot</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
oldscreenshot 1; sleep 500 \[ screenshot ^"screenshot^"; oldscreenshot 0 \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tdm</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to team deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: tdm bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
teamdm $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>teamdm</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to team deathmatch on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: teamdm bath (+ $mutsbitinstagib $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
start $arg1 $modeidxdeathmatch (+ 0 $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>teamval</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>texturecull</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
removes all texures not used in the map from the map config file

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
compactvslots 1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>timetrial</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
requests a map change to time-trial on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: timetrial purge (+ $mutsbitjetpack $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
start $arg1 $modeidxtrial (+ 0 $arg2)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>tip1</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
press ^fs^fcSPACE^fS to ^fs^fyjump^fS and again in mid-air to ^fs^fypropel^fS yourself

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tip10</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
press ^fs^fcK^fS to ^fs^fysuicide^fS, this will reset you in ^fs^fytime-trial^fS and ^fs^fygauntlet^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>tip11</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
press ^fs^fcLSHIFT^fs^fw or ^fSC^fS to crouch while landing to ^fs^fyimpulse slide^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tip12</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
press ^fs^fcSPACE^fS during an ^fs^fyimpulse slide^fS to perform a ^fs^fyimpulse launch^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>tip13</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
when you're ^fs^foon fire^fS you can ^fs^fcjump in water^fS to put yourself out, crouch if necessary

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tip14</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
you're ^fs^fyless accurate^fS when ^fs^fyjumping^fS and ^fs^fymoving^fS, stop for a perfect shot

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>tip15</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
you can ^fs^fyclick these tips^fS to ^fs^fcget a new tip^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tip16</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
you can chat with the developers in ^fs^fc\#redeclipse^fS on ^fs^fcirc.freenode.net^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>tip17</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
share your own tips with the developers in ^fs^fc\#redeclipse^fS on ^fs^fcirc.freenode.net^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tip18</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
tips are ^fs^fccool^fS, you should ^fs^fyread them more often^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>tip2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
press ^fs^fcLSHIFT^fs^fw or ^fSC^fS to ^fs^fycrouch^fS, doing so while landing will perform a ^fs^fyimpulse slide^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tip3</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
press ^fs^fcMOUSE1^fS and ^fs^fcMOUSE2^fS to fire your weapon

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>tip4</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
press ^fs^fcR^fs^fw or ^fSMOUSE3^fS to ^fs^fyreload^fS your weapon, timing this can be crucial to survival

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tip5</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
press ^fs^fcE^fS to ^fs^fyuse items^fS and ^fs^fytriggers^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>tip6</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
press ^fs^fcLCTRL^fS to ^fs^fywalk^fS for better traction and accuracy

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tip7</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
press ^fs^fcQ^fS to ^fs^fywall run^fS, ^fs^fywall kick^fS, or ^fs^fymelee^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>tip8</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
press ^fs^fcRETURN^fs^fw or ^fST^fS to ^fs^fytalk^fS and ^fs^fcY^fS to only speak to ^fs^fyteammates^fS

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tip9</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
press ^fs^fcQ^fS while in the air to ^fs^fyfly-kick^fS enemies

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>tips</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
18

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>tmpt</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>togglegrid</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n case $gridbindswitch 3 \[^n showpastegrid 0; showcursorgrid 0; showselgrid 0; gridbindswitch = 0^n \] 2 \[^n showpastegrid 0; showcursorgrid 0; showselgrid 1; gridbindswitch = 3^n \] 1 \[^n showpastegrid 0; showcursorgrid 1; showselgrid 0; gridbindswitch = 2^n \] 0 \[^n showpastegrid 1; showcursorgrid 0; showselgrid 0; gridbindswitch = 1^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>togglesound</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
if (&gt; $mastervol 0) \[ mastervol 0; echo ^"sound off^" \] \[ mastervol 255; echo ^"sound on^" \]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>trial</b> <i>&lt;map&gt; \[&lt;muts&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
requests a map change to time-trial on a given map; \[&lt;muts&gt;\] optionally adds extra mutators according to bitwise mutator values, conveniently set using a sum of $mutsbit\* vars, example: trial purge (+ $mutsbitjetpack $mutsbitmedieval)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
timetrial $arg1 $arg2

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>universaldelta</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n delta = (format ^"delta\_%1\_%2^" (at $deltastates (getplayerstate)) $modifier)^n if (strcmp (getalias $delta) ^"^") \[^n delta = (format ^"delta\_%1\_%2^" (at $deltastates (getplayerstate)) $defaultmodifier)^n if (strcmp (getalias $delta) ^"^") \[^n delta = (format ^"delta\_%1\_%2^" (at $deltastates 0) $modifier)^n if (strcmp (getalias $delta) ^"^") \[^n delta = (format ^"delta\_%1\_%2^" (at $deltastates 0) $defaultmodifier)^n \]^n \]^n \]^n if (getalias $delta) \[ do \[@delta @arg1\] \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>varbit</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
varname = \[@\[arg1\]val\] ; guibitfield ^"^" $arg2 \[@arg1 $@varname\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>varbit2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
guilist \[^n varname1 = \[@\[arg1\]val1\]^n guibitfield ^"^" $varname1 $arg2 \[\[@@\[arg1\]1\] $@varname1\]^n varname2 = \[@\[arg1\]val2\]^n guibitfield ^"^" $varname2 $arg2 \[\[@@\[arg1\]2\] $@varname2\]^n\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>vardef</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
guitext $arg2 ; \[@\[arg1\]val\] = $$arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>vardef2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guitext $arg2^n \[@\[arg1\]val1\] = $\[@\[arg1\]1\]^n \[@\[arg1\]val2\] = $\[@\[arg1\]2\]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>varfld</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
varname = \[@\[arg1\]val\] ; guifield $varname $arg2 \[@arg1 $@varname\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>varfld2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
guilist \[^n varname1 = \[@\[arg1\]val1\]^n guifield $varname1 $arg2 \[\[@@\[arg1\]1\] $@varname1\]^n varname2 = \[@\[arg1\]val2\]^n guifield $varname2 $arg2 \[\[@@\[arg1\]2\] $@varname2\]^n\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>varhdef</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
guitext $arg2 ; \[@\[arg1\]val\] = (hexcolour $$arg1)

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>varhdef2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guitext $arg2^n \[@\[arg1\]val1\] = (hexcolour $\[@\[arg1\]1\])^n \[@\[arg1\]val2\] = (hexcolour $\[@\[arg1\]2\])^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>varincr</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
guilist \[^n varname1 = \[@\[arg1\]val1\]^n guibutton ^"^^fy-^" \[\[@@\[arg1\]1\] (- $@varname1 1)\]^n guifield $varname1 $arg2 \[\[@@\[arg1\]1\] $@varname1\]^n guibutton ^"^^fg+^" \[\[@@\[arg1\]1\] (+ $@varname1 1)\]^n varname2 = \[@\[arg1\]val2\]^n guifield $varname2 $arg2 \[\[@@\[arg1\]2\] $@varname2\]^n\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>varslist1</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
rotatemaps spawnrotate selfdamage teamdamage spawnhealth maxhealth maxhealthvampire actorscale minresizescale maxresizescale maxcarry regenhealth kamikaze pointlimit capturelimit captureresetdelay

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>varslist2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
defendlimit defendpoints defendoccupy defendflags bomberlimit bomberresetdelay bomberspeed gamespeed gravityscale liquidspeedscale liquidcoastscale floorcoastscale aircoastscale slidecoastscale movespeed movecrawl movepacing movejet movestraight movestrafe moveinair movestepup movestepdown jumpspeed impulsespeed impulselimit impulseboost

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>varslist3</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
impulsedash impulsejump impulsemelee impulseparkour impulseparkournorm impulseallowed impulsestyle impulsecount impulsedelay impulseslide impulsemeter impulsecost impulseskate impulsepacing impulsejet impulseregen impulseregencrouch impulseregenpacing impulseregenjet impulseregenmove impulseregeninair damagescale

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>varslist4</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
itemsallowed hitpushscale hitstunscale deadpushscale wavepushscale wavestunscale timelimit intermlimit votelimit duelreset duelclear duellimit itemspawntime itemspawndelay itemspawnstyle itemthreshold regendelay regentime enemyspawntime enemyspawndelay enemyspawnstyle spawngrenades spawnweapon instaweapon

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>varsmenu</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guifont ^"little^" \[^n guilist \[^n guilistsplit n 4 ^"1 2 3 4^" \[^n guilist \[^n guilist \[ looplist var $\[varslist@n\] \[vardef $var $var\] \]^n guistrut 2^n guilist \[ looplist var $\[varslist@n\] \[varfld $var 8\] \]^n \]^n if (= $n 4) \[^n guistrut 0.5^n guilist \[guistayopen \[^n guistrut 4^n guibutton ^"^^foreset all game variables^" \[resetvars\]^n \]\]^n \]^n \] \[guistrut 3\]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>vertexparam0</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
program.env\[16\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>vertexparam1</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
program.env\[17\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>vertexparam2</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
program.env\[18\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>vertexparam3</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
program.env\[19\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>vertexparam4</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
program.env\[20\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>vertexparam5</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
program.env\[21\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>vertexparam6</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
program.env\[22\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>vertexparam7</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
program.env\[23\]

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>vntyval</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice10snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
286

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice10str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
sorry

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice11snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
286

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice11str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
sry~

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice12snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
287

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice12str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
no problem

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice13snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
287

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice13str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
np~

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice14snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
287

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice14str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
no prob

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice15snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
288

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice15str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
no~

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice16snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
289

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice16str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
go go go

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice17snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
289

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice17str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
gogogo

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice18snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
290

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice18str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
hang on

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice19snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
291

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice19str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
thanks

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice1snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
277

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice1str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
argh

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice20snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
291

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice20str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
ty~

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice2snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
278

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice2str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
lucky shot

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice3snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
279

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice3str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
nice shot

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice4snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
280

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice4str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
boom

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice5snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
281

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice5str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
damn

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice6snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
282

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice6str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
haha

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice7snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
283

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice7str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
suck

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice8snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
284

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice8str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
pzap

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voice9snd</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
285

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voice9str</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
yes~

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>voices</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
integer alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
20

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>voteindex</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>votemenu</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n guipage vote 8 72 3.2 \[1\] (getvote) \[^n voteplayers = (getvote $i 0)^n votemode = (getvote $i 1)^n votemuts = (getvote $i 2)^n votemap = (getvote $i 3)^n voteself = 0^n loop j $voteplayers \[ if (= (getclientnum) (getvote $i 0 $j)) \[ voteself = 1 \] \]^n \] \[1\] \[^n guibutton ^"^^fwThere are no votes currently pending, ^^fgsubmit ^^fwone yourself^" \[showgui maps 1\] \[\] ^"chat^"^n \] \[^n guitip (format ^"press ^^fs^^fc%1^^fS to open this menu at any time^" (searchbinds ^"showgui maps 2^" 5 ^"or^" ^"^^fw^"))^n guistrut 0.5^n guilist \[^n guicheckbox ^"^^fcdynamic sort^" sortvotes; guistrut 1.5^n guicheckbox ^"^^focleanup list^" cleanvotes; guistrut 1.5^n guibutton ^"^^fyclear vote^" clearvote^n guispring^n guitext (format ^"^^fd\[ ^^fc%1 ^^fwvote%2 ^^fd\]^" $votenum (? (!= $votenum 1) ^"s^"))^n guistrut 1^n \]^n guistrut 0.25^n \] \[^n guistrut 0.125^n guimerge 72 \[^n guicenter \[^n guistrut 4 1^n votecolour = (? $voteself ^"^^fy^" ^"^^fw^")^n guicenter \[guifont ^"default^" \[guibutton (concatword $votecolour $voteplayers)\]\]^n guicenter \[guifont ^"little^" \[guibutton (format ^"%1vote%2^" $votecolour (? (!= $voteplayers 1) ^"s^"))\]\]^n \]^n voteimage = ^"textures/chat^"^n votepath = (listfind curmap $maplist \[|| \[=s $curmap $votemap\] \[=s \[maps/@curmap\] $votemap\] \[^n && \[&gt; $mapocta 0\] \[&gt; $hasoctapaks 0\] \[=s \[base/@curmap\] $votemap\]^n \]\])^n if (&gt; $votepath -1) \[ voteimage = (at $mappath $votepath) \]^n guistrut 1^n guiimage $voteimage ^"^" 1.5 1 ^"textures/chat^"^n guistrut 1^n guicenter \[^n gname = (gamename $votemode $votemuts 0 32)^n guifont ^"reduced^" \[ guibutton (format ^"^^fy%1 ^^favoted for on ^^fo%2^" $gname $votemap) \]^n guilist \[^n if (&gt; $voteplayers 0) \[^n guifont ^"reduced^" \[ guibutton ^"^^fwby ^" \]^n pname = ^"^"^n pmore = 0^n loop j $voteplayers \[^n if (&gt; (strlen $pname) 64) \[ pmore = (+ $pmore 1) \] \[^n append pname (format \[^"%1^"\] (getclientname (getvote $i 0 $j) 1))^n \]^n \]^n guifont ^"little^" \[ guibutton (concat (prettylist $pname) (? $pmore (concat ^"and^^fy^" $pmore ^"^^fwmore^"))) \]^n \] \[ guifont ^"reduced^" \[ guibutton ^"^^fano current votes^" \] \]^n \]^n \]^n \] \[^n if (= @voteself 1) \[ clearvote \] \[ start @@votemap @@votemode @@votemuts \]^n \] \[\]^n guistrut 0.125^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>votemenuinit</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
voteindex = 0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>votenum</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>vpstart</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n !!ARBvp1.0^n ^n OPTION ARB\_position\_invariant;^n ATTRIB opos = vertex.position;^n ^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>w</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>water</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmat water $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>water2</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editmat water2 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>water3</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
editmat water3 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>water4</b> <i>\[&lt;filter&gt;\]</i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
modifies the material properties for the selected cubes; &lt;filter&gt; limits the command to only affect cubes whose material match this {water, clip, ladder, etc.}

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
editmat water4 $arg1

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_COMPLETE

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>watershader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n specular = $arg2^n rgbfog = $arg3^n distort = $arg4^n combine = $arg5^n lazyshader 0 $arg1 \[^n @vpstart^n TEMP tc;^n PARAM campos = program.env\[0\];^n PARAM seconds = program.env\[1\];^n @(if $specular \[result ^"PARAM lightpos = program.env\[2\];^"\])^n^n DP4 result.texcoord\[0\].x, state.matrix.texture.row\[0\], opos;^n DP4 result.texcoord\[0\].y, state.matrix.texture.row\[1\], opos;^n @(if (&gt;= (strstr $arg1 ^"underwater^") 0) \[result \[^n SUB result.texcoord\[0\].z, program.env\[7\], opos.z;^n \]\] \[result \[^n SUB result.texcoord\[0\].z, opos.z, program.env\[7\];^n \]\])^n DP4 result.texcoord\[0\].w, state.matrix.texture.row\[3\], opos;^n MUL tc, vertex.texcoord\[0\], 0.1;^n MAD result.texcoord\[1\].xy, seconds, 0.04, tc;^n MAD result.texcoord\[2\].xy, seconds, -0.02, tc;^n SUB result.texcoord\[3\].xyz, campos, opos;^n @(if $specular \[result ^"SUB result.texcoord\[4\].xyz, lightpos, opos;^"\])^n^n MOV result.color, vertex.color;^n^n @fogcoord^n^n END^n \] \[^n @fpstart^n @(if $rgbfog \[result ^"OPTION ARB\_fog\_linear;^"\])^n TEMP he, light, cam, bump, invfresnel, temp, dudv;^n^n ATTRIB projtc = fragment.texcoord\[0\];^n ATTRIB tc1 = fragment.texcoord\[1\];^n ATTRIB tc2 = fragment.texcoord\[2\];^n ATTRIB camts = fragment.texcoord\[3\];^n @(if $specular \[result ^"ATTRIB lightts = fragment.texcoord\[4\];^"\])^n^n @(normalize cam camts)^n @(if $specular \[result \[^n @(normalize light lightts)^n ADD he.xyz, cam, light;^n @(normalize he he)^n \]\])^n^n TEX dudv, tc1, texture\[2\], 2D;^n MAD dudv.xy, dudv, 2, -1;^n^n @distort^n^n @(if $specular \[result \[^n PARAM specfactor = 96;^n^n DP3\_SAT he.x, he, bump;^n POW he.x, he.x, specfactor.w;^n^n MUL light.w, program.env\[4\].x, light.w;^n RCP\_SAT light.w, light.w;^n MAD light.xyz, light.w, -program.env\[3\], program.env\[3\];^n \]\])^n^n @combine^n^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>weapcollidevars</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^"traced^" ^"hit proj^" ^"hit owner^" ^"impact geom^" ^"impact plyr^" ^"impact shot^" ^"bounce geom^" ^"bounce plyr^" ^"bounce shot^" ^"drill geom^" ^"drill plyr^" ^"drill shot^" ^"stick geom^" ^"stick plyr^"

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>weapindex</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>weapindexdelta</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n weapindex = (+ $weapindex $arg1)^n if (&lt; $weapindex 0) \[ weapindex = (+ $weapindex $weapidxnum) \]^n if (&gt;= $weapindex $weapidxnum) \[ weapindex = (- $weapindex $weapidxnum) \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>weapmenu</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
^n guistayopen \[^n guilist \[^n weap = (getweap $weapindex -1)^n guilist \[^n guiimage (getweap $weapindex 1) \[weapindexdelta 1\] 1.25 0 ^"textures/nothumb^"^n guistrut 0.5^n guilist \[^n guifont default \[ guitext \[@weap (@\[weapindex\]/@(+ $weapindex $weapidxnum))\] \]^n guilist \[^n guibutton ^"^^fo&lt;prev^" \[weapindexdelta -1\]^n guistrut 1^n guibutton ^"^^fynext&gt;^" \[weapindexdelta 1\]^n \]^n \]^n \]^n guistrut 1^n guifont ^"little^" \[^n guilist \[^n guilist \[^n vardef \[@\[weap\]name\] ^"name^"^n varhdef \[@\[weap\]colour\] ^"colour^"^n varhdef2 \[@\[weap\]partcol\] ^"partcol^"^n varhdef2 \[@\[weap\]explcol\] ^"explcol^"^n vardef \[@\[weap\]add\] ^"add^"^n vardef \[@\[weap\]max\] ^"max^"^n vardef2 \[@\[weap\]sub\] ^"reduced^"^n vardef2 \[@\[weap\]attackdelay\] ^"attackdelay^"^n vardef \[@\[weap\]reloaddelay\] ^"reloaddelay^"^n vardef2 \[@\[weap\]damage\] ^"damage^"^n vardef2 \[@\[weap\]speed\] ^"speed^"^n vardef2 \[@\[weap\]power\] ^"power^"^n vardef2 \[@\[weap\]time\] ^"time^"^n vardef2 \[@\[weap\]projdelay\] ^"projdelay^"^n vardef2 \[@\[weap\]guideddelay\] ^"guideddelay^"^n vardef2 \[@\[weap\]escapedelay\] ^"escapedelay^"^n vardef2 \[@\[weap\]explode\] ^"explode^"^n \]^n guistrut 2^n guilist \[^n varfld \[@\[weap\]name\] 16^n varfld \[@\[weap\]colour\] 16^n varfld2 \[@\[weap\]partcol\] 7^n varfld2 \[@\[weap\]explcol\] 7^n varfld \[@\[weap\]add\] 16^n varfld \[@\[weap\]max\] 16^n varfld2 \[@\[weap\]sub\] 7^n varfld2 \[@\[weap\]attackdelay\] 7^n varfld \[@\[weap\]reloaddelay\] 16^n varfld2 \[@\[weap\]damage\] 7^n varfld2 \[@\[weap\]speed\] 7^n varfld2 \[@\[weap\]power\] 7^n varfld2 \[@\[weap\]time\] 7^n varfld2 \[@\[weap\]projdelay\] 7^n varfld2 \[@\[weap\]guideddelay\] 7^n varfld2 \[@\[weap\]escapedelay\] 7^n varfld2 \[@\[weap\]explode\] 7^n \]^n \]^n \]^n \]^n guistrut 2^n guifont ^"little^" \[^n guilist \[^n guilist \[^n guilist \[^n vardef2 \[@\[weap\]rays\] ^"rays^"^n vardef2 \[@\[weap\]spread\] ^"spread^"^n vardef2 \[@\[weap\]spreadz\] ^"spreadz^"^n vardef2 \[@\[weap\]aiskew\] ^"aiskew^"^n vardef2 \[@\[weap\]fragweap\] ^"fragweap^"^n vardef2 \[@\[weap\]flakdamage\] ^"flakdamage^"^n vardef2 \[@\[weap\]fragrays\] ^"fragrays^"^n vardef2 \[@\[weap\]fragtime\] ^"fragtime^"^n vardef2 \[@\[weap\]fragspeed\] ^"fragspeed^"^n vardef2 \[@\[weap\]cooked\] ^"cooked^"^n vardef2 \[@\[weap\]guided\] ^"guided^"^n vardef2 \[@\[weap\]extinguish\] ^"extinguish^"^n vardef2 \[@\[weap\]radial\] ^"radial^"^n vardef2 \[@\[weap\]residual\] ^"residual^"^n vardef \[@\[weap\]reloads\] ^"reloads^"^n vardef \[@\[weap\]carried\] ^"carried^"^n vardef \[@\[weap\]zooms\] ^"zooms^"^n vardef2 \[@\[weap\]fullauto\] ^"fullauto^"^n vardef2 \[@\[weap\]taperin\] ^"taperin^"^n vardef2 \[@\[weap\]taperout\] ^"taperout^"^n vardef2 \[@\[weap\]elasticity\] ^"elasticity^"^n vardef2 \[@\[weap\]reflectivity\] ^"reflectivity^"^n vardef2 \[@\[weap\]relativity\] ^"relativity^"^n \]^n guistrut 2^n guilist \[^n varfld2 \[@\[weap\]rays\] 7^n varfld2 \[@\[weap\]spread\] 7^n varfld2 \[@\[weap\]spreadz\] 7^n varfld2 \[@\[weap\]aiskew\] 7^n varfld2 \[@\[weap\]fragweap\] 7^n varfld2 \[@\[weap\]fragdamage\] 7^n varfld2 \[@\[weap\]fragrays\] 7^n varfld2 \[@\[weap\]fragtime\] 7^n varfld2 \[@\[weap\]fragspeed\] 7^n varfld2 \[@\[weap\]cooked\] 7^n varfld2 \[@\[weap\]guided\] 7^n varfld2 \[@\[weap\]extinguish\] 7^n varfld2 \[@\[weap\]radial\] 7^n varfld2 \[@\[weap\]residual\] 7^n varfld \[@\[weap\]reloads\] 16^n varfld \[@\[weap\]carried\] 16^n varfld \[@\[weap\]zooms\] 16^n varfld2 \[@\[weap\]fullauto\] 7^n varfld2 \[@\[weap\]taperin\] 7^n varfld2 \[@\[weap\]taperout\] 7^n varfld2 \[@\[weap\]elasticity\] 7^n varfld2 \[@\[weap\]reflectivity\] 7^n varfld2 \[@\[weap\]relativity\] 7^n \]^n \]^n \]^n guistrut 3^n guilist \[^n guilist \[^n guilist \[^n vardef2 \[@\[weap\]waterfric\] ^"waterfric^"^n vardef2 \[@\[weap\]weight\] ^"weight^"^n vardef2 \[@\[weap\]radius\] ^"radius^"^n vardef2 \[@\[weap\]kickpush\] ^"kickpush^"^n vardef2 \[@\[weap\]hitpush\] ^"hitpush^"^n vardef2 \[@\[weap\]aidist\] ^"aidist^"^n vardef2 \[@\[weap\]partsize\] ^"partsize^"^n vardef2 \[@\[weap\]partlen\] ^"partlen^"^n vardef \[@\[weap\]frequency\] ^"frequency^"^n vardef2 \[@\[weap\]wavepush\] ^"wavepush^"^n vardef2 \[@\[weap\]delta\] ^"delta^"^n vardef2 \[@\[weap\]trace\] ^"trace^"^n vardef2 \[@\[weap\]headmin\] ^"headmin^"^n vardef2 \[@\[weap\]whipdamage\] ^"whipdamage^"^n vardef2 \[@\[weap\]torsodamage\] ^"torsodamage^"^n vardef2 \[@\[weap\]legdamage\] ^"legdamage^"^n vardef2 \[@\[weap\]fragscale\] ^"fragscale^"^n vardef2 \[@\[weap\]fragspread\] ^"fragspread^"^n vardef2 \[@\[weap\]fragrel\] ^"fragrel^"^n vardef2 \[@\[weap\]fragjump\] ^"fragjump^"^n vardef2 \[@\[weap\]fragoffset\] ^"fragoffset^"^n vardef2 \[@\[weap\]fragskew\] ^"fragskew^"^n \]^n guistrut 2^n guilist \[^n varfld2 \[@\[weap\]waterfric\] 7^n varfld2 \[@\[weap\]weight\] 7^n varfld2 \[@\[weap\]radius\] 7^n varfld2 \[@\[weap\]kickpush\] 7^n varfld2 \[@\[weap\]hitpush\] 7^n varfld2 \[@\[weap\]aidist\] 7^n varfld2 \[@\[weap\]partsize\] 7^n varfld2 \[@\[weap\]partlen\] 7^n varfld \[@\[weap\]frequency\] 16^n varfld2 \[@\[weap\]wavepush\] 7^n varfld2 \[@\[weap\]delta\] 7^n varfld2 \[@\[weap\]trace\] 7^n varfld2 \[@\[weap\]headmin\] 7^n varfld2 \[@\[weap\]whipdamage\] 7^n varfld2 \[@\[weap\]torsodamage\] 7^n varfld2 \[@\[weap\]legdamage\] 7^n varfld2 \[@\[weap\]fragscale\] 7^n varfld2 \[@\[weap\]fragspread\] 7^n varfld2 \[@\[weap\]fragrel\] 7^n varfld2 \[@\[weap\]fragjump\] 7^n varfld2 \[@\[weap\]fragoffset\] 7^n varfld2 \[@\[weap\]fragskew\] 7^n \]^n \]^n \]^n guistrut 3^n guilist \[^n loop n 2 \[^n guilist \[^n push n (at ^"collide flakcollide^" $n) \[^n guilist \[^n vardef2 \[@\[weap\]@n\] (format ^"^^fw%1^" (at \[collision: ^"flak collision:^"\] @@n))^n looplist a $weapcollidevars \[guitext $a\]^n \]^n guistrut 2^n guilist \[^n guitext ^"^^fwpri^^fa/^^fwalt^"^n loop b (listlen $weapcollidevars) \[^n varbit2 \[@\[weap\]@n\] (&lt;&lt; 1 $b)^n \]^n \]^n \]^n \]^n if (= $n 0) \[guistrut 2\]^n \]^n \]^n \]^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>weapmenuinit</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
weapindex = 0

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>weapval</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>worldshader</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
string alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
^n stype = 0^n if (&gt;= (strstr $arg1 ^"env^") 0) \[stype = (+ $stype 2)\]^n shader $stype $arg1 \[^n @vpstart^n ADD result.texcoord\[0\].xy, vertex.texcoord\[0\], program.env\[0\];^n MUL result.texcoord\[1\].xy, vertex.texcoord\[1\], @lmcoordscale;^n^n @arg2^n^n \#pragma CUBE2\_shadowmap^n \#pragma CUBE2\_dynlight^n @fogcoord^n \#pragma CUBE2\_water^n^n END^n \] \[^n @fpstart^n OPTION ARB\_fog\_linear;^n TEMP diffuse, lm;^n TEX diffuse, fragment.texcoord\[0\], texture\[0\], 2D;^n TEX lm, fragment.texcoord\[1\], texture\[1\], 2D;^n^n \#pragma CUBE2\_shadowmap lm^n \#pragma CUBE2\_dynlight lm^n^n @arg3^n^n MUL diffuse, diffuse, program.env\[6\];^n @(if (&lt; $numargs 4) \[result \[MUL result.color, diffuse, lm;\]\] \[result $arg4\])^n^n \#pragma CUBE2\_water^n^n END^n \]^n

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>x</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>xhairblend</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>xhairblendstorage</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>xhairprefix</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>xhairsize</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
<b>xhairtex</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:#ECF9FF;">
IDF\_UNKNOWN

</td>
</tr>
<tr>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
<b>y</b> <i>&lt;nowiki&gt;&lt;\#undocumented\#&gt;</nowiki></i>

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
\#undocumented\#

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL alias

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
NULL

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
n/a

</td>
<td style="padding:0 0.5em 0 0.5em; background-color:lightyellow;">
</td>
</tr>
</table>

