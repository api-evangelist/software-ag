---
title: "Experienced z/OS developer looking to learn Natural & Adabas — where should I focus first?"
url: "https://techcommunity.softwareag.com/t/experienced-z-os-developer-looking-to-learn-natural-adabas-where-should-i-focus-first/312540#post_4"
date: "2026-09-16"
author: "@Douglas_Kelly Douglas Kelly"
feed_url: "https://techcommunity.softwareag.com/posts.rss"
---
Just to add on to Eugene’s comments: for Natural on z/OS, JCL and CICS experience transfer just fine. there are platform differences between Linux and z/OS - character sets, collating sequences, etc that can impact programming. For example, a program might sort on an alphanumeric field, expecting numbers to follow alphas (EBCIDIC order) but on open systems (ASCII or Unicode equivalents) numbers precede alphas.
