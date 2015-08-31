---
layout: post
title: What are web components?
---

	With the proliferation of new javascript frameworks using ES6 and ES7 elements,
	implementations of React constantly growing in terms of market share, awaiting the
	arrival of Angular 2.0, and the promises made by the developers Aurelia, many people
	already refactoring their old web apps and building new ones almost entirely out of web
	components. So now, the question many people might ask is what exactly are web components?

	Web components are basically pieces of an app that only serve a specific purpose, making them completely modular in use. Since they are a part of most modern browsers, there are no requirements of other libraries or frameworks to use them. Most common uses of web components
	According to MDN, 
	Web components are made out of the following four technologies:
		
		* Custom Elements
		* HTML Templates
		* Shadow Dom
		* HTML Imports

	Since HTML templates and imports are pretty much self explanatory, I'll explain Custom Elements
	and Shadow Dom in detail.

	Custom elements are the newest additions to HTML, specifically being integrated into evergreen
	browsers to handle web components, basically it allows the developer to create their own 
	HTML elements with whatever traits they so desire or to inherit traits from native elements,
	kind of like psuedoclassical or prototypal inheritance.

	Shadow Dom is a little more tricky in understanding,

