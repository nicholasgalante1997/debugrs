# Changelog

> This changelog accords to the [Common Changelog Spec](https://github.com/vweevers/common-changelog/tree/main).

## [0.2.2] - 06-06-2025

### Changed

- Bumped dependencies to latest (rand, chrono, once_cell)

## [v0.2.1] - 01-23-2025

### Added

- Adds `debug` macro for variable arg formatting

### Changed

- Makes write<T: Display> more flexible

### Removed

- eprintln statements (fail silently).

## [v0.2.0] - 12-09-2024

### Added

- Checks for terminal color support
- Verbose warning messaging on missing env variables
- `RsDebugger::init_env()` to be used to consolidate env variable setup (optional)
- Thread safety for mutable properties in `RsDebugger`

### Changed

- Lazy initializes embedded emoji string search pattern

## [v0.1.0] - 12-04-2024

_Initial release._

### Added

- Environment based filtering based on the `DEBUG` variable
- ANSI color output
- Embedded emoji string support
- Hierarchal debugger extensions
- Timed logging events
