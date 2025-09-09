# Changelog

All notable changes to this project will be documented in this file.

## [beta0.3.9] - 2025-09-09

### Fixed
- **ChatThrottleLib Compatibility**: Fixed AceComm-3.0 library errors caused by version incompatibility between modern WoW message length restrictions and vanilla WoW clients
- Implemented proper version detection instead of disabling safety checks
- Messages longer than 255 bytes now work correctly on vanilla/TurtleWoW while maintaining safety on modern clients

### Changed
- Updated README.md to better explain what the addon does

## [beta0.3.8] - Previous Release

### Notes
- Previous version had ChatThrottleLib errors that were temporarily fixed by commenting out error checks
- This version properly addresses the underlying compatibility issue
