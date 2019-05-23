---
layout: post
date: 2005-01-03 
author: bsag 
title: "New! Version 1.0 of Tracks released" 
categories: [news] 
comments: true
sharing: true
footer: true
---

I've just uploaded the next major release of my app, which is now called 'Tracks' (see the comments [here](http://www.rousette.org.uk/blog/archives/2004/12/23/a-new-site-for-the-gtd-application/) for the brainstorming on the name). Full details are [here](http://www.rousette.org.uk/projects/downloads/8/version-10).
 

Main new features:

* Updated to run on Rails 0.9.x
* You can now add next actions to a particular Project on the Project page. This makes it easy to add a load of next actions while you're thinking about a particular project.
* A rudimentary login system, which password protects all the main files.
* Feeds; there's a fairly basic RSS feed, and a plain text feed so that you can use <a href="http://projects.tynsoe.org/en/geektool/">GeekTool's</a> magic to display all your next actions on the desktop (thanks to <a href="http://www.braino.org/blog/archives/001512.php">Daniel Von Fange</a> for the idea).
* User-settable date format. I was previously being rather dictatorial <strong>and</strong> inconsistent by forcing YYYY-MM-DD format to enter the dates, and displaying it as DD-MM-YYYY format. Now you can choose your own format, and this is used for both entry and display.
* Uses <a href="http://www.whytheluckystiff.net/ruby/redcloth/">RedCloth 3.0</a> for the markup in the notes field. This gives you the best of both worlds by allowing both Textile and Markdown markup.
* Various bits of tidying up, bug fixes and improvements (and probably many more bugs added!) 
