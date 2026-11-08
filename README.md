# JDKFERUM

Small PowerShell utilities for Windows maintenance. Everything here is meant to
be run by hand, with a dry run first.

## Repositories

- [ps-disk-tools](https://github.com/JDKFERUM/ps-disk-tools) — folder sizes,
  large files, empty folders; read-only helpers with a `-WhatIf` cleanup.
- [ps-log-cleanup](https://github.com/JDKFERUM/ps-log-cleanup) — remove log files
  older than N days, filters by extension, dry run by default.

## Notes

- No dependencies beyond PowerShell 7.
- Anything that deletes files starts with a dry run and needs an explicit
  `-Confirm:$false` to actually remove something.
- Tests are plain PowerShell scripts: `pwsh -File tests/<name>.Tests.ps1`.
