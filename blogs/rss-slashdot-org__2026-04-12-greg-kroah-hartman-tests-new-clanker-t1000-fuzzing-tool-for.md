---
title: "Greg Kroah-Hartman Tests New 'Clanker T1000' Fuzzing Tool for Linux Patches"
url: "https://linux.slashdot.org/story/26/04/12/063252/greg-kroah-hartman-tests-new-clanker-t1000-fuzzing-tool-for-linux-patches?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-04-12T14:34:00+00:00"
author: "EditorDavid"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotLinux"
---
The word clanker &mdash; a disparaging term for AI and robots &mdash; "has made its way into the Linux kernel," reports the blog It's FOSS "thanks to Greg Kroah-Hartman, the Linux stable kernel maintainer and the closest thing the project has to a second-in-command."

He's been quietly running what looks like an AI-assisted fuzzing tool on the kernel that lives in a branch called "clanker" on his working kernel tree. It began with the ksmbd and SMB code. Kroah-Hartman filed a three-patch series after running his new tooling against it, describing the motivation quite simply. ["They pass my very limited testing here," he wrote, "but please don't trust them at all and verify that I'm not just making this all up before accepting them."] Kroah-Hartman picked that code because it was easy to set up and test locally with virtual machines. 

"Beyond those initial SMB/KSMBD patches, there have been a flow of other Linux kernel patches touching USB, HID, F2FS, LoongArch, WiFi, LEDs, and more," Phoronix wrote Tuesday, "that were done by Greg Kroah-Hartman in the past 48 hours....
Those patches in the "Clanker" branch all note as part of the Git tag: "Assisted-by: gregkh_clanker_t1000" 
The T1000 presumably in reference to the Terminator T-1000. 

 It's FOSS emphasizes that "What Kroah-Hartman appears to be doing here is not having AI write kernel code. The fuzzer surfaces potential bugs; a human with decades of kernel experience reviews them, writes the actual fixes, and takes responsibility for what gets submitted."
Linus has been thinking about this too. Speaking at Open Source Summit Japan last year, Linus Torvalds said the upcoming Linux Kernel Maintainer Summit will address "expanding our tooling and our policies when it comes to using AI for tooling." 
He also mentioned running an internal AI experiment where the tool reviewed a merge he had objected to. The AI not only agreed with his objections but found additional issues to fix. Linus called that a good sign, while asserting that he is "much less interested in AI for writing code" and more interested in AI as a tool for maintenance, patch checking, and code review.<p><div class="share_submission">
<a class="slashpop" href="http://twitter.com/home?status=Greg+Kroah-Hartman+Tests+New+'Clanker+T1000'+Fuzzing+Tool+for+Linux+Patches%3A+https%3A%2F%2Flinux.slashdot.org%2Fstory%2F26%2F04%2F12%2F063252%2F%3Futm_source%3Dtwitter%26utm_medium%3Dtwitter"><img src="https://a.fsdn.com/sd/twitter_icon_large.png" /></a>
<a class="slashpop" href="http://www.facebook.com/sharer.php?u=https%3A%2F%2Flinux.slashdot.org%2Fstory%2F26%2F04%2F12%2F063252%2Fgreg-kroah-hartman-tests-new-clanker-t1000-fuzzing-tool-for-linux-patches%3Futm_source%3Dslashdot%26utm_medium%3Dfacebook"><img src="https://a.fsdn.com/sd/facebook_icon_large.png" /></a>



</div></p><p><a href="https://linux.slashdot.org/story/26/04/12/063252/greg-kroah-hartman-tests-new-clanker-t1000-fuzzing-tool-for-linux-patches?utm_source=rss1.0moreanon&amp;utm_medium=feed">Read more of this story</a> at Slashdot.</p>
