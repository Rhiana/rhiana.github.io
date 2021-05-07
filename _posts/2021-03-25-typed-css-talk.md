---
layout: presentation
ref: "typed-css2021"
title:  "Move over TypeScript, here comes TypedCSS!"
subtitle: ["WWC | March 2021", "Hover Conference | Apr 2021"]
video: "https://slides.com/rhianaheppenstall/move-over-typescript-here-comes-typedcss/embed"
---

Have you ever wondered how a browser makes sense of CSS properties and values? 

Turns out by parsing strings. Everything is a string: 50%, string. 2px, string. 0.5, string. #FFF, string. 

So what happens when the browser can't work out what the string is?  

width: 24asd;  

It fails silently, warning us with the generic "invalid property value" message. But what if we could assign types to the values? So the browser knew what it was expecting and what was wrong with the value we entered.  

This is where the CSS Typed Object Model comes in. It sits under the umbrella of the CSS Houdini API's and assign types to CSS values. So the browser knows it's expecting a number, colour or keyword. This allows for more control over attributes and for more useful errors. 

In this talk I'm going to take you through the CSS Typed OM and examples of how we can start using and benefiting from TypedCSS. 

[Slides on slides.com](https://slides.com/rhianaheppenstall/move-over-typescript-here-comes-typedcss)

