# Changelog

All notable changes to CorpusCustody are documented in this file.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Changed

- Rule tables are being reorganised for the next patch.

## [1.0.1] - 2026-07-07

### Fixed

- The gate refuses a manifest whose declared purpose is unknown instead of
  falling back to the strictest preset.
- A fixture for the unknown purpose, and the smoke run now covers it.
