# Release Notes for Blitz Hints

## 1.2.3 - 2024-04-16

### Fixed

- Fixed a bug in which that `stackTrace` column was being written to when it did not exist.

## 1.2.2 - 2024-03-12

### Fixed

- Fixed a bug that could throw an error when conditional variables were used in an `extends` tag ([#632](https://github.com/putyourlightson/craft-blitz/issues/632)).

## 1.2.1 - 2024-03-11

### Changed

- The template stack trace is now updated if different for the same field-template combination.

## 1.2.0 - 2024-03-11

### Added

- Added a template stack trace to each hint ([#16](https://github.com/putyourlightson/craft-blitz-recommendations/issues/16)).

## 1.1.1 - 2023-11-01

### Changed

- Changed the module and utility icon.

## 1.1.0 - 2023-10-31

### Changed

- Templates that exist in the vendor folder path are now ignored ([#574](https://github.com/putyourlightson/craft-blitz/issues/574)).

## 1.0.2 - 2023-03-03

### Changed

- Replaced `.collect()` with `.all()` in hint example.

## 1.0.1 - 2022-05-16

### Fixed

- Fixed incorrect behaviour in environments in which `devMode` was disabled.

## 1.0.0 - 2022-05-16

- Initial release.
