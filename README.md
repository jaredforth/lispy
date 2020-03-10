# Build Your Own Lisp

Learn C and language design

## Compiling

In the project root, run `cmake .` then `make`. 

## Troubleshooting 

#### Cannot Find <editline/readline.h>

If the following error is encountered: 

> source/parsing.c:19:10: fatal error: editline/readline.h: No such file or directory #include <editline/readline.h>

The [readline](https://tiswww.case.edu/php/chet/readline/rltop.html) library needs to be installed. 

On Ubuntu:

```
sudo apt-get install libedit-dev
```

#### /usr/bin/ld: cannot find -lreadline
 
If the following error is encountered: 

> /usr/bin/ld: cannot find -lreadline
> collect2: error: ld returned 1 exit status

On Ubuntu: 

```
sudo apt-get install libreadline-dev
```
