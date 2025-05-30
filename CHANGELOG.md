# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog][keepachangelog],
and this project adheres to [Semantic Versioning][semver].

## [Unreleased]

## [0.2.0] - 29/04/2025

### Changed
- Reworked grammar analysis to use installed textX meta-langauge.
- Make patterns more compact by grouping matches of the same kind.
- Use pyproject.toml instead of setup.py.

### Fixed

- scope name in lowercase in template for code generation


## [0.1.2] - 12/28/2019

### Fixed

- Escape non-ascii characters when generating textmate syntax highlighting ([#3])

[#3]: https://github.com/danixeee/textx-gen-coloring/pull/3

## [0.1.1] - 10/03/2019

### Added

- Option to exclude language keywords when generating coloring file ([#1])

### Fixed

- Return result when calling the generator ([#1])

[#1]: https://github.com/danixeee/textx-gen-coloring/pull/1

## [0.1.0] - 09/10/2019

### Added

- _textmate_ syntax highlighting generator
- _azure-pipelines_ CI setup
- _black_ formatter

[keepachangelog]: https://keepachangelog.com/en/1.0.0/
[semver]: https://semver.org/spec/v2.0.0.html

[Unreleased]: https://github.com/danixeee/textx-gen-coloring/compare/v0.1.2...HEAD
[0.1.2]: https://github.com/danixeee/textx-gen-coloring/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/danixeee/textx-gen-coloring/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/danixeee/textx-gen-coloring/compare/80eb53ad926e79c284d36213360ec75515740634...v0.1.0
