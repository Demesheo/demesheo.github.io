---
layout: post
title: Enhancing your Sublime Text Editor 2 
---

	In this post I am going to give directions on how to add SublimeLinter, a program that checks your code syntax and structure as you write it to point out any errors to you. After this first part I will also show how you can add a build system to sublime instead of having to copy and paste your code into the console everytime you want to test something.

	So the first thing you want to do is open up your console and navigate from the root folder to 
	```bash
	Library/Application Support/Sublime Text 2/Packages/
	```

	Then once you are there, run
	```bash
	git clone https://github.com/SublimeLinter/SublimeLinter.git
	```

	This will create a new package in your sublime package folder called SublimeLinter. So once you restart your sublime text editor, go ahead and navigate to preferences -> package settings -> SublimeLinter -> Settings - User .

	Once in there you have a few options you can change, me personally I like my errors to be outlined and to have the linter constantly running instead of just on load or save. To do so I made the following changes.

	On line 13, I changed "sublimelinter" : "load-save",
	to be "sublimelinter" : true,

	On line 73, I changed "sublimelinter_mark_style": "none",
	to be "sublimelinter_mark_style": "outline",

	On line 107, I changed "sublimelinter_popup_errors_on_save": false,
	to be "sublimelinter_popup_errors_on_save": true,

	So now I can see all my errors outlined as I type out my code and upon saving, all of my errors are listed on screen so I can make the appropriate changes before commiting and pushing my code to github.
