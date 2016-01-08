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

## [1.0.0] - 2025-09-30

### Added

- Stable CLI contract: `gate` and `report` with exit codes 0, 1 and 2.
- `docs/FORMAT.md` as the written contract for the manifest and the report.
- Deterministic JSON report with a fixed key order.

## [0.9.0] - 2024-06-25

### Added

- Refusal on unknown provenance: a record with no recognised license is a
  refusal, never a warning.
- `--purpose` presets for internal, redistribute and commercial use.

## [0.7.0] - 2021-11-02

### Added

- Compatibility rules between obligation sets, with the conflicting pair quoted
  in the finding.
- Line numbers on every manifest parse error instead of aborting the run.

