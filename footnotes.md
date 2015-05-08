---
title       : How to Handle Footnotes
layout      : page
permalink   : /footnotes/
---
Ahh, footnotes. They may be the biggest time suck in this whole project. Why? Because of the way they are printed (small at the bottom of the page) and because of the way they're marked (unusual characters like `*`, `†`, `‡`, `§`, `‖`, AND in superscript), they almost always come with significant problems that need to be fixed. 

### Footnotes in Markdown

The formatting for using footnotes in Markdown is like this:

    Here is a footnote reference,[^1] and another.[^longnote]
    
    [^1]: Here is the footnote.
    
    [^longnote]: Here is the other footnote.

So you put the footnote marker (`[^1]`) inline with the text, and then you put the matching marker with a semicolon and space
in front of the text of the footnote: (`[^1]: `)

As you can see in the example above, it doesn't really matter what you put after the `^`, just as long as they match and
there isn't more than one in the book. To avoid the duplication problem, my custom is just to go sequentially through
numbers. 

### Step by Step

So you're scrolling along, working your way through a book, when lo and behold, there's the dreaded footnote. Here is what you should do:

1.  Look at the original book and find the footnote marker on the page.
2.  Navigate to the end of that word in the text.
3.  Add the Markdown footnote marker there.
4.  Highlight the footnote text and cut it.
5.  Rejoin the interuppted paragraph, if necessary.
6.  Paste the footnote text.
7.  Add the correct Markdown markup for the footnote.
8.  Feel the satisfaction of a footnote well done.

Let's work through it with an example. From *Workday Religion* by J.R. Miller, here's a footnote:

![](/assets/img/footnotes-1.png)

It's easy to see where the footnote link belongs in this case - it's just two lines above the footnote in the original, and
the asterisk was picked up collectly by the OCR engine. However, the footnote was treated as just another paragraph, which
means it has split the correct paragraph in two.

So, following the steps above, we've already found where the footnote link should be and see that word in the text (steps 1 and 2). Now, for
**Step 3**, we delete the asterisk and add the footnote marker: `[^1]`. We're following the *Chicago Manual of Style* here, which
states that the footnote marker should always come after the punctuation, except for a dash. So in this case we put it after the comma, like so:

![](/assets/img/footnotes-2.png)

Now for **Steps 4 and 5**, we'll cut the text of the footnote, and rejoin the paragraph that had been seperated. We end up with
this:

![](/assets/img/footnotes-3.png)

Now for **Step 6**, we paste back in the footnote text, below the now complete paragraph. It'll look like this:

![](/assets/img/footnotes-4.png)

Everything's almost in place - now all we need to is remove the original footnote marker in the text (the `*`) and replace it
with the proper markup that matches what's in the text - **Step 7**. In this case, that'll be `[^1]:`. So the final product looks like this:

![](/assets/img/footnotes-5.png)

And there you have it - a footnote that will render correctly to the web, in eBooks, and in print. 

And the quote in this footnote is pretty great, I might add - when we're choosing a field of labor, Lord, let us be willing
to go "where nobody else is willing to go!"
