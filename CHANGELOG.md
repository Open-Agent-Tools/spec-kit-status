# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-02-27

### Added

- `/speckit.status` command — display project status, feature progress, and recommended next actions
- Support for `--all`, `--verbose`, `--json`, and `--feature` flags
- Bash discovery script (`scripts/bash/get-project-status.sh`)
- PowerShell discovery script (`scripts/powershell/Get-ProjectStatus.ps1`)
- Pipeline view showing all features with workflow stages (Specify → Plan → Tasks → Implement)
- Artifact status for the current/selected feature
- Task completion tracking for features in implementation
- Next action recommendations based on current state
- JSON output format for machine-readable integration

[1.0.0]: https://github.com/Open-Agent-Tools/spec-kit-status/releases/tag/v1.0.0
