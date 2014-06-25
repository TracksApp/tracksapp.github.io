---
layout: page
title: "Development"
date: 2014-06-25 15:39
comments: false
sharing: false
footer: false
---

## Reporting bugs and requesting features

If you find a bug or have a bright idea for a feature, you can report the bug on our [issue tracker][1].

## Getting the latest cutting edge version

Tracks is hosted on [GitHub][2].

The latest stable version of Tracks can be downloaded as a .zip file (see the download link in the sidebar). If you don't want to install Git, but you are feeling adventurous and want to get the very latest development version, you can use the 'Download' button on the GitHub page to get a tarball of the project.

To clone Tracks, change to a directory in which you want to store Tracks (e.g. ~/Sites):

{% codeblock lang:bash %}
git clone https://github.com/TracksApp/tracks.git
cd tracks
{% endcodeblock %}

If (when!) you produce a cool new feature or fix a bug, create a patch. If you develop in a branch called 'experiment':

{% codeblock lang:bash %}
git diff master..experiment > my_feature.patch 
{% endcodeblock %}

Then attach my_feature.patch to a ticket.

Or you can sign up for a free account on GitHub and fork Tracks using the convenient button. You can then use the button to issue a pull request for your changes to be pulled into the main repository.

[1]: https://github.com/TracksApp/tracks/issues
[2]: https://github.com/TracksApp/tracks
