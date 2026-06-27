---
title: "After Six Years Of Work and Over 360 Patches, Linux 7.2 Finally Removes Bug-Prone strncpy"
url: "https://linux.slashdot.org/story/26/06/21/1810200/after-six-years-of-work-and-over-360-patches-linux-72-finally-removes-bug-prone-strncpy?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-06-21"
author: "EditorDavid"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotLinux"
---
Tech Times reports: Linux 7.2's merge window closed out a cleanup campaign on Friday that most kernel developers had stopped expecting to see end: the complete removal of strncpy(), a C string-copy function that the kernel's own documentation labels "actively dangerous," from every subsystem, driver, and architecture-specific file in the kernel source tree. The merge landed June 20, 2026. After around 362 commits spread across six years of incremental work, no call site using the function remained, and the function itself — including the last per-CPU-architecture optimized implementations — wa
