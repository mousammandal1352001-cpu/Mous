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

### For One UI 5.1 Devices:

1. **Enable Installation from Unknown Sources**
   - Settings → Apps → Permission Manager → Install Unknown Apps
   - Select your file manager and toggle **ON**

2. **Install the APK**
   - Download `QStuner-OneUI5-Compatible-v11.0.03.15-MOD.apk`
   - Use file manager to navigate and tap to install
   - Grant all requested permissions

3. **Verify Installation**
   - Open Settings → Apps → Quick Settings Tuner
   - App should launch without errors

## Features

- 🎨 Advanced Quick Settings customization
- ⚙️ System-level QS panel modifications
- 🎯 One-tap custom shortcuts
- 📱 Multi-device support (One UI 5.1 - 8.0+)

## Known Issues

None reported for One UI 5.1

## Troubleshooting

**Installation Fails:**
- Clear Google Play Services cache: Settings → Apps → Google Play Services → Storage → Clear Cache
- Restart device
- Retry installation

**App Force Closes:**
- Uninstall and reinstall
- Check available storage (min 100MB)
- Ensure One UI 5.1 or higher

**Permissions Not Granted:**
- Go to Settings → Apps → Quick Settings Tuner → Permissions
- Grant all required permissions manually

## File Information

- **App Name:** Samsung Quick Settings Tuner
- **Package:** com.samsung.android.qstuner
- **Version:** 11.0.03.15
- **Build ID:** 1100315000
- **Architecture:** arm64-v8a
- **Min SDK:** 29 (Android 10)
- **Target SDK:** 33 (One UI 5.1)

## Technical Details

### APK Modifications Process
1. Decompiled with APKTool v2.7.0
2. Modified AndroidManifest.xml targetSdkVersion
3. Removed incompatible libraries for API 36
4. Recompiled APK
5. Signed with debug certificate

### APK Signing Info
- **Certificate Type:** Debug
- **SHA-1:** [Generated during build]
- **Valid Until:** 2054

## Installation Sizes

- **Compressed APK:** ~11.8 MB
- **Installed Size:** ~28-35 MB (varies by device)
- **Cache:** ~5-10 MB

## Support & Issues

For issues or bugs:
1. Report in GitHub Issues
2. Include device model and One UI version
3. Attach logcat output if possible

## Disclaimer

⚠️ **USE AT YOUR OWN RISK**

This is an unofficial modification. Samsung does not endorse this mod. 

- No warranty provided
- May void device warranty in some regions
- Create backup before installation
- Not responsible for device damage

## Credits

- Original App: Samsung Electronics
- Mod: Community Development
- Based on: QS Tuner v11.0.03.15

## License

This modification is provided as-is for educational and personal use only.

---

**Last Updated:** 2026-06-17
**Mod Version:** 1.0
**Tested On:** One UI 5.1 (Galaxy S23, S24 series)
