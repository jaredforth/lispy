# Build Your Own Lisp

Learn C and language design

## Compiling

In the project root, run `cmake .` then `make`. 

## Troubleshooting 

**Cannot Find <editline/readline.h>**

If the following error is encountered: 

> source/parsing.c:19:10: fatal error: editline/readline.h: No such file or directory #include <editline/readline.h>

The [readline]() library needs to be installed. 