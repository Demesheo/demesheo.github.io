---
layout: post
title: Enhancing your Sublime Text Editor 2 
---

	In this post I am going to give directions on how to add SublimeLinter, a program that checks your code syntax and structure as you write it to point out any errors to you. After this first part I will also show how you can add a build system to sublime instead of having to copy and paste your code into the console everytime you want to test something.

	So the first thing you want to do is open up your console and navigate from the root folder to 
	``` bash
	Library/Application Support/Sublime Text 2/Packages/
	```

	Then once you are there, run
	``` bash
	git clone https://github.com/SublimeLinter/SublimeLinter.git
	```

	This will create a new package in your sublime package folder called SublimeLinter.