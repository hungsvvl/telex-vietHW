# VietKey Privacy Policy

Privacy Policy URLs:

```text
English/Vietnamese: https://hungsvvl.github.io/telex-vietHW/privacy-policy/
Simplified Chinese: https://hungsvvl.github.io/telex-vietHW/privacy-policy/zh-cn/
```

## Âm lịch Việt Nam

Simplified Chinese (default for AppGallery China):
`https://hungsvvl.github.io/telex-vietHW/privacy-policy/amlich-vietnam/`

The standalone page above is for the HarmonyOS NEXT app `com.amlich.vietnam`.
It is kept in a separate folder so the VietKey policy URLs remain unchanged.

## G Navigation

Privacy Policy URLs:

```text
Vietnamese (default): https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-navigation/
English: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-navigation/en/
Simplified Chinese: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-navigation/zh-cn/
```

These standalone pages cover G Navigation for Android (`com.gnavigation.mobile`),
Huawei Watch Full, and Huawei Watch Lite (`com.gnavigation.watch`). They are kept
in a separate folder so the VietKey and Âm lịch Việt Nam policy URLs remain unchanged.

## G Navigation watch app (Huawei Lite Wearable)

Privacy Policy URLs:

```text
Vietnamese (default): https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-navigation-watch/
English: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-navigation-watch/en/
Simplified Chinese: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-navigation-watch/zh-cn/
Vietnamese fallback alias: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-navigation-watch/vi/
Chinese fallback alias: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-navigation-watch/zh/
```

These pages cover only the watch-side processing of the G Navigation watch app
`com.gnavigation.watch` from version 1.1 on, the app formerly tested as G Viewer: guidance,
map images and route position received from authenticated G Navigation Android
(`com.gnavigation.mobile`) over Huawei Wear Engine, the local consent marker, display
preferences and device profile. The phone app and the older 1.0.121 watch app remain covered
by the G Navigation pages above. The QR assets
`g-navigation-watch/g-navigation-watch-privacy-qr.svg` and `.png` encode the canonical
Vietnamese HTTPS URL above.

Setup-and-use guide (not a policy; linked from the watch's "Not connected" screen through a
QR code):

```text
Vietnamese (default): https://hungsvvl.github.io/telex-vietHW/g-navigation/guide/
English: https://hungsvvl.github.io/telex-vietHW/g-navigation/guide/en/
Simplified Chinese: https://hungsvvl.github.io/telex-vietHW/g-navigation/guide/zh-cn/
```

## G Viewer

Privacy Policy URLs:

```text
Vietnamese (default): https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-viewer/
English: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-viewer/en/
Simplified Chinese: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-viewer/zh-cn/
Vietnamese fallback alias: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-viewer/vi/
Chinese fallback alias: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-viewer/zh/
```

These standalone pages cover the text-only Huawei Lite Wearable application
`com.gviewer.watch`. They describe only G Viewer's watch-side processing: live
text guidance in volatile memory, the local consent marker, and the Huawei Wear
Engine P2P link to authenticated G Navigation Android
(`com.gnavigation.mobile`). The QR assets `g-viewer/g-viewer-privacy-qr.svg`
and `g-viewer/g-viewer-privacy-qr.png` encode the canonical Vietnamese HTTPS
URL above. No G Navigation phone-policy scope is copied into this document.

Setup-and-use guide (not a policy; linked from the watch's "Not connected"
screen through a QR code):

```text
Vietnamese (default): https://hungsvvl.github.io/telex-vietHW/g-viewer/guide/
English: https://hungsvvl.github.io/telex-vietHW/g-viewer/guide/en/
Simplified Chinese: https://hungsvvl.github.io/telex-vietHW/g-viewer/guide/zh-cn/
```

## App Information

- App name: VietKey
- Bundle ID: `com.vietnam.keyboard`
- Platform: HarmonyOS NEXT
- Supported devices: Mobile phone, Tablet
- Developer and data controller: `NGUYEN THANH HUNG`
- Contact: hng89tn@gmail.com or https://github.com/hungsvvl/telex-vietHW/issues
- Last updated: July 30, 2026

## Real Permission Usage

| Permission | Permission name | Supported device | Usage reason |
| --- | --- | --- | --- |
| Record audio / Microphone | `ohos.permission.MICROPHONE` | Mobile phone, Tablet | Used for speech recognition to input text. Permission is requested only after the user accepts the privacy notice and explicitly starts Voice to Text. Audio is processed locally and is not uploaded, shared, or permanently stored. |
| Read clipboard | `ohos.permission.READ_PASTEBOARD` | Mobile phone, Tablet | Used only after privacy acceptance and an explicit clipboard action to show paste suggestions and maintain the optional local clipboard history. Clipboard text is not uploaded or shared. |
| Vibrate | `ohos.permission.VIBRATE` | Mobile phone, Tablet | Used to provide haptic feedback when the user presses keys. |

## Data Handling

- Keyboard input is processed locally to provide Telex/VNI/Pinyin typing.
- VietKey does not store per-key logs or upload keyboard text.
- VietKey does not include analytics, advertising, or third-party tracking SDKs.
- The current app package does not declare an internet permission.
- Offline Voice to Text uses bundled model files on the device. Voice audio is processed locally and is not permanently stored by VietKey.
- Clipboard data access is optional and remains inactive until the user explicitly enables/uses the feature and grants permission. VietKey stores at most 20 recent items and 20 pinned items locally. Each item is limited to 10,000 characters.
- After privacy acceptance, bounded on-device suggestion learning is enabled by default. Vietnamese learned-word/context counters, Chinese word/pair counters, and the Pinyin user dictionary stay in local app storage and are never uploaded.
- Complete sentences, full input-field contents, links, code, and per-key logs are not stored as learning data. Learning can be disabled, and all learned language data can be cleared without deleting the custom dictionary.
- Keyboard settings, custom shortcuts, and user preferences are stored locally on the device.
- A keyboard background image selected through the system Photo Picker is copied into VietKey's private app storage only for local rendering. It is not uploaded and can be removed from Theme settings, by resetting app settings, by clearing app data, or by uninstalling VietKey.

## Consent and Controls

- VietKey presents an in-app privacy notice before requesting Microphone or Read clipboard permission.
- Declining the notice does not block the core keyboard. Voice input and clipboard features remain unavailable until the user accepts and deliberately invokes them.
- Accepting the notice enables bounded on-device suggestion learning by default. The user can disable learning or clear learned data at any time.
- The user can review the full policy, withdraw consent, manage system permissions, delete learned data, and delete local clipboard history from **About > Privacy Policy**.
- Withdrawing consent immediately disables learning and stops VietKey from starting voice input or reading clipboard content. Previously granted HarmonyOS permissions can also be revoked from the system permission settings.

## Vietnamese Summary

VietKey không lưu nhật ký từng phím, không tải văn bản hoặc âm thanh lên máy chủ và không dùng SDK quảng cáo/theo dõi. Sau khi người dùng đồng ý chính sách, học gợi ý giới hạn trên thiết bị được bật mặc định và có thể tắt hoặc xóa bất cứ lúc nào. Ứng dụng chỉ xin quyền micro hoặc đọc bộ nhớ tạm sau khi người dùng đồng ý và chủ động dùng tính năng tương ứng.

## Chinese Summary

VietKey 不保存逐键日志，不会将文本或音频上传到服务器，也不使用广告、分析或第三方跟踪 SDK。用户同意政策后，有限的设备端建议学习将默认启用，并可随时关闭或清除。仅在用户同意隐私提示并主动使用相应功能后，应用才会申请麦克风或读取剪贴板权限。

## Contact

For privacy, support, or deletion requests, please contact:

mailto:hng89tn@gmail.com
https://github.com/hungsvvl/telex-vietHW/issues

## G Navigation for iOS

Privacy Policy URLs:

```text
Vietnamese (default): https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-navigation-ios/
English: https://hungsvvl.github.io/telex-vietHW/privacy-policy/g-navigation-ios/en/
```

The iOS app is its own page because it is its own app: it reads no notifications,
records no audio, has no account, no trial and no Premium, and talks to a
different set of services than the Android build. The URL above is the one in
App Store Connect and in the app's own Settings tab.
