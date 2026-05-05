---
title: "Linux 7.0 Released"
url: "https://linux.slashdot.org/story/26/04/13/1857240/linux-70-released?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-04-13T19:00:00+00:00"
author: "BeauHD"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotLinux"
---
"The new Linux kernel was released and it's kind of a big deal," writes longtime Slashdot reader rexx mainframe. "Here is what you can expect." Linuxiac reports: A key update in Linux 7.0 is the removal of the experimental label from Rust support. That (of course) does not make Rust a dominant language in kernel development, but it is still an important step in its gradual integration into the project. Another notable security-related change is the addition of ML-DSA post-quantum signatures for kernel module authentication, while support for SHA-1-based module-signing schemes has been removed.
 
The kernel now includes BPF-based filtering for io_uring operations, providing administrators with improved control in restricted environments. Additionally, BTF type lookups are now faster due to binary search. At the same time, this release continues ongoing cleanup in the kernel's lower layers. The removal of linuxrc initrd code advances the transition to initramfs as the sole early-userspace boot mechanism.
 
Linux 7.0 also introduces NULLFS, an immutable and empty root filesystem designed for systems that mount the real root later. Plus, preemption handling is now simpler on most architectures, with further improvements to restartable sequences, workqueues, RCU internals, slab allocation, and type-based hardening. Filesystems and storage receive several updates as well. Non-blocking timestamp updates now function correctly, and filesystems must explicitly opt in to leases rather than receiving them by default. Phoronix has compiled a list of the many exciting changes.
 
Linus Torvalds himself announced the release, which can be downloaded directly from his git tree or from the kernel.org website.
 
Linux 7.0 has a major new version number but it's "largely a numbering reset [...], not a sign of some unusually disruptive release," notes Linuxiac.<p><div class="share_submission">
<a class="slashpop" href="http://twitter.com/home?status=Linux+7.0+Released%3A+https%3A%2F%2Flinux.slashdot.org%2Fstory%2F26%2F04%2F13%2F1857240%2F%3Futm_source%3Dtwitter%26utm_medium%3Dtwitter"><img src="https://a.fsdn.com/sd/twitter_icon_large.png" /></a>
<a class="slashpop" href="http://www.facebook.com/sharer.php?u=https%3A%2F%2Flinux.slashdot.org%2Fstory%2F26%2F04%2F13%2F1857240%2Flinux-70-released%3Futm_source%3Dslashdot%26utm_medium%3Dfacebook"><img src="https://a.fsdn.com/sd/facebook_icon_large.png" /></a>



</div></p><p><a href="https://linux.slashdot.org/story/26/04/13/1857240/linux-70-released?utm_source=rss1.0moreanon&amp;utm_medium=feed">Read more of this story</a> at Slashdot.</p>
