# pypastebin


What it does?
------
PyPastebin is a tool that allows you to generate a pastebin url inside a shell.

Prerequisites
-----
* A shell :)
* Python3.x
* requests module
  * If you don't have `requests`, you can install it running in a shell:
    ```
    pip3 install requests
    ```

Usage
-----
```
$ cat pypastebin.py | python3 pypastebin.py

Output:
The url is: http://dpaste.com/xxxxxx
```

TODO
-----

* Add the options for choosing different syntaxes [text by default]
* Add the options for choosing different expires [1 by default]
* Choose a different pastebin [dpaste by default]
