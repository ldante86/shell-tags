<h2 id="shell-tags">shell-tags</h2>
<h3 id="description">DESCRIPTION</h3>
<p>These scripts parse bash scripts for functions and provide various output.</p>
<h3 id="files">FILES</h3>
<table>
<col width="22%" />
<col width="70%" />
<thead>
<tr class="header">
<th align="left">Files</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">htags</td>
<td align="left">HTML page of function names and line numbers.</td>
</tr>
<tr class="even">
<td align="left">jtags</td>
<td align="left">Create JSON array: {&quot;script&quot;:[&quot;function&quot;, linenumber]}</td>
</tr>
<tr class="odd">
<td align="left">function-list</td>
<td align="left">Create 'script'-index.txt with function index.</td>
</tr>
</tbody>
</table>
<h3 id="notes">NOTES</h3>
<p>Bash function format:</p>
<pre><code>myfunc()
{
   : # code
}</code></pre>
