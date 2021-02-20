---
categories: ["Engineering"]
date: "2017-03-02T00:00:00+05:30"
description: ""
draft: false
slug: "breaking-github-down"
title: "Breaking GitHub Down"
---

During my mid semester exams, one night I was getting bored so I decided to
check how to break the most used code hosting website
[GitHub](https://github.com/). I wrote a
script[[1]](https://github.com/DefCon-007/Commiter-source) to add infinite
commits to a repository named
“Commiter”[[2]](https://github.com/DefCon-007/Commiter). It added a dot at the
end of a text file after every commit. The script pushed to the master branch
after every 10,000 commits and then after 1,00,000 commits it deleted the
repository and then cloned it back with just the last commit. I had to do it
because after a large number of commits the directory size was quite
large(approx 7–9 GBs).

With the help of this script I was able to find three bugs on GitHub after which
they blocked my repository[[2]](https://github.com/DefCon-007/Commiter) .

1.  **Z-index for commit label of contribution graph was not proper** :

Below is the screenshot of the issue I am talking about.

![](https://cdn-images-1.medium.com/max/800/1*RTWPIaRI0H0hm0FCwxsZlg.png)
<span class="figcaption_hack">Issue #1</span>

The label for the commit number should be above the graph. I got the following
response for this issue.

![](https://cdn-images-1.medium.com/max/800/1*nlqHSF2LRW8qJ5t3J34cvg.png)
<span class="figcaption_hack">Reply for issue #3</span>

**2. Latest commit info was not loading :**

After some days the I noticed that the GitHub was failing to load the latest
commit information on the repository homepage.

![](https://cdn-images-1.medium.com/max/800/1*Z4JGEWJ5rZYt_xMtsTu_oA.png)
<span class="figcaption_hack">Issue #2</span>

And for this issue I got the following reply.

![](https://cdn-images-1.medium.com/max/800/1*ZS_cheHLvv5xxdFYQyuGEA.png)
<span class="figcaption_hack">Reply for issue #2</span>

**3. Contributions graph failing to load :**

According to me this was a major bug. The contributions graph stopped loading.
It showed the below screen for hours and then the page said “Failed to load
contributions graph”.

![](https://cdn-images-1.medium.com/max/800/1*H7bPVHj9h4VJn5ABHz9JGQ.png)
<span class="figcaption_hack">Issue #3</span>

Sadly this was the last issue I was able to track. After reporting this people
at GitHub disabled access to my repository. The reason stated by them was :

> The repository you’re inquiring about, DefCon-007/Commiter, has been deemed
> abusive to our system and we have disabled it.

> Large numbers of commits do not lend themselves well to versioning with Git and
> performance issues with a repository of this size can endanger the availability
of your repo as well as other user’s repositories. Additionally, the pattern of
your commits is very different than that which Git was meant to handle, and
therefore consumes far more resources than a normal Git repository of its size.

And at the end they clearly mentioned that the repository access will not
enabled again.

P.S. : I was able to reach around 6,567,567 commits.

So this was my story how I used my mid semester exam frustration to do some
mischief with GitHub.

References :

[1]
[https://github.com/DefCon-007/Commiter-source](https://github.com/DefCon-007/Commiter-source)

[2][https://github.com/DefCon-007/Commiter](https://github.com/DefCon-007/Commiter)

*This article is written by [Ayush Goyal](https://github.com/Defcon-007)*
