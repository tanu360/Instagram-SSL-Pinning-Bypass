# Instagram-SSL-Pinning-Bypass
 Bypass Instgram SSL Pinning in Android App.

## Project Overview
This project hosts modified versions of the Instagram app (309.1.0.41.113) that include an SSL bypassing patch. This feature enables the interception and analysis of encrypted traffic, particularly focusing on Instagram's private APIs. The repository includes builds for different architectures to support a wide range of Android devices.

### Custom SSL Certificate Warning 🔴
- **Notice:** Users may encounter a security warning indicating that the APKs are unsafe. This warning is triggered by the custom SSL certificate used for signing the APKs.

### Why This Warning Appears ℹ️
- **Reason:** Android systems flag apps signed with custom or unfamiliar SSL certificates as potential security risks. This is a standard precautionary measure.

### Safety Assurance ✅
- **Safety:** Despite this warning, please be assured that these APKs are safe to use. They have been modified only to enable SSL bypassing, which is essential for analyzing Instagram's private API traffic.

### User Responsibility ⚠️
- **Caution:** Users should understand the implications of bypassing SSL and ensure they are complying with legal and ethical guidelines in their use of these APKs.


## App Details
- **App Name:** Instagram
- **Package Name:** com.instagram.android
- **Version:** 309.1.0.41.113
- **Supported Architectures:** x86, ARM (armeabi-v7a), ARM64 (arm64-v8a)


## Modified APK Files

### Instagram_309.1.0.41.113_x86_nr.apk
- **Architecture:** x86
- **Description:** This version is tailored for devices or emulators that operate on an x86 architecture. It is ideal for debugging on x86 Android emulators.

### Instagram_309.1.0.41.113_armeabi-v7a_nr.apk
- **Architecture:** ARM (armeabi-v7a)
- **Description:** This build is compatible with older and lower-end devices that use ARM architecture. It ensures broader compatibility, particularly with devices that do not support newer ARM versions.

### Instagram_309.1.0.41.113_arm64-v8a_nr.apk
- **Architecture:** ARM64 (arm64-v8a)
- **Description:** Optimized for modern devices with ARM64 architecture, this APK offers enhanced performance and stability on the latest Android devices.

## APK Comparison

| APK File | Architecture | Description |
|----------|--------------|-------------|
| Instagram_309.1.0.41.113_x86_nr.apk | x86 | Suitable for x86 devices/emulators. Ideal for debugging on x86 platforms. |
| Instagram_309.1.0.41.113_armeabi-v7a_nr.apk | ARM (armeabi-v7a) | Compatible with older and low-end ARM devices. Ensures broader device compatibility. |
| Instagram_309.1.0.41.113_arm64-v8a_nr.apk | ARM64 (arm64-v8a) | Optimized for modern ARM64 devices. Provides enhanced performance and stability. |

## Features
- **SSL Bypass Patch:** Enables the interception of encrypted network traffic, facilitating the analysis of Instagram's private API calls.
- **Multiple Architectures:** Tailored APKs for x86, ARM, and ARM64 architectures, enhancing compatibility across different Android devices and emulators.

## Usage Instructions
1. Select the APK corresponding to your device's architecture.
2. Download and install the APK on your Android device or emulator.
   - Ensure that 'Installation from unknown sources' is enabled in your device settings.
3. Download and install BurpSuite.. 
   - Follow [these instructions](https://portswigger.net/burp/documentation/desktop/mobile/config-android-device) to set up a proxy server with BurpSuite.

## Disclaimer
These modified APKs are for educational and research purposes only. It is essential to comply with all legal and ethical guidelines when intercepting network traffic.

## Contributing
Contributions to this project are welcome. Please submit issues or pull requests for improvements or bug fixes.

## Updates
For new updates, please send an email to tarun360@duck.com. I will try to provide updates as and when I have some free time.

## Support
For any issues or queries, feel free to open an issue.

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.
