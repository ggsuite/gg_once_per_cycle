# Changelog

## Unreleased

### Added

- Add .gitattributes file

### Changed

- Rework copyright headers

### Fixed

- Cleanup copy right headers. Update to dart 3.13. Auto fixes.

## 1.3.5 - 2024-04-13

### Removed

- dependency to gg_install_gg, remove ./check script
- dependency pana

## 1.3.4 - 2024-04-09

### Removed

- 'Pipline: Disable cache'

## 1.3.3 - 2024-04-09

### Changed

- Rework changelog
- 'Github Actions Pipeline'
- 'Github Actions Pipeline: Add SDK file containing flutter into .github/workflows to make github installing flutter and not dart SDK'

## 1.3.2 - 2024-01-01

- Update minimum SDK version
- Update check scripts & VSCode settings
- Fix warnings

## 1.3.1 - 2024-01-01

Add a `scheduleTask` callback via constructor or via `trigger()` to specify a own
task scheduler method, e.g. `Future.microtask`

## 1.2.0 - 2024-01-01

Add a `isTest` constructor parameter + `executeNow()` method control execution
in test szenarios.

## 1.1.0 - 2024-01-01

Added a `dispose` method to prevent late execution of asynchronous callbacks.

## 1.0.0 - 2024-01-01

Updated dependencies.

## 0.0.1+3 - 2024-01-01

Moved original source code to [https://github.com/inlavigo/gg_once_per_cycle](https://github.com/inlavigo/gg_once_per_cycle)

## 0.0.1+2 - 2024-01-01

- Cleaned up code

## 0.0.1+1 - 2024-01-01

- Initial version.
