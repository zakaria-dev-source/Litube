Description

This is a privacy-enhanced fork of Litube, an advanced WebView wrapper for YouTube. This modified version focuses on improving user privacy by removing potentially invasive third-party libraries and dependencies.

Key Features

Advanced YouTube WebView wrapper

Video download functionality

Hide YouTube Shorts

Display dislikes counter

Custom themes and styling

Multi-language support

Enhanced privacy (no tracking libraries)

Privacy Improvements

This modified version includes the following privacy enhancements:

Removed Libraries:

Tencent MMKV (com.tencent.mmkv)

Reason: Chinese company with potential privacy concerns

Native library difficult to audit

Replaced with: Android native SharedPreferences/Room

Square Picasso (com.squareup.picasso)

Reason: Potential image loading tracking may send analytics data

Replaced with: Privacy-focused alternative (Coil/Glide or custom solution)

Google libraries (reduced to minimum)

Kept only essential utilities (Google Common)

Removed unnecessary dependencies
What Remains:

com.google.common - Essential utilities only

com.coremedia.iso - Video file processing (necessary for functionality)
Releases

Download the latest APK from the Releases page.

Current Version: v2.0.0-privacy-enhanced

File: litube.apk

Size: ~14 MB

Android: 5.0+ (API 21+)

Security

✅️ Scanned by https://www.virustotal.com/gui/file/e05ebaf402b9dd1a8694cccad0af4c106f598d9199b8fa231b20602fb1cd3292/detection

✅ No tracking libraries

✅ No telemetry

✅ Minimal third-party dependencies

✅ Full transparency (unobfuscated code)

✅ Self-signed with private key

Installation

Download the APK from Releases

Enable "Install from Unknown Sources" in Android settings

Install the APK

Enjoy YouTube with enhanced privacy!

⚠️ Disclaimer

This is an unofficial modified version. Use at your own discretion. The original Litube project can be found at: https://github.com/HydeYYHH/litube

🤝 Contributing

Feel free to open issues or submit pull requests for improvements.

📄 License

This project maintains the same license as the original Litube project.

🙏 Credits

Original Litube: HydeYYHH

Privacy modifications by: zakaria-dev-source
