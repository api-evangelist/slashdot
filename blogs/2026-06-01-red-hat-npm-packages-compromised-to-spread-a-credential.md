---
title: "Red Hat npm Packages Compromised to Spread a Credential-Stealing Worm"
url: "https://it.slashdot.org/story/26/06/01/1624228/red-hat-npm-packages-compromised-to-spread-a-credential-stealing-worm?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-06-01"
author: "BeauHD"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotMain"
---
Aikido Security says more than 30 official @redhat-cloud-services npm packages were compromised with a credential-stealing worm called "Miasma," a variant resembling the open-sourced Mini Shai-Hulud supply-chain malware. "The packages were published via GitHub Actions OIDC, indicating the CI/CD pipeline was compromised rather than an npm token," the report says. "If you have installed any affected package versions since June 1, 2026, treat all CI secrets, cloud credentials, SSH keys, and npm tokens as compromised and rotate them immediately." From the report: Each compromised package declares 
