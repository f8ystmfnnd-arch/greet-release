# Changelog

This file records changes visible to users.
This project follows Keep a Changelog 1.1.0 and Semantic Versioning.

## [Unreleased]

### Added
- `greet()` previously always used `!` and now accepts an optional `punctuation` argument that defaults to `!`.

### Fixed
- `greet()` now returns `Hello, world!` for empty or whitespace-only names instead of displaying the blank name.

## [0.1.0] - 2026-11-09

### Added
- Added `greet(name)` and a command-line greeting that defaults to `world`.
