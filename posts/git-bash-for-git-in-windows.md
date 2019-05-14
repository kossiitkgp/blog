+++
categories = ["Engineering"]
date = 2018-10-05T00:00:00+05:30
description = ""
draft = false
slug = "git-bash-in-windows"
title = "Using Git Bash for git in Windows"
+++

This blog post helps in installing git bash, for using git in windows. Git for
Windows provides a BASH emulation used to run Git from the command line. *NIX
users should feel right at home, as the BASH emulation behaves just like the
“git” command in LINUX and UNIX environments.

### Steps to install Git for Windows

1.  Click on the link to [[download](https://git-scm.com/downloads)]. This will
redirect to a page, where git will be automatically downloaded.

![](https://cdn-images-1.medium.com/max/800/1*r84LXjhlRvyL31uA9B0ULw.jpeg)
<span class="figcaption_hack">First window for installation</span>

![](https://cdn-images-1.medium.com/max/800/1*b_Gpwccl8Ju3cMIOdv2WrA.jpeg)
<span class="figcaption_hack">You can check off Git GUI, if you do not need it</span>

![](https://cdn-images-1.medium.com/max/800/1*Svkldsu4asg-CxUhuM-PWw.jpeg)
<span class="figcaption_hack">If you are having any preferable text editor, you can choose one.</span>

![](https://cdn-images-1.medium.com/max/800/1*D06k45WD3tmHG6Qc-AT9nQ.jpeg)
<span class="figcaption_hack">Choose option 1 , unless you know what you are doing</span>

![](https://cdn-images-1.medium.com/max/800/1*qtzvCVmTW1nv_cQdCJDdGw.jpeg)

![](https://cdn-images-1.medium.com/max/800/1*RSQfiZw7Gxtopd6JqMdDCg.jpeg)

![](https://cdn-images-1.medium.com/max/800/1*Y38aZdXgII6mHs7Q0FIR9g.jpeg)

![](https://cdn-images-1.medium.com/max/800/1*dsn3cGji9Y4HJDvLUWwsXA.jpeg)

![](https://cdn-images-1.medium.com/max/800/1*IPJen_NLY8WjxsAwS-eZrg.jpeg)
<span class="figcaption_hack">You can skip bleeding edge technology</span>

![](https://cdn-images-1.medium.com/max/800/1*0f20vDHE6R593r3D67anYw.jpeg)
<span class="figcaption_hack">Git is being installed</span>

![](https://cdn-images-1.medium.com/max/800/1*1vG0qWZ6ej92TWpa7SyvMw.jpeg)
<span class="figcaption_hack">Voila ! Git is installed</span>

### Some Steps before we start using Git

Note, we have to set username, and proxy settings, for using git in windows.

#### Configure git:

1.  After you’ve installed git properly, it’s time to set some variables for the git
configuration. You’ve to do this only once. Follow the commands on terminal.

2. User settings to be set —

     // Setting system.proxy in git                                               git config --global https.proxy

3. Now check `git config --list` to know you've set the variables correctly.

Congratulations, you’ve git up and running on your computer. Now, it’s time to
start learning git.

* This article is written by [Yash Sharma](https://github.com/yashrsharma44)*
