---
title: "Open Source Developer Brings Linux to Windows 95, Windows 98, and Windows ME"
url: "https://tech.slashdot.org/story/26/04/25/179232/open-source-developer-brings-linux-to-windows-95-windows-98-and-windows-me?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-04-25T18:34:00+00:00"
author: "EditorDavid"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotLinux"
---
Microsoft released the "Windows Subsystem for Linux" in 2016, adding an optional Linux environment into every operating system since Windows 10. But now an open source developer has brought Linux to Windows 95, Windows 98, and Windows Me, reports the blog It's FOSS, "with Linux kernel 6.19 running alongside the Windows 9x kernel, letting both operate on the same machine at the same time."

A virtual device driver handles initialization, loads the kernel off disk and manages the event loop for page faults and syscalls. Since Win9x lacks the right interrupt table support for the standard Linux syscall interrupt, WSL9x reroutes those calls through the fault handler instead. Rounding it all out is wsl.com, a small 16-bit DOS program that pipes the terminal output from Linux back to whatever MS-DOS prompt window you ran it from. 

The end result is that WSL9x requires no hardware virtualization, and can run on hardware as old as the i486, the article points out. On Mastodon the developer says they "really got this one in right under the wire, before they start removing 486 support from Linux." 

The source code for WSL9x is released under the GPL-3 license, and was "proudly written without AI."<p><div class="share_submission">
<a class="slashpop" href="http://twitter.com/home?status=Open+Source+Developer+Brings+Linux+to+Windows+95%2C+Windows+98%2C+and+Windows+ME%3A+https%3A%2F%2Ftech.slashdot.org%2Fstory%2F26%2F04%2F25%2F179232%2F%3Futm_source%3Dtwitter%26utm_medium%3Dtwitter"><img src="https://a.fsdn.com/sd/twitter_icon_large.png" /></a>
<a class="slashpop" href="http://www.facebook.com/sharer.php?u=https%3A%2F%2Ftech.slashdot.org%2Fstory%2F26%2F04%2F25%2F179232%2Fopen-source-developer-brings-linux-to-windows-95-windows-98-and-windows-me%3Futm_source%3Dslashdot%26utm_medium%3Dfacebook"><img src="https://a.fsdn.com/sd/facebook_icon_large.png" /></a>



</div></p><p><a href="https://tech.slashdot.org/story/26/04/25/179232/open-source-developer-brings-linux-to-windows-95-windows-98-and-windows-me?utm_source=rss1.0moreanon&amp;utm_medium=feed">Read more of this story</a> at Slashdot.</p>
