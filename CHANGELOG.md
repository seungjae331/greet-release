# Changelog

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog 1.1.0](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2026-11-09

### Added
- `greet(name, punctuation="!")`: fixed exclamation mark → optional custom punctuation while preserving the default.

### Fixed
- `greet(name)`: empty or whitespace-only names produced a blank greeting → use `world` instead.

## [0.1.0] - 2026-11-09

### Added
- Introduce `greet(name)` and the command-line greeting: no greeting API or CLI → `Hello, <name>!`, with `world` as the CLI default.
