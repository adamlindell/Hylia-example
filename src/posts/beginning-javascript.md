---
tags:
- mentoring
title: Beginning JavaScript
date: 2019-11-01T22:59:00.000+00:00
ogImage: ''

---
## Where to begin?

JavaScript is the world's most misunderstood language, and for good reason. I mean, let's start with the name: Java and JavaScript have little in common. They weren't invented at the same place (Java was invented at Sun, JavaScript was invented at Netscape). They have very different opinions on fundamental language features like types, objects, and programming paradigms. Java was trying to position itself as the language of the web (after first failing to become the language of "smart appliances" in the early 90's). In 1994, everyone thought that web applications would be dominated by Java Applets.

[![xkcd comic where a man says "my motto is to move fast and break things!" and a listing of all the jobs he's been fired from](/images/xkcd-movefast.png)](https://xkcd.com/1428/)

Netscape wasn't sold on applets and they were looking for a (proprietary) killer feature for Navigator 2.0. Being a company that believed in _move fast and break things_ before it was cool, they gave designer Brendan Eich **10 days** to develop ~~Mocha~~ ~~LiveScript~~ JavaScript. The Netscape marketing team named it JavaScript so that they could ride the Java hype train. Which worked only too well.

## Footguns aplenty

From this crazy beginning, JavaScript is almost shockingly high quality. The design goals were to make a language that was tolerant of faults, easy for non-programmers to pick up, and not too syntactically different from the popular languages of the day so that "real" programmers wouldn't be scared off.

### Helpful to a fault

However, the same features that made the language "easy for non-programmers" turned out to make the language very difficult to use for complex applications. Things like automatic semicolon insertion are nice affordances to keep less-than-perfect programs running… unless the language _misinterprets_ your intentions, wandering off to do Lord knows what. JavaScript can sometimes seem to have a mind of its own.

### Deceptive curly braces

In order to appeal to 1990's programmers, JavaScript was intended to look like other curly-brace languages like Java and C. And yet, it behaves very differently. It has a lot more in common with the ancient language LISP (most closely resembling Scheme) than any of the other curly-brace languages. This ruse worked a little too well – developers were so comfortable with JavaScript's syntax that they began to use it without first learning how the language worked. Since the internals of the language are different, JavaScript again appeared to be haunted – doing strange things with seemingly normal code. Check out

[https://javascriptwtf.com/](https://javascriptwtf.com/ "https://javascriptwtf.com/") for plenty of wild examples.

## Hope Springs Eternal

What's the lesson here?

**JavaScript requires discipline to learn**. You must ignore its superficial similarities to languages you may know and _actually learn it_.

Also, because of its beginnings, **JavaScript requires discipline to write**. There are plenty of bad parts and weird corner cases in the language. As developers, we have enough complexity to deal with in our lives (more on this later). We want to have the code be as easy to understand as possible, which means using the good parts of the language and avoiding the bad. In coming posts, I will lay out to good resources as I find them to develop a solid foundation.

***

#### More Background

If you want to learn more about the history of JavaScript and of software in general, I recommend a series of lectures called "Crockford on JavaScript". His [first talk](https://www.youtube.com/watch?v=JxAXlJEmNMg "video of the first Douglas Crockford Lecture") begins with the Jacquard loom in 1801 and ends with the era of the personal computer. If you like history but not _that_ much history, his [second talk](https://www.youtube.com/watch?v=RO1Wnu-xKoY "Video of the second Crockford On JavaScript lecture") covers the history of JavaScript.