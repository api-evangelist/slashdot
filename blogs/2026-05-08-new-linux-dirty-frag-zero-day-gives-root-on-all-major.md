---
title: "New Linux 'Dirty Frag' Zero-Day Gives Root On All Major Distros"
url: "https://linux.slashdot.org/story/26/05/08/1913238/new-linux-dirty-frag-zero-day-gives-root-on-all-major-distros?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-05-08"
author: "BeauHD"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotMain"
---
mrspoonsi shares a report: Dirty Frag is a vulnerability class, first discovered and reported by Hyunwoo Kim (@v4bel), that can obtain root privileges on major Linux distributions by chaining the xfrm-ESP Page-Cache Write vulnerability and the RxRPC Page-Cache Write vulnerability. Dirty Frag extends the bug class to which Dirty Pipe and Copy Fail belong. Because it is a deterministic logic bug that does not depend on a timing window, no race condition is required, the kernel does not panic when the exploit fails, and the success rate is very high.
