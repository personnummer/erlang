# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

- Use the `+` separator from the calendar year a person turns 100, preserving
  the birth century when short-format personnummer are parsed again.
- Reject inputs with trailing newlines instead of accepting them as valid
  personnummer.

## [3.1.1] - 2026-10-15

### Changed

- Moved the repository to [personnummer/erlang](https://github.com/personnummer/erlang).
  The Hex package name remains `personnummer_erl`.

## [3.1.0] - 2026-05-03

### Added

- Initial implementation of the
  [personnummer specification v3.1](https://github.com/personnummer/meta).

[Unreleased]: https://github.com/personnummer/erlang/compare/v3.1.1...HEAD
[3.1.1]: https://github.com/personnummer/erlang/compare/v3.1.0...v3.1.1
[3.1.0]: https://github.com/personnummer/erlang/releases/tag/v3.1.0
