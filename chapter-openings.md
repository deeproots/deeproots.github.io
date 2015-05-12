---
title       : Chapter Openings
layout      : page
permalink   : /chapter-openings/
---
Some authors begin every chapter with a specific Scripture, quote, or poem. We want to make sure these are highlighted correctly, not interpreted as the beginning of the main text block.

### General Syntax

In the case of chapter openings, we're **breaking from the standard Markdown** that we're using most other places. Instead, we'll use some syntax from ConTeXt, the file format that we're using to create PDFs for download and print. 

*Abide in Christ* by Andrew Murray is a book where each chapter begins with a specific verse or two. We'll use it here as an illustration of how to handle it well.

![](/assets/img/chapter-openings-1.png) 

Just like everything else in Markdown, we want to make sure that there's at least one blank line between the chapter heading and the chapter openning. Then one line with the code `\startchapteropening`, then the content, and the a closing `\stopchapteropening`. And it's as simple as that. Here's an example screenshot: 

![](/assets/img/chapter-openings-2.png) 

This rule is in the [poems documentation](/poems/) as well, but I'll mention it here to cover all bases: We use the same kind of markup, `\startpoem` and `\stoppoem` to (you guessed it!) start and stop poems. But it's important to note here that **`chapteropenings` trumps `poems`**. Chapter openings will get a different typographical treatment than poems that are inline with the rest of the text, and so it's more important for our purposes that it be marked as a proper chapter opening than as poem.

In many books these chapter openings are a key point in setting up what the author is going to be saying, and we want to set them apart from the rest of the text well so that they can serve their purpose and be as clear and un-distracting as possible.  
