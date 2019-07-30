# Day 1 of Learning Python

I’m marking today and the official day I start to learn Python programming. I’ll be working my way through Linux Academy’s Intro to Python Development Course and sprinkling in some exercises from the book Python Crash Course, 2nd edition.

I can’t tell you how many times I’ve forgotten how to exit the REPL in python. Well, that stops today.

```>>> exit()```

Either use the exit function or **Ctrl+D**.

At the beginning of a python script, you can place the ‘shebang’ on the first line. This indicates to the interpreter that you want to use the python version in your path.

```#!/usr/bin/env python3.7```

Now, you don’t need to hard code the exact path to the executable.

It’s a good idea to create a bin folder in your home directory. This can be a place you put your python tools. To run them without the .py extension, you can put your home/bin folder in your path, if it’s not already there.

Be sure to make the script executable.
```
chmod u+x
export PATH=$PATH:$HOME/bin
echo $PATH
```
Now you can run the  script from bin.

How to comment in python:

Add a hash before the line of code or as a trailing comment after a line of code, either in the REPL or in a script to comment it out.

**Strings:**

Strings in Python can be created with either single or double quotes.


```
>>>'This is a string'
>>>"This is also a string"
```
You can also create multl-line strings with triple single quotes.

With all the examples I’ve gone over today, the one most used is to clear the REPL. On my linux machine, I use **Ctrl+L**. On my Mac, I can use both **Ctrl+L** and **Command+K** to clear the screen.