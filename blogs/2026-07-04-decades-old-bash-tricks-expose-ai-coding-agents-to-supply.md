---
title: "Decades-Old Bash Tricks Expose AI Coding Agents To Supply Chain Attacks"
url: "https://linux.slashdot.org/story/26/07/04/0325244/decades-old-bash-tricks-expose-ai-coding-agents-to-supply-chain-attacks?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-07-04"
author: "EditorDavid"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotLinux"
---
Slashdot reader wiredmikey writes: AI security researchers have uncovered a structural security flaw dubbed GuardFall that allows decades-old Bash shell tricks to bypass safeguards in most open source AI coding agents. By exploiting shell behaviors such as quote removal and variable expansion, attackers can hide malicious commands in repositories, README files, Makefiles, or other content consumed by AI agents. If executed — particularly in auto-approve or CI environments—the commands can steal credentials, compromise developer systems, or enable software supply chain attacks.
