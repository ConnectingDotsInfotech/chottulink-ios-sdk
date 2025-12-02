# 📋 Changelog

All notable changes to the **ChottuLink iOS SDK** will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/).

---

## [1.0.8] – 2025-12-02

### ✅ Added
- **Exposed `shortLinkRaw` in `getAppLinkDataFromUrl` method**: Direct access to raw short link data for enhanced link analytics and tracking
- **3-second delay for missing credentials**: Added automatic 3-second delay in `handleLink` methods when credentials are missing to improve reliability and reduce transient failures

### 🛠️ Improvements
- **Enhanced Error Handling**: Improved error handling across all methods with more descriptive error messages and better error recovery mechanisms
- Better error reporting for debugging and troubleshooting
- More robust handling of edge cases and network failures

## [1.0.7] – 2025-11-24

### ✅ Added
- **Enhanced Metadata Support**: Expose `shortLinkRaw` in metadata
- Improved access to short link information for analytics and tracking purposes

## [1.0.5] – 2025-10-23
- **Minor bug fixes** to improve stability and reliability
- Improved error handling and edge case coverage
- Enhanced overall SDK performance

## [1.0.4] – 2025-09-18

### ✅ Added
- **Expanded Device Support**: Lowered minimum iOS requirement from 15.6 to 15.0
- **Broader Compatibility**: Now supports older iOS devices running iOS 15.0+

### 🛠️ Improvements
- Enhanced device compatibility without breaking existing functionality
- Maintained full backward compatibility with all previous versions

## [1.0.3] – 2025-07-09

### ✅ Added
- **Cross-Platform API Consistency**: New `getAppLinkDataFromUrl(from:)` method for SDK consistency
- **Enhanced Error Handling**: Improved error handling and logging

### ⚠️ Breaking Changes
- **Removed `resolveDynamicLink(from:)` method** - Migration required to new API

## [1.0.2] – 2025-07-08

### ✅ Added
- **Async/Await Support**: New `resolveDynamicLink` method with modern Swift concurrency
- **Enhanced Type Safety**: Improved error handling and type safety
- **Updated Delegate Methods**: Enhanced metadata with originalURL support

### ⚠️ Breaking Changes
- `createDynamicLink` completion handler is now **deprecated** in favor of async version

### 🛠️ Improvements
- Maintained backward compatibility with existing implementations
- Enhanced error handling and type safety
- Improved delegate method metadata

### 📋 Notes
- The completion handler version of `createDynamicLink` is deprecated but will continue to work
- Consider migrating to the new async/await API for better performance and modern Swift practices

---

## [1.0.1] – 2025-06-29

### ✅ Added
- Support for **Apple Silicon (arm64)** and **Intel (x86_64)** simulators via updated `XCFramework`
- Enhanced compatibility for M1/M2/M3 Macs and Xcode's simulator environments

### 🐛 Fixed
- Architecture mismatch errors during simulator builds

### 📋 Notes
- No API changes
- Fully backward compatible with `v1.0.0`
- XCFramework now supports both Intel and Apple Silicon Macs

---

## [1.0.0] – 2025-06-10

### Added
- 🚀 Initial release of ChottuLink iOS SDK
- Deep link handling
- Dynamic link creation
- Deferred deep link support
- Basic analytics integration
- Thread-safe SDK initialization and execution
- Swift Package Manager and manual integration support

---

## 📌 Format Legend
- ✅ New features
- 🛠️ Improvements
- 🐛 Bug fixes
- ❗ Breaking changes
- 🔧 Internal/maintenance
