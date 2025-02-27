# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- ## Unreleased - YYYY-MM-DD

### Added

### Changed

### Deprecated

### Removed

### Fixed

### Security -->

## 0.7.0 - 2023-03-14

### Fixed

- Use `impl AsRef<str>` parameter instead of a generic `S: AsRef<str>` parameter;

## 0.6.0 - 2023-03-09

### Changed

- `FromHexPrefixed::from_hex_prefixed` takes a `S: AsRef<str>` parameter;
- `ToHexPrefixed::decode` takes a `S: AsRef<str>` parameter;

## 0.5.0 - 2022-10-10

### Changed

- Updated dependencies;

## 0.4.0 - 2022-05-05

### Added

- `std` feature;
- `impl std::error::Error for Error {}`;

## 0.3.0 - 2022-03-30

### Added

- Implementation of `ToHexPrefixed` for `Box<[u8]>` and `&Box<[u8]>`;

## 0.2.0 - 2022-03-17

### Added

- Implementation of `ToHexPrefixed` for `&[u8;N]`;

## 0.1.0 - 2022-03-17

### Added

- Initial features;
