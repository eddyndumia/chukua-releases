# Chukua releases

[![Total downloads](https://img.shields.io/github/downloads/eddyndumia/chukua-releases/total?label=downloads)](https://github.com/eddyndumia/chukua-releases/releases)
[![Latest release downloads](https://img.shields.io/github/downloads/eddyndumia/chukua-releases/latest/total?label=latest%20release)](https://github.com/eddyndumia/chukua-releases/releases/latest)

Android builds of [Chukua](https://github.com/eddyndumia), free stuff near you in Nairobi.
The app's code is private; this repo only hosts the APKs.

**Latest:** [chukua.apk](https://github.com/eddyndumia/chukua-releases/releases/latest/download/chukua.apk)

## Installing

1. Download `chukua.apk` on your Android phone.
2. Open it. If Android asks, allow your browser to install unknown apps.
3. Open Chukua and sign in with the code sent to your email.

## Download counts

The counters above are GitHub's own download counts for the APKs in this repo, all CPU builds added up. They include downloads from the website and in-app updates, since both fetch from here. Play Store installs are not counted.

## Test builds

Builds tagged `-test` run in test mode:

- SMS is simulated. Your login code appears in the app instead of arriving by SMS.
- M-Pesa is simulated. No money moves; claims are confirmed straight away.
- Value estimates come from a rule table, not the AI model yet.
- The feed includes demo listings with made-up givers.

Anything you post or claim in a test build may be wiped before launch.
