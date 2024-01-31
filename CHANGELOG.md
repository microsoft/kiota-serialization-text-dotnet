# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

### Changed

## [1.1.2] - 2024-01-30

### Changed

- Fixed AOT warnings with reflection being used for enum types.

## [1.1.1] - 2023-11-15

### Added

- Added support for dotnet 8.

## [1.1.0] - 2023-10-23

### Added

- Added support for dotnet trimming.

## [1.0.3] - 2023-07-14

### Changed

- Change to encoding on underlying stream [#85](https://github.com/microsoft/kiota-serialization-text-dotnet/issues/85) to match default used by `StreamWriter` class.

## [1.0.2] - 2023-07-12

### Changed

- Fix for unreadable stream [#82](https://github.com/microsoft/kiota-serialization-text-dotnet/issues/82)

## [1.0.1] - 2023-03-10

### Changed

- Bumps abstraction dependency

## [1.0.0] - 2023-02-27

### Added

- GA release

## [1.0.0-rc.3] - 2023-01-27

### Changed

- Relaxed nullability tolerance when merging objects for composed types.

## [1.0.0-rc.2] - 2023-01-17

### Changed

- Adds support for nullable reference types

## [1.0.0-rc.1] - 2022-12-15

### Changed

- Release candidate 1

## [1.0.0-preview.4] - 2022-09-02

### Added

- Added support for composed types serialization.

## [1.0.0-preview.3] - 2022-05-18

### Changed

- Updated abstractions version to 1.0.0.preview8

## [1.0.0-preview.2] - 2022-04-12

### Changed

- Breaking: Changes target runtime to netstandard2.0

## [1.0.0-preview.1] - 2022-03-18

### Added

- Initial Nuget release
