# Changelog

All notable changes to this collection will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

### Added

- pre-commit checks aligned with [zjleblanc.utils](https://github.com/autodotes/zjleblanc.utils/blob/main/.pre-commit-config.yaml), covering whitespace, yamllint, ruff, shellcheck, gitleaks, and ansible-lint.

### Changed

- Collection content now lives at the repository root. The publish workflow builds from `.` and writes the release version into `galaxy.yml`.
- `requires_ansible` is `>=2.15.0`.
- Collection README role links are relative paths and include `cve`, `dnf`, and `table_per_host`.
- `galaxy.yml` `build_ignore` excludes repository tooling so it is not packaged in the collection artifact.

## [1.5.1] and earlier

Releases prior to this file being introduced were tracked only via [GitHub tags](https://github.com/autodotes/zjleblanc.reporting/tags) and commit history.
