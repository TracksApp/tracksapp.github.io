---
layout: page
title: "Development"
date: 2014-06-25 15:39
comments: false
sharing: false
footer: false
---

## Reporting bugs and requesting features

If you find a bug or have a bright idea for a feature, you can report the bug on our [bug tracker][2]). You can search and browse the tickets and comments without being logged in, but if you want to create a new ticket or comment on an existing one, you'll need to register for an account (use the link at the top of the bug tracker page). Once you have an account, visit the [Tracks Space][2], click on the 'Team' tab, and you should see a link at the top right of the page marked "Public Space | Join this space". Click the "Join this space" link, and you'll be added as a Tracks team member. You may find that you need to log out and then log in again after your initial registration to get the join link to work and not return a blank page. If you still have trouble, please email me (butshesagirl [at] rousette [dot] org [dot] uk) with your username and I'll add you manually to the team.

## Getting the latest cutting edge version

We are developing using [Git][3] and host the development branch at [GitHub][4]. The main reason for this move was to make it much easier for people to contribute to the project. Anyone can clone the repository and submit patches, but to make life even easier, you can sign up for a free account at GitHub and then fork Tracks. GitHub provides a 'pull request' button, so when you've added something cool or fixed a bug, hit the button and we'll pull in your changes. Git makes merging **much** easier than Subversion, even if the codebase has moved on a bit since you created the patch. If you're not a programmer, you can still contribute to the project. The manual can be found by following the 'Manual' link in the navigation bar of this site. The manual is actually included in the [source code of this site][5], so if you'd like to add to or improve the manual, you can fork the repository and submit a pull request through Github.

The latest stable version of Tracks can still be downloaded as a .zip file (see the download link in the sidebar). If you don't want to install Git, but you are feeling adventurous and want to get the very latest development version, you can use the 'Download' button on the GitHub page to get a tarball of the project.

To clone Tracks, change to a directory in which you want to store Tracks (e.g. ~/Sites):

{% codeblock lang:bash %}
git clone git://github.com/TracksApp/tracks.git
cd tracks
{% endcodeblock %}

If (when!) you produce a cool new feature or fix a bug, create a patch. If you develop in a branch called 'experiment':

{% codeblock lang:bash %}
git diff master..experiment > my_feature.patch 
{% endcodeblock %}

Then attach my_feature.patch to a ticket.

Or you can sign up for a free account on github and fork Tracks using the convenient button. You can then use the button to issue a pull request for your changes to be pulled into the main repository.

[1]: http://groups.google.com/group/TracksApp
[2]: https://www.assembla.com/spaces/tracks-tickets/
[3]: http://git-scm.com/
[4]: https://github.com/TracksApp/tracks
[5]: https://github.com/TracksApp/tracksapp.github.com
