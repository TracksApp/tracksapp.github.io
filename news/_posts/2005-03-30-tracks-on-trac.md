---
layout: post
date: 2005-03-30 
author: bsag 
title: "Tracks on Trac" 
categories: [news] 
comments: true
sharing: true
footer: true
---

I've got some good news; the cool people at [TextDrive](http://textdrive.com/) have set up a [Trac](http://projects.edgewall.com/trac/) (yes, I know those names are going to get confusing) installation for me [here](http://dev.rousette.org.uk/wiki). Trac is an Open Source project to help developers to share their work with others and accept contributions of bug reports, feature requests or patches.
 

It's a really nice system in which you can view already submitted tickets, submit your own tickets and browse the source files in development, which are versioned using Subversion. There's also a wiki, in which I've started to write a guide to installing Tracks and all the dependencies, along with a few other snippets. Eventually, I'll try to extract everything that's still relevant from the old Dokuwiki [install](http://www.rousette.org.uk/projects/wiki/) and include it. Until the dust has settled, only I can edit the Trac wiki, but I hope to open editing up to everyone in due course.

In the meantime, please [create tickets](http://dev.rousette.org.uk/newticket) for any bugs you've found, features you'd like to suggest and so on. Please add as much detail as possible, particularly with bug reports; "it doesn't work" isn't very helpful. You can submit anonymously if you like, but if you don't mind providing it, an email address would be very helpful if I need to get in touch with you to find out more detail on your report. Also, please try to scan the previous tickets to see if your bug/feature has been suggested before submitting a duplicate request.

I'm really excited about this. I've had three very helpful patches recently from (in no particular order) Lolindrath, Jim Ray and Nicholas Lee, so contributions to the project are really starting to take off. Using Trac will make it much easier for people to make a contribution, even if it is a contribution of ideas rather than code, and it will be much easier for me to keep track of (sorry) than the old wiki.

One word of caution; while you can check out a copy of the version that I'm currently developing from the trunk using <code>svn</code>, please be aware that it is a very bleeding edge version. I frequently break stuff in there while fixing other things, and it's not suitable for actual use. Anyway, if you're curious or want to generate a patch to add a new feature against the latest version, the URL is:

<pre>
<code>
svn co --username=guest http://www.rousette.org.uk/svn/tracks-repos/trunk/tracks
</code>
</pre>

The username is 'guest'. Once you've checked out the latest trunk, added your fix, **tested it** and found that it works, just issue the following command in the root of the tracks directory:

<pre>
<code>
svn diff > /pathto/your_name_patch_description.patch
</code>
</pre>

Once you've submitted a ticket describing what your patch does, you should be able to view the ticket and use the 'Attach file' button to attach your *.patch file (I'm not sure why that's not possible when you create the ticket).

Go mad with it! 
