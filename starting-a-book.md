---
title       : Starting a Book
layout      : page
permalink   : /starting-a-book/
---
So you've forked and cloned the Deep Roots project, and found a book you want to work on. **Now what?** Well, here's the workflow that I've found to be best for me.

To start with, you'll notice that project is organized by `author > book > files`. When you open a book folder you'll see a few files: 

-   `original.pdf` --- This is the images of the original book pages. You'll open this and refer to it often in editing the text.
-   `book.txt` --- This is the editable, [Markdown](/markdown-intro/) version of the book.
-   `metadata.yaml` --- This is the file that holds the metadata for the book. Usually it will already be complete and you probably won't need it anyway - it's more for the publishing process.

The setup that works best for me is to have both the text of the book (the Markdown file) and the PDF of the original pages on my laptop screen, usually with the original book on the left and the text on the right. I find it most comfortable to split the screen at about 40/60 in favor of the text, because the majority of the time will be spent there - the original is just for reference and double checking.

As you can see from the screenshots below, I find it helpful to keep the text fairly large, for a couple reasons: (a) it's easier on your eyes for long editing sessions, and (b) it's easier to spot the subtle issues, like punctutation errors or incorrect spacing.

### Chapter Headings

The first thing I do when I get the raw text of a new book is go through it and insert the correct chapter breaks. It doesn't take long, and it makes working through the rest of the book so much easier; if jump in to full blown edit mode without the chapter headings in place, it's easy to get lost in relation to the whole. Then when you need to refer to the originals it can be very frustrating to find your place.

The other benefit of inserting the chapter breaks first is getting the "lay of the land" with the book - you get to see how the book progresses, the structure - you know what to expect when you get into full blow proofreading.

![](/assets/img/chapter-heading-1.png)

Here's an example from *Weekday Religion* by J.R. Miller: I start the editing process by scrolling through the book and adding/correcting the chapter headings. As you can see, I've come to chapter 2, and there are a few issues: The chapter title is in CAPS, which we don't want, the dropcap O in the original book has not been correctly picked up by the OCR, and the small caps in the original has translated into CAPS in the text, and the bottom of the dropcap O on the second line of the original has resulted in some garbage characters in the first sentence.

Now there's a split-second judgment call - is it faster to just delete all this and retype it, or try to correct it? It depends on the book and sometimes even chapter by chapter. In this case, the obvious choice is just to retype it all. 

I jump in at the beginning of the word "find" and delete it back up to "cannot" - it's not missing any words, just extraneous characters and line break to remove. Then with the cursor at the beginning of "young", delete everything up to the II, and retype it, leaving **2 blank lines above** the heading and **1 below.** It should end up looking like this…

![](/assets/img/chapter-heading-3.png)

If you do this at the very beginning of the book process, it will be the biggest help for you and anyone else who comes along in the future.

### The Case of the Missing Preface

I currently use a tool called [Calibre](http://calibre-ebook.com) to convert the books from ePubs to plain text so that we can start the editing process. And for some reason in the transition, the preface of the book seems to be missing. I'm working on trying to track down this problem, but in the meantime, if you come across a book with a missing preface, the best (only) thing to do is go ahead and type up the missing part manually. :-(

And now we have a book, most likely still with major issues… but at least the chapter headings are there, and its missing preface has been restored. Now onto the [main show](/basic-editing/).
