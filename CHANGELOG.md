# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1] - 2026-11-26

### Fixed

- resolve katex and js-yaml security alerts in dev dependencies (#61)
- use client-id instead of the deprecated app-id for the bot token (#55)
- ignore TypeScript 7 and ESLint 10 updates until the lint tooling supports them (#47)
- use the real repository description (#45)

### Changed

- deps-dev(deps-dev): bump @types/node from 25.3.2 to 26.6.6 (#53)
- bump @winccoa-tools-pack/npm-winccoa-core (#51)
- bump minimatch and markdownlint-cli (#41)
- replace the old Pre-Release (Develop) workflow with the Pre-Release (Alpha) variant (#57)
- deps-dev(deps-dev): bump @eslint/js from 9.39.3 to 9.39.5 (#52)
- align .github files and scripts with the template (#58)
- prefer REPO_ADMIN_TOKEN over the bot app token for merges and branch updates (#56)
- deps-dev(deps-dev): bump markdownlint from 0.40.0 to 0.42.2 (#54)
- deps-dev(deps-dev): bump typescript from 5.9.3 to 6.0.3 (#48)
- use the winccoa-tools-pack-bot app token for automated PR actions (#49)
- bump softprops/action-gh-release from 2 to 3 (#18)
- bump actions/upload-artifact from 6 to 7 (#2)
- bump actions/checkout from 6 to 7 (#29)
- bump actions/setup-node from 6 to 7 (#50)
- deps-dev(deps-dev): bump flatted from 3.3.3 to 3.4.4 (#11)
- run integration tests manually and warn on limited test coverage (#44)
- add apply-settings helper scripts and actions policy (#43)
- auto-release patch and minor releases (#42)
- deps-dev(deps-dev): bump markdownlint-cli from 0.47.0 to 0.50.0 (#32)
- deps-dev(deps-dev): bump prettier (#28)
- deps-dev(deps-dev): bump linkify-it from 5.0.0 to 5.0.2 (#36)
- deps-dev(deps-dev): bump globals from 17.3.0 to 17.14.0 (#31)
- deps-dev(deps-dev): bump @humanfs/node from 0.16.7 to 0.16.8 (#38)
- deps-dev(deps-dev): bump typescript-eslint from 8.56.1 to 8.73.0 (#30)
- bump esbuild and tsx (#34)
- deps-dev(deps-dev): bump brace-expansion from 1.1.12 to 1.1.22 (#40)
- align .github with template-npm-shared-library (#27)
- Feature/initial setup (#8)

## [0.2.0] - 2026-03-03

### Changed

- Add changelog generation and validation scripts, update workflows, and repository settings (#33)
- Add peer dependencies to package-lock.json and implement CLI tests for argument parsing (#32)
- update template
- Add actions to sync org and template files
- Update sync-template-files.yml
- Update sync-template-files.yml
- Create sync-template-files.yml
- Create sync-org-files.yml
- Update bug_report.yml
- upmerge from core npm
- bump actions/upload-artifact from 5 to 6
- add setup-gitflow and gitflow-action workflows
- Add Buy Me a Coffee funding option

## [Unreleased]

### Documentation

- Align README CLI/API examples with actual tool behavior (in-place conversion, required version).

## [0.1.0] - 2026-02-28

### Added

- Core converter `PnlXmlConverter` wrapping WinCC OA `WCCOAui` `-xmlConvert`.
- CLI `winccoa-pnl-xml` with `convert pnl-to-xml` / `convert xml-to-pnl`.
- TypeScript API convenience functions `pnlToXml()` and `xmlToPnl()`.
- Unit tests covering CLI parsing, API wrappers, and converter arguments.
