[![Version](https://img.shields.io/badge/version-1.0.2-blue.svg)](https://github.com/yourusername/ChottuLinkSDK/releases)
# ChottuLinkSDK

## 🚀 What's New in v1.0.2

This release introduces **async/await support** for dynamic link operations and improves type safety with enhanced error handling.

### ✨ New Features
- **Async/Await Support**: New `resolveDynamicLink` method with modern Swift concurrency
- **Enhanced Type Safety**: Improved error handling and type safety
- **Backward Compatibility**: Maintains support for existing implementations
- **Updated Delegate Methods**: Enhanced metadata with originalURL support

### ⚠️ Breaking Changes
- `createDynamicLink` completion handler is now **deprecated** in favor of async version

## ✨ Features

- Deep Link Handling
- Dynamic Link Creation (with async/await support)
- Deferred Deep Links
- Analytics Integration
- ✅ Apple Silicon & Intel simulator compatibility
- ✅ Modern Swift concurrency support (new in `v1.0.2`)

## 📋 Requirements

- iOS 15.6+
- Xcode 16.0+
- Swift 6.0+

## 🚀 Installation

### ✅ Swift Package Manager (Recommended)

Use the following in your Package.swift:

```swift
dependencies: [
    .package(url: "https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk", from: "1.0.2")
]
```
> [!TIP]
> Make sure to replace `1.0.2` with the latest version of the SDK. You can find the latest version on our [GitHub repository](https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk/releases).

### 📦 Manual Installation

1. Download the latest `ChottuLinkSDK-x.x.x-xcframework.zip` from the [Github Releases](https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk/releases)
2. Extract the zip file
3. Drag `ChottuLinkSDK.xcframework` into your project
4. Ensure it is embedded in your target under "Frameworks, Libraries, and Embedded Content"

## 🔍 File Integrity

To verify the authenticity of the downloaded XCFramework:

### SHA256 hash:

```txt
[Updated hash for v1.0.2 will be provided in release notes]
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

### Latest – v1.0.2 (July 8, 2025)

- ✅ Added `resolveDynamicLink` method with async/await support
- ⚠️ Deprecated `createDynamicLink` completion handler in favor of async version
- 🔧 Updated delegate method to include originalURL in metadata
- 🛠️ Improved type safety and error handling
- ✅ Maintained backward compatibility

[View full changelog →](https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk/blob/main/CHANGELOG.md)

> [!NOTE]
> **Migration Notice**: If you're using the completion handler version of `createDynamicLink`, consider migrating to the new async/await API for better performance and modern Swift practices. The completion handler version is deprecated but will continue to work for backward compatibility.
> 
> Please report any issues or feature requests on our [GitHub Issues](https://github.com/ConnectingDotsInfotech/chottulink-ios-sdk/issues) page.
