<!-- markdownlint-disable -->
# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v1.0.1] - 2020-09-06

### Added
- Super Linter config
- Dependabot config
- Privacy policy & contact pages
- Preloading of assets
- Add Google Analytics with external link click events

### Changed
- Numerous dependency updates
- Import updates to several components/`_include/`s
- Use Docker image for Super Linter
- Check for GitHub Actions updates weekly instead of daily
- Make all requests default to `"no-referrer"`

### Fixed
- Disable linting of bash scripts due to issue with `.rvmrc`

### Removed
- Delete unused config for theme and `dns-prefetch`

<!-- markdownlint-restore -->
