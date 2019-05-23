---
layout: post
date: 2006-05-11 
author: bsag 
title: "Updated migrations files" 
categories: [news] 
comments: true
sharing: true
footer: true
---

I've just updated the migrations files in both the tracks-1.041.zip package and in the tagged 1.041 release. Many (<em>many</em>) people had trouble with the migrations for various reasons, one of which was that there was a bit of raw SQL which would cause some databases to choke. Windows users also seemed to have trouble with it. Anyway, I've changed the migrations now so that they use Rails itself to generate the SQL, which means that it gets appropriately translated for the different databases. So &mdash; fingers crossed &mdash; it should work much better now!

If you've been having trouble with your rake migrate, download again and give it a go. 

 
