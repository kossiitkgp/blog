+++
categories = ["Engineering"]
date = 2018-06-05T00:00:00+05:30
description = ""
draft = false
slug = "virtual-box-and-vagrant"
title = "Learning command line basics and Virtual box"
+++

Hello people!

So I was looking up for a course that would teach me the basics of linux command
line and I got across this one. Though I already know the basics of command line
but just in case I was missing something, I thought to go through it once.

https://in.udacity.com/course/linux-command-line-basics--ud595

This course is for a beginner. It’s not preferred to go through it, if you
already know about the commands. But I have mentioned the brief summary of it
and key points which I didn’t know.

In the start of the course, I found something really fascinating, how to set up
a virtual machine on my own computer. It made me feel really good that I can set
up a new computer on my own system. Sounds interesting, right? Why Virtual
Machine? This link will tell you the reasons why people prefer to use the
virtual machine for their work.

So in this blog, I will mention all those things which I learnt something new
today.

1.  To set up the virtual machine, follow the above link. In the first few slides,
you will be carried through the instructions how to set the virtual environment
up. I wont mention that here.
1.  `cat <file_name>` will display the content of the file on the terminal itself.
1.  `man <command_name>` for eg: man apt will give you the manual pages (detailed
help) of the command apt. you can look through it in case of a doubt. *Note*:
Many commands also have a `-h` flag which shows help. `man` shows a “detailed
version” of the help.
1.  Line based commands: There some commands which when typed doesn’t return back
the cursor, eg: `bc` (used to access the calculator). You got to type quit or
Ctrl+D for exiting from that interface.
1.  There is a command `less <file_name>` which is used to access a text file page
wise rather than using `cat <file_name>` which displays the whole text. This is
especially useful when dealing with long texts.

<span class="figcaption_hack">Relative Path v/s Absolute Path</span>

6. `cd` without arguments is a shortcut to take you to your home directory.

7. `mkdir` is used to make a directory (You all must be knowing that). But
`rmdir`is used to remove an empty directory (Note empty). If you wish to remove
a directory with files in it, you will have to do that recursively using `rm -r
<directory name>`*.*

8. `ls` is used to list all the files in the current directory. `ls -a` will
list all the hidden and non-hidden files in the directory and `ls -al` will give
all the details of the files. Here -a and -al are called the flags.

9. `touch` will create an empty file in the current directory.

10. `cp` copies the file in the required directory. Syntax is like `cp test.txt
Downloads` . Here the second word is the destination folder. `cp -r docs
more_docs` copies the content of of docs to more_docs. Note the -r flag standing
for recursive.

11. `date` gives the current date.

So to wrap up, using the virtual machine really amazed me. Using it, I can store
files hidden, in case needed. I even learnt about some new commands of the
command line.

Keep learning! Cheers!

* This article is written by [Nikhil Choudhary](https://github.com/nikhilch23)*

