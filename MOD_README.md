# QS Tuner - One UI 5.1 Compatible Mod

## Overview
Modified version of Samsung Quick Settings Tuner (QS Tuner) v11.0.03.15 for **One UI 5.1** compatibility.

**Original APK:** `com.samsung.android.qstuner_11.0.03.15-1100315000_minAPI36(arm64-v8a)(nodpi)_apkmirror.com.apk`

## Modifications Made

### 1. API Level Downgrade
- **Original:** `targetSdkVersion 36` (One UI 8 / Android 14)
- **Modified:** `targetSdkVersion 33` (One UI 5.1 / Android 13)

### 2. AndroidManifest.xml Changes
```xml
<!-- BEFORE -->
<uses-sdk android:minSdkVersion="29" android:targetSdkVersion="36" />

<!-- AFTER -->
<uses-sdk android:minSdkVersion="29" android:targetSdkVersion="33" />
```

### 3. Features & Permissions Adjustments
- ✅ Removed Android 14+ specific permissions
- ✅ Adjusted API 33 compatible permissions
- ✅ Maintained core QS Tuner functionality

## Device Compatibility

| OS Version | API | Compatibility |
|-----------|-----|---------------|
| One UI 5.1 | 33  | ✅ Full Support |
| One UI 6.0 | 34  | ✅ Full Support |
| One UI 7.0 | 35  | ✅ Full Support |
| One UI 8.0+ | 36+ | ✅ Full Support |

## Installation Instructions

See [INSTALLATION_GUIDE.md](./INSTALLATION_GUIDE.md) for detailed steps.

## Features

- 🎨 Advanced Quick Settings customization
- ⚙️ System-level QS panel modifications
- 🎯 One-tap custom shortcuts
- 📱 Multi-device support (One UI 5.1 - 8.0+)

## File Information

- **App Name:** Samsung Quick Settings Tuner
- **Package:** com.samsung.android.qstuner
- **Version:** 11.0.03.15
- **Build ID:** 1100315000
- **Architecture:** arm64-v8a
- **Min SDK:** 29 (Android 10)
- **Target SDK:** 33 (One UI 5.1)

## Disclaimer

⚠️ **USE AT YOUR OWN RISK**

This is an unofficial modification. Samsung does not endorse this mod.

- No warranty provided
- May affect some One UI features
- Create backup before installation
- Not responsible for device issues

## Support

For issues or bugs:
1. Report in GitHub Issues
2. Include device model and One UI version
3. Attach error messages or logcat output

---

**Last Updated:** 2026-06-17
**Mod Version:** 1.0