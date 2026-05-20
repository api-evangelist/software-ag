---
title: "Question about RCI.LOAD on IBM z/OS // RMODE"
url: "https://techcommunity.softwareag.com/t/question-about-rci-load-on-ibm-z-os-rmode/312093#post_1"
date: "Mon, 13 Apr 2026 14:47:46 +0000"
author: "@ChristianHeld ChristianHeld"
feed_url: "https://techcommunity.softwareag.com/posts.rss"
---
Product/components used and version/fix level: We use Connx on IBM z/OS. Currently we run CONNX 14.8 (build 23268). Detailed explanation of the problem: When one inspects the RCI.LOAD you find detailed information about AMODE and RMODE: .ACE014.B23268.RCI.LOAD MEMBER STATUS ---------------------- ATTRIBUTES ------------------------ ACECALL RENT REUS AM=31 RM=ANY ACEINT RENT REUS AM=31 RM= 24 ACELINK RENT REUS AM=31 RM= 24 ACEPCC RENT REUS AM=31 RM =24 ACEPCCOB RENT REUS AM=31 RM=24 APILINK RENT REUS AM=31 RM=24 My simple question “why is RM=24” used, and not RM=ANY?
