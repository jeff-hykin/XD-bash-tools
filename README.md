# What
These are some tools that make the basics of bash easier. For example 'show' is a more readable form of ls and 'sub' is a more friendly version of sed.

# Installation 
Make sure you have ruby installed. Then put the each of the files somewhere in your path, ex: /usr/bin, then make sure you have permission to execute that file, and that no one has permission to edit the file. 


# Commands

### show
Just type 'show' in any directory and it will show files/folders and links.

### sub
Uses ruby regular expressions to make replacements. When given 1 argument it functions like grep.

##### examples
`echo "hello" | sub 'e' 'a'`<br>
\>>> `hallo`<br>
<br>
If there is a file 'test.txt' with `hello world` in it then<br>
`sub 'world' 'internet' test.txt`<br>
would change the contents of test.txt to `hello internet` 


