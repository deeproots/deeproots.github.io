---
title       : What Needs Done
layout      : page
permalink   : /what-needs-done/
---
There's an example of this in the [Introduction to Vim](/vim-intro/), but here's the gist of what I have found to work well: I open the text of the book (the Markdown file) and the PDF of the original pages on my laptop screen, usually with the original book on the left and the text on the right. I find it most comfortable to split the screen at about 40/60 in favor of the text, because the majority of the time will be spent in the text - the original is just there for reference and double checking.

As you can see from the screenshot, I find that it's helpful to keep the text fairly large, for a couple reasons: (a) it's easier on your eyes for long editing sessions, and (b) it's easier to spot the subtle issues, like punctutation errors or incorrect spacing.

### Chapter Headings

The first thing I do when I get the raw text of a new book is go through it and find the chapter breaks, and make sure those are correct. It shouldn't take long, but it makes working through the rest of the book so much easier; if you're editing the text of a whole book without the chapter headings, it's easy to get lost in where your at, and then when you need to refer to the originals for clarification it can be very frustrating to find your place.

The other benefit of doing it this way is that you get the "lay of the land" with the book - you get to see how the parts/chapters progress, are there no poems or lots of poems, does every chapter start with a verse or end with a prayer, etc.

Here's an example from *Weekday Religion* by J.R. Miller: I start the editing process by scrolling through the book and adding/correcting the chapter headings. As you can see, I've come to chapter 2, and there are a few issues: The chapter title is in caps, which we don't want, the dropcap O in the original book has not been correctly picked up by the OCR, and the small caps  in the original has translated into all caps in the text, and the bottom of the dropcap O on the second line of the original has resulted in some garbage characters in the first sentence.

This is where there is a bit of a judgement call for you - is it faster to just delete all this and retype it, or try to correct it? It depends on the book and sometimes chapter by chapter. In this case, the obvious choice is just to retype it all. 

I jump in at the beginning of the word "find" and delete it back up to "cannot" - it's not missing any words, just extraneous characters and line break to remove. Then with the cursor at the beginning of "young", delete everything up to the II, and retype it, leaving **2 blank lines above** the heading and **1 below.**

If you do this at the very beginning of the book process, it will be the biggest help for you and anyone else who comes along in the future.

### The Case of the Missing Preface

I use a tool called [Calibre]() to convert the books from ePubs to plain text so that we can start the editing process. And for some reason in the transition, the preface of the book seems to be missing. I'm working on trying to track down this problem, but in the meantime, the best thing to do is go ahead and type up the missing  
