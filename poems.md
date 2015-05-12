---
title       : Poems
layout      : page
permalink   : /poems/
---
Because they generally occur with an italic typeface in the original, the beautiful poems in these books are often rife with errors. Not only that, but there are always spacing issues that we have to deal with, and quotation marks to delete. If there's a bunch of them, it can be a real time suck, but hopefully we'll make it as efficient as possible.

### Step by Step

1.  Starting at the bottom, delete the bottom quotation mark enclosing entire poem.
2.  Working up, delete blank lines except for breaks in verses.
3.  Change any internal singe quotes (i.e. dialog) back into double quotes.
4.  Delete top quotation mark that enclosed the entire poem.
5.  Add `\startpoem` to the line above the poem.
6.  Add `\stoppoem` to the line below the poem.

I know it may seem like a lot, so let's go through it via an example.

### Example

![](/assets/img/poems-1.png)

Here we have a poem in our example book, *Weekday Religion* by J.R. Miller. So, starting with **Step 1**, we can see that this first quotation mark is one enclosing the whole poem - there isn't any dialog here. So we get rid of that. **Step 2** is getting rid of all the blank lines - there aren't any line breaks in the original, so we'll get rid of all of them. **Step 3** doesn't apply in this case, because there are no internal quotation marks. So the result after the first three steps should look like this:

![](/assets/img/poems-2.png)

Now, you can see that the OCR engine did not correctly capture the opening quotation mark here - it's both bold and italic on the original page, and the computer understood it to be a `■` instead of a double quote. That's a character that should never exist in any of our books, so it's an easy catch. We just delete back to the beginning of the line, and that takes care of **Step 4**. And then for **Steps 5 + 6**, we just add `\startpoem` immediately  before the poem, and `\stoppoem` immediately  after. The result should look like this:

![](/assets/img/poems-3.png)

And that's how to markup a poem. I know that it's a bit of a pain, but these poems play such a pivotal role is some of these books for driving the point home in a poignant and artistic way. I've been overcome with joy and convicted to repent while taking these steps on various poems in these books!
