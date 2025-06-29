[![Version](https://img.shields.io/badge/version-1.0.1-blue.svg)](https://github.com/yourusername/ChottuLinkSDK/releases)
# ChottuLinkSDK

## 🚀 What's New in v1.0.1

This release adds full simulator support for both **Apple Silicon (arm64)** and **Intel (x86_64)** Macs via an updated `XCFramework`.

## ✨ Features

- Deep Link Handling
- Dynamic Link Creation
- Deferred Deep Links
- Analytics Integration
- ✅ Apple Silicon & Intel simulator compatibility (new in `v1.0.1`)

## 📋 Requirements

- iOS 15.6+
- Xcode 16.0+
- Swift 6.0+

## 🚀 Installation

### ✅ Swift Package Manager (Recommended)

Use the following in your Package.swift:

```swift
dependencies: [
    .package(url: "https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk", from: "1.0.1")
]
```
> [!TIP]
> Make sure to replace `1.0.1` with the latest version of the SDK. You can find the latest version on our [GitHub repository](https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk/releases).

### 📦 Manual Installation

1. Download the latest `ChottuLinkSDK-x.x.x-xcframework.zip` from the [Github Releases](https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk/releases)
2. Extract the zip file
3. Drag `ChottuLinkSDK.xcframework` into your project
4. Ensure it is embedded in your target under "Frameworks, Libraries, and Embedded Content"

## 🔍 File Integrity

To verify the authenticity of the downloaded XCFramework:

### SHA256 hash:

```txt
23588f12c2634f63062dc25170cac613567f60480285b7a5800043f6c17218b0
```

### You can check it using the terminal:

```bash
shasum -a 256 ChottuLinkSDK-x.x.x-xcframework.zip
```

> [!TIP]
> Make sure to replace `x.x.x` with the latest version of the SDK. You can find the latest version on our [GitHub repository](https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk/releases).

## ⚡ Quick Start

1. [Configure ChottuLink Dashboard](https://docs.chottulink.com/get-started/ios-setup#-configure-chottulink-dashboard)
    - Set up your project
    - Configure iOS app settings
    - Get your API key
2. [Install ChottuLink iOS SDK](https://docs.chottulink.com/get-started/ios-setup#-installation)
    - Using Swift Package Manager _(recommended)_
    - Or manual installation
3. [Initialize ChottuLink iOS SDK](https://docs.chottulink.com/get-started/ios-setup#-initialize-the-chottulink-sdk)
    - Add initialization code to AppDelegate
    - Configure Universal Links

## 🧑‍💻 Documentation

- [Integration Guide](https://docs.chottulink.com/get-started/ios-setup)
- [API Reference](https://docs.chottulink.com/create-dynamic-links/rest-api-create)

## 🤝 Support

- [GitHub Issues](https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk/issues)
- [Documentation](https://docs.chottulink.com)

## 🙏 Acknowledgments

- Thanks to all beta testers
- Special thanks to our early adopters
- Community feedback and suggestions

## 🎯 What's Next

We're actively working on:
- More analytics features
- Enhanced campaign tracking
- Additional platform support
- Performance optimizations

## 🐛 Known Issues

- None in this release

## 📋 Changelog

### Latest – v1.0.1 (June 29, 2025)

- ✅ Added Apple Silicon (arm64) and Intel (x86_64) simulator support
- 🛠️ Improved XCFramework compatibility for modern Macs

[View full changelog →](https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk/blob/main/CHANGELOG.md)

> [!NOTE]
> This is our first release, and we welcome your feedback and suggestions for future improvements.
> Please report any issues or feature requests on our [GitHub Issues](https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk/issues) page.
