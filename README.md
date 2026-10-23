# Locator Recorder

A minimal, local Android recorder for selected contacts. One contact list covers incoming and outgoing ordinary SIM/cellular calls. Empty selections, hidden caller IDs and unselected numbers are not recorded.

Download the [signed v0.2.0 APK](https://github.com/Raunik2/locator-recorder/releases/download/v0.2.0/locator-recorder-v0.2.0.apk) and [complete corresponding source](https://github.com/Raunik2/locator-recorder/releases/download/v0.2.0/recorder-source-0.2.0.tar.gz) from the [v0.2.0 prerelease](https://github.com/Raunik2/locator-recorder/releases/tag/v0.2.0). The automatically generated GitHub source zip is not the Android source; use the attached archive.

## Version 0.2.0

- Recordings, playback, one contact selector and an on/off switch.
- No transcripts, summaries, Telegram, webpage uploads or Shizuku setup.
- No notification permission request. Android's mandatory recording/privacy and active-app disclosures still apply.
- High-quality AAC/M4A at 128 kbps. Local folder storage, no automatic deletion.
- Outgoing capture waits for confirmed connection; incoming ringing never starts capture. Missing connection state skips capture rather than recording ringing.
- Dedicated notification cleanup, cancelled late starts and a call-end watchdog.

The release build passes 1,977 automated tests. Fresh-install phone/background permission dialogs and notification-free, built-in split-screen pairing were verified on a Motorola Edge 50 Fusion running Android 16. Ordinary permissions alone cannot grant both-sided cellular audio: the one-time Android helper connection is still necessary, but no second app is required. Follow SETUP.md in the source archive. No new live call was placed during this redesign; verify both voices and incoming/outgoing timing on each phone and call route before relying on it. The earlier 0.1.1 two-sided outgoing test does not by itself validate every 0.2.0 path.

This is an independent MODIFIED FORK of [CallVault](https://github.com/madkongo/CallVault), originally derived from [ShizuCallRecorder](https://github.com/kitsumed/ShizuCallRecorder), under GPL-3.0-or-later with additional Section 7 terms. Not affiliated with or endorsed by either project. Attribution and full license are included in the corresponding source and the app's About screen.
