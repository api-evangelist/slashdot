---
title: "Slashdot Reader Builds a Photo-Verification App for iPhones"
url: "https://apple.slashdot.org/story/26/08/08/2328239/slashdot-reader-builds-a-photo-verification-app-for-iphones?utm_source=rss1.0mainlinkanon&utm_medium=feed"
date: "2026-08-08"
author: "EditorDavid"
feed_url: "https://rss.slashdot.org/Slashdot/slashdotApple"
---
Long-time Slashdot reader BrianFagioli is announcing that he's released a new iPhone app that creates a cryptographic witness for photos without uploading the original image. The app hashes the file, signs the hash using a dedicated identity stored in Apple Keychain, and publishes the witness to Nostr relays while keeping the photo inside the app unless the user chooses to export it. Rather than trying to determine whether a scene was genuine, the app — named Veridenz — answers a narrower question, by verifying whether a photo file matches the one that was originally witnessed.
