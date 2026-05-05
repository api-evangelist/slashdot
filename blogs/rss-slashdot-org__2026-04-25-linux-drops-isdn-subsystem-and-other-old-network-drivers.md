---
title: "Linux  Drops ISDN Subsystem and Other Old Network Drivers"
url: "https://linux.slashdot.org/story/26/04/25/0757219/linux-drops-isdn-subsystem-and-other-old-network-drivers?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-04-25T17:34:00+00:00"
author: "EditorDavid"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotLinux"
---
"Old code like amateur radio and NFC have long been a burden to core networking developers," reads the pull request. 

And so Thursday Linus Torvald merged the pull request "to rid the Linux kernel of the old Integrated Services Digital Network (ISDN) subsystem," reports Phoronix, "and various other old network drivers largely for PCMCIA era network adapters."


 This was the code suggested for removal given the recent influx of AI/LLM-generated bug reports against this dated code that likely has no active upstream users remaining... [W]ith the large language models and increased code fuzzing finding potential issues with these drivers for obsolete hardware, it's easier to just get rid of these drivers if no one is actively using the hardware from decades ago...

This merge lightens the kernel by 138,161 lines of code with ISDN gone and numerous old network adapters and also getting rid of legacy ATM device drivers as well as the amateur ham radio support. The main networking drivers removed affect the 3com 3c509 / 3c515 / 3c574 / 3c589, AMD Lance, AMD NMCLAN, SMSC SMC9194 / SMC91C92, Fujitsu FMVJ18X, and 8390 AX88190 / Ultra / WD80X3. 

Linux 7.1 also has removed the long-obsolete bus mouse support as well as beginning to phase out Intel 486 CPU support and removing support for Russia's Baikal CPUs.


<p><div class="share_submission">
<a class="slashpop" href="http://twitter.com/home?status=Linux++Drops+ISDN+Subsystem+and+Other+Old+Network+Drivers%3A+https%3A%2F%2Flinux.slashdot.org%2Fstory%2F26%2F04%2F25%2F0757219%2F%3Futm_source%3Dtwitter%26utm_medium%3Dtwitter"><img src="https://a.fsdn.com/sd/twitter_icon_large.png" /></a>
<a class="slashpop" href="http://www.facebook.com/sharer.php?u=https%3A%2F%2Flinux.slashdot.org%2Fstory%2F26%2F04%2F25%2F0757219%2Flinux-drops-isdn-subsystem-and-other-old-network-drivers%3Futm_source%3Dslashdot%26utm_medium%3Dfacebook"><img src="https://a.fsdn.com/sd/facebook_icon_large.png" /></a>



</div></p><p><a href="https://linux.slashdot.org/story/26/04/25/0757219/linux-drops-isdn-subsystem-and-other-old-network-drivers?utm_source=rss1.0moreanon&amp;utm_medium=feed">Read more of this story</a> at Slashdot.</p>
