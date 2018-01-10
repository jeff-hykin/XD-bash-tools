# Sub
Its like sed, but modern and simple. It uses ruby regular expressions to make replacements. When given 1 argument it functions like grep.

### examples
`echo "hello" | sub 'e' 'a'`<br>
\>>> `hallo`<br>
<br>
If there is a file 'test.txt' with `hello world` in it then<br>
`sub 'world' 'internet' test.txt`<br>
would change the contents of test.txt to `hello internet` 

# Installation 
Make sure you have ruby installed. Then put the 'sub' file somewhere in your path, ex: /usr/bin
