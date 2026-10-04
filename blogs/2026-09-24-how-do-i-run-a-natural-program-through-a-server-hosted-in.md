---
title: "How do I run a Natural program through a server hosted in an offline environment?"
url: "https://techcommunity.softwareag.com/t/how-do-i-run-a-natural-program-through-a-server-hosted-in-an-offline-environment/312577#post_2"
date: "2026-09-24"
author: "@Ralph_Zbrog Ralph Zbrog"
feed_url: "https://techcommunity.softwareag.com/posts.rss"
---
To execute program yourpgm from library yourlib , change your Natural command to natural.exe batchmode parm=yourparm stack=(logon yourlib;yourpgm;fin) bmtime=on natlog=all The PARM keyword specifies a Natural parameter file created and maintained by the Natural Configuration utility. You may need to customize the input for the individual user. Option 1: See the STACK parameter in the documentation.
