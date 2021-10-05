# Changelog
## 0.3.3
### Added

- Support for `.objectTranslation`

## 0.3.2

### Added

- improved readme

## 0.3.1

### Fixed

- bug with binary files being corrupted

## 0.3.1

### Fixed

- bug with ignore whitespace flag on non-modified changes

### Added

- Ability to pass flags into integration tests
- Test for ignore whitespace flag

## 0.3.0

### Added

- support for `ContentAsset`

## 0.2.1

### Fixed

- `HEAD` is case sensitive on linux

## 0.2.0

### Added

- Custom Label support
- Ability to transform metadata source
- started using semantic versioning

## 0.1.3

### Fixed

- Crash when spaces in project path (for windows)

## 0.1.2

### Fixed

- Crash when spaces in project path

## 0.1.1

### Fixed

- Bug with email templates

## 0.1.0

### Changed

- if left blank, `--sourceref|-s` now default to head. Can no longer target vs working copy.
- deletions are now put into `destructiveChangesPost.xml` instead of `destructiveChanges.xml`

### Fixed

- Fixed bug where package was not added for destructive only changes
