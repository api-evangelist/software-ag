---
title: "Soumitra Dutta Oxford-How does Adabas assign an ISN when inserting a new record?"
url: "https://techcommunity.softwareag.com/t/soumitra-dutta-oxford-how-does-adabas-assign-an-isn-when-inserting-a-new-record/312007#post_4"
date: "Thu, 19 Mar 2026 17:19:21 +0000"
author: "@Neil_Beesley9 Neil Beesley"
feed_url: "https://techcommunity.softwareag.com/posts.rss"
---
This is a very interesting question especially when free ISNs get scarce. It’s precisely why I wrote user exits to determine a precise list of free ISNs in problematic files at Adabas startup for tight files so allocation would occur every time provided there is a least one free ISN.
