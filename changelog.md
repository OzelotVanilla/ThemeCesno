# Change Log

All notable changes to this theme will be documented in this file.

The main structure is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

The date format is `MM/DD/YYYY` (if necessary, `hh24:mm:ss` will be appended).

The version names of this project follows this rule (idea borrowed from [Semantic Versioning](https://semver.org/spec/v2.0.0.html)).
for a version number `major.minor.update.patch`:
* `major`: incompatible changes (probably not in this project).
* `minor`: group of functionality updates (e.g. noticeable UI/UX changes)
* `update`: single release of functionality (e.g. added new colour definition for tokens)
* `patch`: bugfix, typo fix, format or other changes that does not affect functionality. Omit if empty.

## [Unreleased]

## [0.0.8]

### Fixed

* Wrong colorisation of string, comment, punctuation, enum member and operators.

### Added

* Colour of the asterisk of JavaScript generator.

## [0.0.7]

### Fixed

* Some flow keywords cannot be highlighted correctly.

### Change

* Add modifier `default` for JavaScript/TypeScript.
* Change colour of import path for C++.

## [0.0.6]

### Fixed

* Some operators cannot be highlighted correctly.

## [0.0.5]

### Fixed

* Some operators cannot be highlighted correctly.
* Object member fallback.

### Change

* For visual enhance, and TS type notation, arrow in arrow function is now
  rendered as "type".

## [0.0.4]

### Fixed

* Some control keywords or operators not highlighted correctly.
* Class member accessor added to punctuation.
* Function declaration colour added.

### Added

* HTML tag attribute is now in italic.

## [0.0.3]

### Fixed

* Wrong fallback "bold" style.
* Too greedy punctuation.

### Added

* Example picture of *Quiet Cesno*.
* Various tokens are with highlight colour now.

## [0.0.2] - 10/07/2023

### Added

* Add pale grey colour `#777777` for punctuation.

## [0.0.1] - 10/06/2023

### Added

* Crude version of *Quiet Cesno* theme.