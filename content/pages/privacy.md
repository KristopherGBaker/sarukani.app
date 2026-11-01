---
title: "Privacy"
description: "What Sarukani keeps, what it sends, and where."
summary: "What Sarukani keeps, what it sends, and where."
layout: article
---

Sarukani has no servers and no accounts of its own. It collects nothing about you, contains no
analytics or advertising, and does not track you.

## What stays on your device

Your subjects, reviews, settings, reminders and any Anki decks you import are kept in the app's
own storage on your device. Deck files are read from the place you pick them and copied only into
the app's own storage.

## What goes where, and why

- **WaniKani.** If you sign in, your WaniKani personal access token is used to talk to the
  WaniKani API on your behalf: to download your subjects and progress and to send your lessons and
  reviews. Pronunciation audio is downloaded from WaniKani. What WaniKani does with that is
  covered by WaniKani's own privacy policy.
- **iCloud.** Your token is stored in your iCloud Keychain, so your other devices signed in to the
  same Apple Account can use it. Progress from Sarukani's own practice (reverse reviews, past
  Burned reviews, extra study words and deck progress) syncs through your private iCloud
  database. Only you can read either; Apple's privacy policy covers iCloud.
- **The reading dictionary.** The first time you open a vocabulary word, Sarukani downloads a
  Japanese reading dictionary (Open JTalk's, from GitHub) to show furigana. Nothing about you is
  sent with that request beyond what any download sends.

Demo Mode, the sample data you can try without an account, sends nothing anywhere.

## Notifications

Review reminders are local notifications scheduled on your device. No push service learns your
schedule. iCloud uses silent pushes to tell your devices that synced practice has changed.

## Beta builds

If you test a TestFlight build, Apple shares the crash reports and feedback you choose to send
with the developer, as described in TestFlight's own terms.

## Signing out

Signing out deletes your token from your iCloud Keychain and removes your WaniKani data, synced
practice and imported decks from the device. Synced practice stays in your private iCloud
database, where your next sign-in finds it.

## Contact

Questions: sarukani@krisbaker.com.

Sarukani is not made by or affiliated with WaniKani or Tofugu.
