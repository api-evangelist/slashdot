---
title: "Ruby Fights Supply-Chain Attacks With Filter Offering 'Cooldown' Before Installing New Packages"
url: "https://developers.slashdot.org/story/26/06/08/0511207/ruby-fights-supply-chain-attacks-with-filter-offering-cooldown-before-installing-new-packages?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-06-08"
author: "EditorDavid"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotDevelopers"
---
Most supply-chain attacks using Ruby's package hosting site "exploit a narrow window," according to a new blog post form Ruby core maintainer Hiroshi Shibata. So its packaging-managing Bundler tool now offers a filter that blocks new version until it's been public "for at least N days. Releases too new to have been scrutinized are passed over in favor of ones that have aged past the window." The feature was designed in the open, drawing on how other ecosystems approach the same problem.
