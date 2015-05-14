---
title       : "Save & Submit Changes"
layout      : page
permalink   : /save-and-submit/
---
Now that you've [forked and cloned](/fork-and-clone/) the `books` repo, you can edit it on your own computer. But then how do you get those changes back onto your own Github account, and then back to the `deeproots` account? That's what this is all about:

### Commit and Sync

The lingo of Github was scary to me for a long time - I didn't learn how to use it because the terminology seemed so foreign. But don't be afraid - once you get the hang of this, it becomes second nature, and this is where Github starts to become really powerful.

The best way to show you would be to work through an example. Here I've just edited a poem in *Weekday Religion* by J.R. Miller. Once I save the file, you can see that it now shows up in the Github, with a nice display of the changes I made - you can see what I deleted in pink, and what I added in green.

![](/assets/img/pull-request-1.png)

All the files that you've changed since the last time you've synced up with Github will be listed in this panel. Now, notice at the bottom left where it says "Summary", "Description", and "Commit to master", because that's where we focus our attention next.

A "commit" is, by Github's own definition, "a snapshot of your code [or book!] at a point in time." So basically, all you're doing in those two little boxes is giving a brief description of the changes that you made.

For our purposes, unless you did something that requires more explanation, the "Summary" portion will suffice - in this case I'll just say "Corrected poem." because that's what I did - I just followed the steps outlined in the [poems](/poems/) documentation - delete blank lines, delete enclosing quotation marks, add markup to top and bottom.

![](/assets/img/pull-request-2.png)

After I'm satisfied with the summary and description of my changes, I'll then hit the "Commit to master" button directly below.Then as you'll notice, the file disappears from this list. But that doesn't mean that it's been uploaded to Github yet - now look at the top of the sidebar on the left, and you'll see that it now says "(0) Change - (1) Unsynced". 

![](/assets/img/pull-request-3.png)

So, the next step is to go to the top right corner of the app and hit the "Sync" button. And *now* we're done - give it a few seconds, then go to the Github website, and you'll see that your changes have been "pushed" - the files on your computer and on Github are now the same.

### Submitting Your Changes

Imagine that I've spent an hour or so working on this books. I've probably committed changes a few times during that hour - maybe once after I finished fixing paragraphs, again when I finished fixing poems, and once more when I finished punctuation. Now I'm done for the day and I want to submit my changes to the main Deep Roots repo. The way I do that is by submitting a **pull request** - it's me saying, "Hey, I've made some good changes - I'm *requesting* that you *pull* them into the main project!"

So, assuming that you have committed all your changes and synced with Github, the next step is to go to *your* Github account, and then to the `books` repo you just synced those changes to, like I am here, at `lukewil/books`. Now, at the top of the files, you can see there's this small button that says, "Pull Request".

![](/assets/img/pull-request-5.png)

If you click that, you'll be taken to a screen where you can quickly see the differences between the deeproots version of the files and your changes. If everything looks good, just hit that big green button that says, "Create pull request".

![](/assets/img/pull-request-6.png)

Then you'll have the opportunity to give more details as to what the pull request is all about. If it's simple, it's fine to keep it simple. If there's something you wondered about whether you did something correctly, this would be the place to mention that. And then, hit the "Create pull request" button again, and you are done.

![](/assets/img/pull-request-7.png)

I (or others as the team grows larger, hopefully) will look at the pull request, make sure that everything is right, and approve. If something's not quite right, the great thing about the system is that we can talk about it right there in the comments of the pull request itself.

And that's how it works. To recap, once you've made changes to a book, you commit those changes, sync the changes to Github. When you're at a good stopping point or milestone, submit a pull request so that we can merge your changes into the main repository and everyone can benefit from your work!
