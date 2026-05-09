---
title: "Microsoft Edge Stores Passwords In Plaintext In RAM"
url: "https://yro.slashdot.org/story/26/05/06/2014204/microsoft-edge-stores-passwords-in-plaintext-in-ram?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-05-06"
author: "BeauHD"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotYourRightsOnline"
---
Longtime Slashdot reader UnknowingFool writes: Security researcher Tom Joran Sonstebyseter Ronning has found that Microsoft Edge stores passwords in plaintext in RAM. After creating a password and storing it using Edge's password manager, Ronning found that he could dump the RAM and recover his password which was stored in plaintext. Part of the issue is Edge loads all passwords to all sites upon a single verification check, even if the user was not visiting a specific site.
