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

## [0.6.0] - 2020-11-24

### Added

- JSON report: `report --format json` with stable key order.
- Per-record obligation summaries in the report.

## [0.5.0] - 2019-10-07

### Added

- The obligation model: attribution, share-alike, notice and source disclosure
  as separate obligations, never collapsed into one flag.
- A worked gate run over the three bundled manifests.

## [0.4.0] - 2018-10-16

### Added

- Gate decisions per record: PASS, REFUSE, with the deciding rule named.
- Purpose differences documented, because the same corpus can pass one purpose
  and refuse another.

## [0.3.0] - 2017-12-05

### Added

- SPDX identifier parsing with a conservative fallback for unrecognised ids.
- Strict validation for record ids, licenses and source fields.

## [0.2.0] - 2016-09-20

### Added

- Manifest parser for mixed-provenance corpora.
- The first compatibility table between common licenses.

## [0.1.0] - 2015-04-27

### Added

- First release: record model and a line oriented report with a findings total.

<!-- draft note 1620 -->
