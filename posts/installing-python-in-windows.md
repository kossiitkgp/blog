+++
categories = ["Engineering"]
date = 2018-08-30T00:00:00+05:30
description = ""
draft = false
slug = "installing-python-in-windows"
title = "Installing Python in Windows"
+++

# Installing Python in Windows

This article deals with installing Python on Windows. Even though Python can be
installed in Windows, it is recommended to use Linux, to use Python and develop
applications. While I have used windows 10 for the demonstration of
installation, this can also be referred for installing the same in Windows 7.I
have installed both Python2 and Python3.

Let’s begin!

### Download the Python Software

Download the required files from the Python’s website
[[Python2](https://www.python.org/ftp/python/2.7.15/python-2.7.15.msi) |
[Python3](https://www.python.org/downloads/release/python-370/)].

### Installing Python 2

I have used the following steps to install Python 2

![](https://cdn-images-1.medium.com/max/800/1*UOiYWaNMJTgLIlIayw-OJQ.jpeg)
<span class="figcaption_hack">Choose Install for all users</span>

![](https://cdn-images-1.medium.com/max/800/1*en8i8Wf80eINFhv5n6Q1EQ.jpeg)
<span class="figcaption_hack">Keep the folder where Python will be installed in C drive</span>

<span class="figcaption_hack">Keep the default options, and click Next</span>

<span class="figcaption_hack">Python will be installed</span>

### Installing Python 3

After installing Python 2, we will install Python 3. Note that if you want to
install only Python 2( which is not recommended), then you have to append the
`python.exe` in the PATH variable.

<span class="figcaption_hack">Choose Add Python3.7 to PATH</span>

<span class="figcaption_hack">Python will be installed</span>

<span class="figcaption_hack">Python is installed.</span>

### Running Python 2 and Python 3

You can start Python 2, using `py -2` command in your command terminal. For
Python 3 use, `py -3`.

<span class="figcaption_hack">Python 2 and Python 3 is up and running !</span>

*****

### Caveat! Differences between Py2 and Py3

Note: This part is just for beginners who would be installing python for the
very first time. Of course, there are many more differences between the two
version.

* **print** : In python 2, the print was a statement, and hence one could print
any item, and wrapping them in curly brackets , was optional. However, due the
misuse of the above flexibility, the print statement was changed into a
function, and thus restricting the misuse of the above said advantage.
* **Integer division **: The integer division in python2 takes two numbers, and
returns the integer portion, as it discards the decimal part. This was certainly
not obvious, as `3/2` should return `1.5` and not `1`. Python 3 ensured that the
integer division returns values in float, rather than int.
* **Speed** : Python 3.3 performs at approximately the same speed as Python 2.7,
although some benchmarks measure the new language as being much faster.

* This article is written by [Yash Sharma](https://github.com/yashrsharma44)*
