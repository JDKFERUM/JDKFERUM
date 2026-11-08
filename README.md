# JDKFERUM

Small tools for Windows, Linux and macOS. Read-only by default, dry runs
everywhere, no telemetry.

## Repositories

- [ps-disk-tools](https://github.com/JDKFERUM/ps-disk-tools) — folder sizes,
  large files and empty folders in PowerShell; `-WhatIf` before anything is
  removed.
- [ps-log-cleanup](https://github.com/JDKFERUM/ps-log-cleanup) — remove log files
  older than N days, filter by extension, dry run by default.
- [exif-clean](https://github.com/JDKFERUM/exif-clean) — strip EXIF and XMP from
  JPEGs before sharing them, without re-encoding the picture.
- [pointer-glide](https://github.com/JDKFERUM/pointer-glide) — accessibility
  helper for Linux and macOS: the pointer centres and glides straight down at
  one of ten speeds.

## Notes

- Python projects need Python 3.10+, PowerShell modules need PowerShell 7+.
- Anything that deletes or overwrites files starts with a dry run.
- Tests are plain scripts: `python -m pytest` or `pwsh -File tests/<name>.Tests.ps1`.
