# Locator Recorder

An independent GPLv3 Android call-recorder fork based on [CallVault](https://github.com/madkongo/CallVault), which in turn is based on [ShizuCallRecorder](https://github.com/kitsumed/ShizuCallRecorder). It is not affiliated with either project.

Download the [signed Android 14+ APK](https://github.com/Raunik2/locator-recorder/releases/download/v0.1.1/locator-recorder-v0.1.1.apk) and the [complete corresponding source archive](https://github.com/Raunik2/locator-recorder/releases/download/v0.1.1/recorder-source-0.1.1.tar.gz) from the [v0.1.1 prerelease](https://github.com/Raunik2/locator-recorder/releases/tag/v0.1.1). **The automatically generated GitHub source zip for this repository is not the Android source.** Use the attached archive.

The app targets ordinary SIM calls and automatically records only explicitly selected incoming/outgoing numbers. Two-sided capture needs on-device Wireless Debugging pairing; normal permissions alone are insufficient. Optional upload goes to an [unlisted recording viewer](https://locator-b445c.web.app/recordings/) after device approval and explicit opt-in. Anyone with a generated viewer link can listen to those recordings.

An outgoing cellular call was tested on a Motorola Edge 50 Fusion running Android 16: both voices were confirmed clear, the recording saved and uploaded, and capture released at hang-up. Incoming capture and unselected-call behavior still need separate hardware checks. The Android unit suite passes 1,958 tests. Follow `SETUP.md` inside the source archive and test on each phone before relying on it.
