# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

Expected 5.X release

### Added

- Typedefs for public Objective-C blocks
- `NS_DESIGNATED_INITIALIZER` for required inits
- `NS_TYPED_EXTENSIBLE_ENUM` where made sense
- `getter` name for certain properties, like booleans
- `NS_ASSUME_NONNULL_BEGIN`, `NS_ASSUME_NONNULL_END`, and other nullability annotations
- Generics for Arrays, Sets, and Dictionaries
- `NS_SWIFT_NAME` to remove the `FBSDK` prefix where necessary (left `FB` prefix for UI elements)

### Changed

- Using `instancetype` for inits
- All `NSError **` translate to throws on Swift
- Updated Xcode Projects and Schemes to most Valid Project settings
- Getter methods changed to `readonly` properties
- Getter/Setter methods changed to `readwrite` properties
- Dot notation for access to properties
- Collections/Dictionaries became non null when at all possible
- Class creation methods become Swift inits

### Removed

- Deprecated methods
- Deprecated classes
- Deprecated properties
- Made `init` and `new` unavailable where necessary
- Used `NS_SWIFT_UNAVAILABLE` where necessary

### Fixed

- Various bug fixes

## [4.40.0] - 2019-01-17

### Fixed

- Various bug fixes

## [4.39.1] - 2019-01-08

### Other

- Facebook Developer Docs: [Changelog v4.x](https://developers.facebook.com/docs/ios/change-log-4x)

<!-- Links -->

[Unreleased]: https://github.com/facebook/facebook-objc-sdk/compare/v4.40.0...HEAD
[4.40.0]: https://github.com/facebook/facebook-objc-sdk/compare/v4.39.1...v4.40.0
[4.39.1]: https://github.com/facebook/facebook-objc-sdk/compare/sdk-version-4.0.0...v4.39.1
