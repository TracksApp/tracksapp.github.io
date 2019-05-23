---
layout: post
date: 2008-06-15 
author: bsag 
title: "Tracks moves to GitHub!" 
categories: [news] 
comments: true
sharing: true
footer: true
---

I'm happy to say that Tracks has now moved to GitHub. The subversion repository is still available as a read-only repository, but all new development will happen via <a href="http://git.or.cz/">Git</a> at  <a href="http://github.com/bsag/tracks/tree">GitHub</a>. The main reason for this move is to make it much easier for people to contribute to the project. Anyone can clone the repository and submit patches, but to make life even easier, you can sign up for a free account at GitHub and then fork Tracks. GitHub provides a 'pull request' button, so when you've added something cool or fixed a bug, hit the button and we'll pull in your changes. Git makes merging **much** easier than Subversion, even if the codebase has moved on a bit since you created the patch.

The latest stable version of Tracks can still be downloaded as a .zip file (see the download link in the sidebar). If you don't want to install Git, but you are feeling adventurous and want to get the very latest development version, you can use the 'Download' button on the GitHub page to get a tarball of the project.

To clone Tracks, change to a directory in which you want to store Tracks (e.g. ~/Sites):

<pre>
<code>
git clone git://github.com/bsag/tracks.git
cd tracks
</code>
</pre>

If (when!) you produce a cool new feature or fix a bug, create a patch. If you develop in a branch called 'experiment':

<pre>
<code>
git diff master..experiment > my_feature.patch 
</code>
</pre>

Then attach my_feature.patch to a ticket.

Or you can sign up for a free account on github and fork Tracks using the convenient button. You can then use the button to issue a pull request for your changes to be pulled into the main repository. 

 
