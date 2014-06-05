

*******************************************************
How do I fix the indentation of an entire file in Vi?
>gg=G
or
>1G=G 
(That should indent all the lines in the file. 
1G takes you the first line, 
= will start the auto-indent 
and the final G will take you the last line in the file.)



*****************************************************
How to search for an exampleString?
/exampleString  
*****************************************************
How to search BACKWARDS for an exampleString?
?exampleString
*****************************************************
How to get to the next search result?
n
*****************************************************
How to get to the previous search result?
N
*****************************************************
How to undo a change?
u
*****************************************************
How to save and quit the file?
:wq
*****************************************************
How to add a new line below current line?
o
(that is a small o)
*****************************************************
How to add a new line above current line?
O
(that is a capital o)
*****************************************************
How to delete 23 lines?
23dd
*****************************************************
How to show the file name and line number?
:f
*****************************************************
How to remove leading white space?
:'a,.s/^\s\+
*****************************************************
How to list all marks?
:marks
*****************************************************
How to mark a line locally with a?
ma
*****************************************************
How to replace a string?
:s/string/replaceString/
*****************************************************
How to jump to mark a?
'a
*****************************************************
How to jump back?
"
*****************************************************
How to comment out all lines betwen mark a and current line? (with #)
:'a,. s/^/#/
*****************************************************
How to start the visual block mode?
ctrl+v
*****************************************************
What is the beginning of a line?
^
*****************************************************
What is the end of a line?
$
*****************************************************
How to comment out all lines betwen mark a and current line? (with //)
:'a,. s/^/\/\/
-> you have to escape slash with backslash
*****************************************************

*****************************************************

*****************************************************

*****************************************************

*****************************************************

*****************************************************

*****************************************************

*****************************************************

*****************************************************

*****************************************************

*****************************************************

*****************************************************

*****************************************************

*****************************************************
