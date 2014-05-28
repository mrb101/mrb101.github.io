---
layout: post
title: "Using Linux Software on Mac OS X"
author: bas
date: 2014-05-28 12:50:39 +02:00
---

<p>One of the reasons I love GNU/Linux is the vast amount of software packages available to it. Some software packages are awesome and most developers and programmers can't live without after using it.</p>

### How can I use Linux software in Mac ?!

<p>Some Developers prefer Mac OS X over Linux OS due to some applications Like Adobe Suit or iTunes to accompany their iPhone and some for the love of its stability, performance and speed. But they would like to use the tools which is available in Linux and Unix like Systems. Due to the fact that OS X itself is a Unix Like OS. Makes it easy to accomplish the goal.</p>

<p>There are more than one Package Manager for OS X to help install Unix packages.</p>

* HomeBrew
* Fink
* MacPorts

<p> I prefer HomeBrew. And I have used it for quite some time. and its a simple installation process. First make sure to install Command Line Tools for Xcode.</p>

1 Install Xcode from the App Store
2 Start Xcode on the Mac.
3 Choose Preferences from the Xcode menu.
4 In the General panel, click Downloads.
5 On the Downloads window, choose the Components tab.
6 Click the Install button next to Command Line Tools. 

<p>Now you are ready to install HomeBrew. Copy and paste the following command in your terminal window.</p>

	ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

<p>Home brew is simple very simple to use. Lets see how to look for a package.</p>

	brew search PackageName

<p>And to install a package we type.</p>

	brew install PackageName

<p>You can update the list of packages by typing.</p>

	brew update

<p>And to check HomeBrew</p>

	brew doctor

<p>Easy eh ? If you use a different package manager please share your thoughts. If you have any questions please drop a comment below</p>