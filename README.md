## shell-tags

### DESCRIPTION

These scripts parse bash scripts for functions and provide various output.

### FILES

----------		---------------------------------------------------
Files			Description
----------		---------------------------------------------------
htags			HTML page of function names and line numbers.

jtags			Create JSON array: {"script":["function", linenumber]}

function-list		Create 'script'-index.txt with function index.
----------		---------------------------------------------------

### NOTES

Bash function format:


~~~
myfunc()
{
   : # code
}
~~~
