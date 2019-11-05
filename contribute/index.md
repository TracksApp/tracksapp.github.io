---
title: "Contribute"
layout: page
comments: false
sharing: false
footer: false
---

We gladly welcome all contributions! There are many ways you can help.
If you need help to get started, check out the resources below and drop
in on [Gitter](https://gitter.im/TracksApp/tracks) for a chat!

* [Report a bug or a feature request](https://github.com/TracksApp/tracks/issues)
* [Contribute code or localisations](https://github.com/TracksApp/tracks/blob/master/CONTRIBUTING.md)
* [Triage the issues](https://github.com/TracksApp/tracks/issues)
* or perhaps [fix an issue](https://github.com/TracksApp/tracks/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22)

## Getting the latest cutting edge version

Tracks is hosted on [GitHub][2].

The latest stable version of Tracks can be downloaded as a .zip file (see the download link in the sidebar). If you don't want to install Git, but you are feeling adventurous and want to get the very latest development version, you can use the 'Download' button on the GitHub page to get a tarball of the project.

To clone Tracks, change to a directory in which you want to store Tracks (e.g. ~/Sites):

{% highlight bash %}
git clone https://github.com/TracksApp/tracks.git
cd tracks
{% endhighlight %}

If (when!) you produce a cool new feature or fix a bug, create a patch. If you develop in a branch called 'experiment':

{% highlight bash %}
git diff master..experiment > my_feature.patch 
{% endhighlight %}

Then attach my_feature.patch to a ticket.

Or you can sign up for a free account on GitHub and fork Tracks using the convenient button. You can then use the button to issue a pull request for your changes to be pulled into the main repository.

[1]: https://github.com/TracksApp/tracks/issues
[2]: https://github.com/TracksApp/tracks
