---
layout: page
title: "Tracks 2.0"
date: 2011-10-09 19:22
comments: false
sharing: false
footer: false
---

{% img left /images/screens/tracks_home_thumb.png 'Full screen screenshot of Tracks' %}

Tracks is a web-based application to help you implement <a href="http://www.davidco.com/">David Allen's</a> <a href="http://www.amazon.com/gp/product/0142000280/qid=1143370534/sr=2-1/ref=pd_bbs_b_2_1/103-9587420-9758203?s=books&amp;v=glance&amp;n=283155">Getting Things Done&#8482;</a> methodology. It was built using <a href="http://www.rubyonrails.com/">Ruby on Rails</a>, and comes with a built-in webserver (<span class="caps">WEB</span>rick), so that you can run it on your own computer if you like. It can be run on any platform on which Ruby can be installed, including Mac OS X, Windows XP and Linux. Tracks is Open Source, free and licensed under the <a href="http://creativecommons.org/licenses/GPL/2.0/"><span class="caps">GNU</span> <span class="caps">GPL</span></a>.

## Current features

### Flexible views of your actions

{% img left /images/screens/tracks_context_list.png 'Screenshot of context list' %}

The main page shows all your actions sorted by context, but you can also view pages showing just the actions in one context (for when you want to focus on your office tasks, email or errands), or just the actions in one project. You can add as many contexts and projects as you like, and drag them around on the page to change the sort order, so that your more commonly used contexts and projects are at the top of the page. Projects can have attached notes, as can individual actions. You can also mark projects as active, hidden or completed. If you want to put a project on the back-burner for a while, but you haven't completed it, marking it as hidden hides the project's actions from your home page. Similarly, contexts can be hidden from the home page, which is handy for contexts such as 'Someday/Maybe': things you want to make a note of, but which you don't want to deal with right now.

### Tagging and starring

{% img left /images/screens/tracks_tags.png 'Screenshot of tags' %}

If you need alternative ways to slice your actions, you can now tag actions with free-form tags, and view all actions tagged with a particular tag on one page. This gives you another way to look at  your data which works in parallel with the more traditional contexts and projects. In addition, you can 'star' actions very quickly by just clicking the star icon. Starred actions can also be viewed on their own page, and can be used in whatever way you find most helpful. A starred task might be a particularly urgent or important one, or something you're aiming to do today.

### Quick and easy adding of new actions

{% img left /images/screens/tracks_home.png 'Screenshot of adding actions %}

The main editing functions in Tracks use Ajax, which &#8212; if you're not into the terminology &#8212; means that you see nearly instant changes to the page without having to refresh the page. A form on the main page lets you add actions to any context or project, whereas forms on context and project pages automatically assign the current context or project to the new next action. In Tracks 1.5, your existing context and project names are auto-completed as you type, saving you time and reducing input errors. Furthermore, you can set a default context for each of your projects, which saves you typing 'Office' for every action in a particular project.

### Getting yourself organised

{% img left /images/screens/tracks_tickler.png 'Screenshot of tickler %}

Actions can have due dates (which are optional), which are displayed in your preferred format. The due date is displayed with a coloured background, depending on how far away the date is. If it's due today, or overdue, the background is red. If it's due tomorrow it's dark orange, if due in the next 7 days, it's orange, otherwise it's green. It's basically a traffic light code. A new feature in Tracks 1.5 lets you schedule actions for the future. The 'tickler' allows you to schedule actions to be shown on the home page after some future date. This allows you to get the action out of your head into a concrete, safe system (where it belongs), but you don't need to be bothered by the action until the time comes when you can actually deal with it. You can show a configurable number of completed items at the bottom of the main page, but you can see all your completed items on the completed page.

### Getting everyone organised

{% img left /images/screens/tracks_preferences.png 'Screenshot of preferences %}

Tracks is multi-user: each user has his or her own contexts, projects and next actions, and their own preferences for things like date formatting. As the admin user, you set your own account up and then you can add or delete additional users. Non-admin users can't create new accounts, which prevents someone finding your page and signing themselves up. A login page keeps everyone's actions private. Get your family, friends and co-workers sorted out!

### Measure your progress

{% img left /images/screens/tracks_stats.png 'Screenshot of statistics page %}

New in Tracks 1.5 is a comprehensive statistics page, which shows you a wealth of information about your progress. You can view the average time you take to complete tasks, and see how many actions you've completed in the past month or year. Do you suspect that you are most productive on Mondays, but least productive on Fridays? Now you can find out if that's true. The statistics page allows you to measure your progress and plan your time to exploit those periods when you are at your most dynamic and effective.

### Getting informed

{% img left /images/screens/tracks_feeds.png 'Screenshot of feeds' %}

Tracks has numerous feeds (both text, iCal and <span class="caps">RSS</span>), so you can subscribe to your list of next actions to see all of your stuff, or just the urgent things due in the next seven days. Do you need to provide your employer or clients with a report of your work during the week? Then just subscribe to the completed actions in the past 7 days feed, and the job is nearly done. You can now also export your data in <span class="caps">YAML</span>, <span class="caps">CSV</span> or <span class="caps">XML</span> format, making it easy to use your data for other purposes, or just make a backup.

### Other ways to interact with Tracks

Tracks now has a great <span class="caps">API</span>, so if you're handy with a shell script, Ruby script or AppleScript, you can create other ways to get data into and out of your Tracks installation. If you have a browser on your mobile phone, you can access a clean, lightweight interface to Tracks by visiting http://yourtracks.url/mobile/ &#8211; a great way to get things done on the move!


## Getting Tracks

You can download a zipped file containing the latest stable version of Tracks by using the 'Get Tracks' button in the sidebar on the right of this page. If you'd like to get a development version, or contribute to the project, all the information you need is on the <a href="/development">Development page</a>.

## History

The origins of this application are <a href="http://www.rousette.org.uk/blog/archives/rails-gtd-application/">here</a> and <a href="http://www.rousette.org.uk/blog/archives/2004/11/07/gtd-on-rails/">here</a>. The name Tracks was suggested by Timothy Martens, and the tag-line &#8216;Doing Things Properly' came from a comment by Pete <a href="http://www.rousette.org.uk/blog/archives/2004/12/07/do-it-now-by-steve-pavlina/#comment-2976">here</a>. I rather liked it.

Tracks is now developed by maintained by a team of <a href="http://www.getontracks.org/wiki/Contributors/">contributors</a>. Why not <a href="http://www.rousette.org.uk/projects/tracks/contribute">join us</a>?
