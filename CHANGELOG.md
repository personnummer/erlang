# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [3.1.2] - 2026-10-18

### Changed

- Add CI coverage for OTP 29 while retaining OTP 27 and 28 support.
- Pin the development toolchain to OTP 29.1.2, rebar3 3.27.3, and ELP 2026-10-14.
- Include Eqwalizer in `mise check` and use ELP's bundled support library and
  matching checker instead of separate local or Git dependencies.

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

[Unreleased]: https://github.com/personnummer/erlang/compare/v3.1.2...HEAD
[3.1.2]: https://github.com/personnummer/erlang/compare/v3.1.1...v3.1.2
[3.1.1]: https://github.com/personnummer/erlang/compare/v3.1.0...v3.1.1
[3.1.0]: https://github.com/personnummer/erlang/releases/tag/v3.1.0
