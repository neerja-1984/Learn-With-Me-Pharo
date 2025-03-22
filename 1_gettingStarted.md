"opens a small window with the text "hello world""

'hello world' asMorph openInWindow

```smalltalk
"a simple web scrapper"

    ZnClient new
        url: 'https://en.wikipedia.org/w/index.php';
        queryAt: 'title' put: 'neerjs';
        queryAt: 'action' put: 'edit';
        get 
```	
-----------------------------------------------------------

```smalltalk
"on creating  multi line exection -> select both and print it"

    1000 factorial
    / 999 factorial
    + 1

"anything which is in red -> not recognized by system eg. Colox"
"anything which is in blue -> not recognized by system eg. Color"
```

--------------------------------------------------

"for debugging videos see : W4 Live E"