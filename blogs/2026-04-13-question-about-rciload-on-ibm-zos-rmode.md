---
title: "Question about RCI.LOAD on IBM z/OS // RMODE"
url: "https://techcommunity.softwareag.com/t/question-about-rci-load-on-ibm-z-os-rmode/312093#post_1"
date: "Mon, 13 Apr 2026 14:47:46 +0000"
author: "@ChristianHeld ChristianHeld"
feed_url: "https://techcommunity.softwareag.com/posts.rss"
---
<h4><a class="anchor" href="https://techcommunity.softwareag.com#p-580140-productcomponents-used-and-versionfix-level-1" name="p-580140-productcomponents-used-and-versionfix-level-1"></a><em><strong>Product/components</strong> used and <strong>version/fix</strong> level:</em></h4>
<p>We use Connx on IBM z/OS.</p>
<p>Currently we run CONNX 14.8 (build 23268).</p>
<h4><a class="anchor" href="https://techcommunity.softwareag.com#p-580140-detailed-explanation-of-the-problem-2" name="p-580140-detailed-explanation-of-the-problem-2"></a><em>Detailed explanation of the problem:</em></h4>
<p>When one inspects the RCI.LOAD you find detailed information about AMODE and RMODE:</p>
<p><span lang="EN-US">.ACE014.B23268.RCI.LOAD</span><span lang="EN-US"> </span></p>
<p><span lang="EN-US">MEMBER    STATUS  ---------------------- ATTRIBUTES ------------------------ </span></p>
<p><span lang="EN-US">    ACECALL           RENT REUS                                    AM=31  RM=ANY  </span></p>
<p><span lang="EN-US">    ACEINT            RENT REUS                                    AM=31  RM= 24</span></p>
<p><span lang="EN-US">    ACELINK           RENT REUS                                    AM=31  RM=  24</span></p>
<p><span lang="EN-US">    ACEPCC            RENT REUS                                    AM=31  RM  =24</span></p>
<p><span lang="EN-US">   </span>ACEPCCOB          RENT REUS                                    AM=31  RM=24</p>
<p>APILINK           RENT REUS                                    AM=31  RM=24</p>
<p>My simple question “why is RM=24” used, and not RM=ANY?</p>
<p>I appreciate any feedback. Deadline is 2026-09-30, at this date I retire, being over seventy</p>
