---
title       : Introduction to Vim
layout      : page
permalink   : /vim-intro/
---
To start with, let me just say this: without a doubt, this bit of the editing stack is the least essential and the most controversial, but I decided to include it because it completes the trifecta of tools that I'm using to edit these books faster than I ever thought possible.

The kicker: **the code Vim is based on was written in 1976.** In tech years, that may be older than some of the books in this project!

The satisfying irony of using an old text editor to edit old books aside, this is not some hipster vintage computing mumbo-jumbo. I would toss any bit of this whole toolbox aside and use something else if the next thing was more effective or efficient. I just have yet to see that tool, so Vim is what **I'm** using, and I want to the share the why and how with you.

*Note*: If you'd rather skip learning vim for now and just use another editor, there are alternatives listed at the bottom of the page.

As I've gotten more comfortable with it more reasons have emerged, but I'll just give you **two reasons for my love for Vim…**

### 1. Everything is a keyboard shortuct. 

And what's a shortcut – it's a way to your desired destination faster!

When Vim (and it's predecessor, vi) was created, the mouse wasn't around - the keyboard was all there was. And while the mouse (and now trackpad) is great, keyboard shortcuts are still order of magnitude more efficent when multipled times a few thousand times a week.

Let me give you an example: here's a page from *When the Song Begins* by J.R. Miller, where the OCR engine mistook a page break for a new paragraph - this text needs to be joined back together.

![](/assets/img/paragraph-error-page.png)

In a **more traditional text editor**, I would grab my mouse, move the cursor to the bottom paragraph, hopefully hitting on just the right spot, then drag to highlight the extra line, hopefully not grabbing more or less than I intended. Then hit backspace to delete it, check to make sure it looks right, then moving on.

**In Vim**, though, I'm strolling through the text using the down arrow with my right hand, and scrolling the original PDF pages at the same time with my left hand on the trackpad. I notice the error, my cursor is already in the right spot. I hit A to go to the beginning of the line, then backspace 3x and I'm done. 

I know it seems like not a big difference, but just like playing an instrument or tying your shoes, once you do it a few hundred times muscle memory takes over and you start doing it withought thinking. 

(In full-on Billy Mays voice...) But WAIT, there's more!

### 2. It's ridiculously customizable.

The improvement above is helpful, but not enough to start using Vim. But here's the thing: the frequency varies from book to book, but that's one of the more common errors you'll see – it'll happen at least once in almost every book. Rather than typing `A`, then 3 backspaces, I can just create a custom keyboard shortcut to do it for me. 

There's this beautiful little file called `.vimrc`, where all your customizations go. I've uploaded my vimrc so that you can use it and have all the same cool shortcuts I've made for editing these books.

For all the Vim customizations it has what's called a **leader key** – mine is comma. It tells vim that there is a shortcut coming. And for this case, I chose to use `j` - it's easy for me to remember because I'm trying to **join** these two paragraphs.

So, back to the example. I'm scrolling along, and I see the error. Oops, those two paragraphs are actually one. As long as the cursor is anywhere in the paragraph, I hit `,j`, and I'm on my way, as best I can time it in about half a second or so. It's so fast almost doesn't break my momentum while I'm scrolling, and requires zero brain power (a good thing!).

Is that amazing or what? When I first discovered these customizations, I spontaneously I broke out in the Doxology! 😉I have shortcuts like these all programmed in for the most common problems you'll find in these books - and if you want to learn the intricacies of Vim, you'll the using them like a boss in no time at all.

### Vim Alternatives

If you don't feel like jumping into an entirely new text editor right now, I can completely understand and appreciate that. So here are a few alternatives…

As we talked about in the [Introduction to Markdown](/markdown-intro/), Markdown files are nothing more than plain text files. So any plain text editor can edit a `.md` file as well, even something as simple as Notepad on the PC or TextEdit on the Mac (although I would strongly not recommend either of those). The most important feature to look for will be the search - does it highlight well, is it easy to go to the next occurance, or do you have to scroll and find them? If it supports regular expressions, even better - all the ones listed below do. And don't worry if you don't know what regular expressions are - it's just an advanced way of find stuff, I'll have a list of them you can copy and paste.

Here are some great Vim alternative editors that you can considering using:

-   [TextWrangler](http://www.barebones.com/products/textwrangler/) (Mac) - Free
-   [Atom](https://atom.io) (Mac or Linux) - Free
-   [Sublime Edit](http://www.sublimetext.com) (Mac, Linux, or Windows) - Free
-   [Notepad++](http://notepad-plus-plus.org) (Windows) - Free

I hope that is helpful - obviously I'm pretty passionate about the way that Vim has improved my efficiency, but I'm very interested to know what you end up using!
