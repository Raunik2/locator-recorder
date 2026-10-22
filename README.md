# Locator Recorder

An independent GPLv3 Android call-recorder fork based on [CallVault](https://github.com/madkongo/CallVault), which in turn is based on [ShizuCallRecorder](https://github.com/kitsumed/ShizuCallRecorder). It is not affiliated with either project.

Download the [signed Android 14+ APK](https://github.com/Raunik2/locator-recorder/releases/download/v0.1.0/locator-recorder-v0.1.0.apk) and the [complete corresponding source archive](https://github.com/Raunik2/locator-recorder/releases/download/v0.1.0/recorder-source-0.1.0.tar.gz) from the [v0.1.0 prerelease](https://github.com/Raunik2/locator-recorder/releases/tag/v0.1.0). **The automatically generated GitHub source zip for this stub repository is not the Android source.** Use the attached archive.

The app targets ordinary SIM calls and automatically records only explicitly selected incoming/outgoing numbers. Two-sided capture needs on-device Wireless Debugging pairing; normal permissions alone are insufficient. Optional upload goes to an [unlisted recording viewer](https://locator-b445c.web.app/recordings/) after device approval and explicit opt-in. Anyone with a generated viewer link can listen to those recordings.

This is a device-test build. Two-sided call audio has **not** yet been verified on the target Motorola Edge 50 Fusion. Test a selected incoming call, a selected outgoing call, and an unselected call before relying on it. Follow `SETUP.md` inside the source archive.
