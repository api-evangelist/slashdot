---
title: "After Six Years Of Work and Over 360 Patches, Linux 7.2 Finally Removes Bug-Prone strncpy"
url: "https://linux.slashdot.org/story/26/06/21/1810200/after-six-years-of-work-and-over-360-patches-linux-72-finally-removes-bug-prone-strncpy"
date: "2026-06-21"
author: "EditorDavid"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotMain"
---
The Linux kernel completed elimination of the strncpy() function across all subsystems after 362 commits over six years, replacing the "actively dangerous" function with five context-specific alternatives. The cleanup removes an entire class of memory disclosure vulnerabilities.
