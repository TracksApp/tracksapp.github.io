---
layout: post
date: 2005-01-09 
author: bsag 
title: "Subversion access available" 
categories: [news] 
comments: true
sharing: true
footer: true
---

I've managed to get Subversion access set up for Tracks. At the moment, you can only checkout from the 'tags' directory using the username 'guest' and password 'guest'. You can't check your changes back in--if you'd like to be able to contribute to the project, please let me know (tell me your preferred username and pasword), and I'll add access for you. My proposal is that the 'trunk' directory is just for me to break things in <img src="http://www.getontracks.org/images/smileys/wink.gif" width="19" height="19" alt="wink" style="border:0;" />, while the 'tags' directory is for people to checkout stable releases. The 'branches' directory will be for people to contribute their fixes and code additions.
 

If you want to checkout the stable 1.01 release of Tracks (see [Download](http://www.rousette.org.uk/projects/downloads/) page for details of what's in the new release), you can enter the following in a terminal (assuming that you have a [Subversion client](http://subversion.tigris.org/) on your machine):

<pre>
<code>
cd ~/Sites
svn co --username=guest http://www.rousette.org.uk/svn/tracks-repos/tags/tracks-1.01/tracks
</code>
</pre>

You'll get the following prompt, at which you should enter the password 'guest' (without quotes):

<pre>
<code>
Authentication realm: <http://www.rousette.org.uk:80> rousette.org.uk
Password for 'guest':
</code>
</pre>

Subversion will then copy the directory 'tracks' into ~/Sites. Make sure that you don't over-write any version you want to keep! I've made a few changes to the config/* files and the logs directory to ease updating with Subversion, so please read tracks/README_FIRST/ and tracks/doc/README.txt carefully before you start using it. 
