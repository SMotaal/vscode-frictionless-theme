# Change Log

<!--
All notable changes to the "experimental-theme" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.
 -->

<!--
 TODO: Best approach to incorporate into a theme?
 SEE: https://github.com/PKief/vscode-material-icon-theme/issues/559
-->

## [`0.1.1`] — 2019-10-12

- Improve rules for token colors — `jsdoc`, and `json` and `html` mostly
- Shorten color definitions — ie `#xxx` and `#xxxx`

## [`0.1.0`] — 2019-10-02

- Initial release

## [`0.0.1`] — 2019-10-02

- Prerelease release

## [Unreleased `0.0.1-alpha.2b`] - 2019-10-02

### Changed

- Harmonized `light`/`dark` blending for all UI aspects
- Enhanced `light`/`dark` background and contrast
- Improved cascading of token colors — now closer to `markup-light`

## [Unreleased `0.0.1-alpha.2`] - 2019-09-30

### Added

- Created `themes/tokens.json` for token colors
- Created `themes/base.json` with a new blending model — extending `tokens.json`
  - Implemented a new blending color scheme model
- Created `themes/light.json` and `themes/dark.json` — extending `base.json`
  - Added `light`/`dark` blend overrides for dominant token colors
- Created static [markout](smotaal.io/markout) content
  - Created `.nojekyll` to disable github pages prerendering
  - Created `index.html` redirect page

### Changed

- Updated `package.json` to reflect `frictionless` prefix and requirements for new blend theme
  - Switched to support `vscode^1.38.0` upwards
  - Defined `frictionless-material` in `contributions:iconThemes` — replaces `#experimental-icon-theme`
  - Defined `frictionless-light` and `frictionless-dark` in `contributions:themes` — replaces `#experimental-light-theme`
- Simplified color values in `themes/`
  - Rounded principal colors to `#0369c0` steps
- Deleted `themes/experimental-light.json` variant
- Refactored `meta/` artifacts
  - Moved `vsc-extension-quickstart.md` into `meta/`
- Refactored `icons/pkief-material-icons/` artifacts
  - Renamed `icons/experimental-icon-theme.json` to `icons/pkief-material-icons.json`
  - Renamed `icons/material-icons/` to `icons/pkief-material-icons/`

### Fixed

- Fixed `dark` contrast for `<kbd>` elements
- Fixed `light`/`dark` active line number element vibrance

## [Unreleased `0.0.1-alpha.1`] - 2019-03-30

### Added

- Added `experimental-light.json` (adopted from `markup-light`)
- Added icon theme from [PKief/vscode-material-icon-theme](https://github.com/PKief/vscode-material-icon-theme)
