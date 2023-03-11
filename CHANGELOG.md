# Change Log
All notable changes to the "CobaltNext" extension will be documented in this
file.

## [0.4.3] - 2023-03-10

### Fixed/Changed
* Fixed the issue where custom component and web-component tags didn't get the yellow color and appeared as normal tags. This wasn't an issue in react (as far as I'm aware), but it was causing a problem in Vue and a few other frame works.

## [0.4.0] - 2022-09-2

### Changed
* Change the color/styles for file diffs. Before diffs were hard to read because each line got a border and a background color. Now it's a cleaned up experience that more mimics github.

## [0.3.2] - 2020-10-1

### Changed
* Added support for native bracket color matching
  - To use native bracket color matching, remove the `Bracket Pair Colorizer` extension and add `"editor.bracketPairColorization.enabled": true,` to your `settings.json` file
* Updated README with updated settings

## [0.3.1] - 2020-10-1

### Changed
* Fixed highlight color on Dark and Minimal Themes

## [0.3.0] - 2020-9-16

### Added
* Added minimal version. While it's not super different from Cobalt Dark, it does have a few extra treats in there.
  - I strongly recommend going through [Caleb Porzio's](https://twitter.com/calebporzio) [Make VS Code Awesome](https://makevscodeawesome.com/) Course if you're going to use the Minimal Version.

## [0.2.7] - 2020-9-15

### Changed
* Fix the color for component in JSX because tokens have been updated

## [0.2.6] - 2020-8-8

### Changed
* Update terminal cursor styles for to show text behind cursor

## [0.2.5] - 2020-8-7

### Changed
* Updated the tab styles on the Dark Version.

## [0.2.3] - 2020-4-13

### Changed
* Updated the color of selections inside of inputs on the Dark Version.

## [0.2.2] - 2020-3-22

### Changed
* Updated the color of the `quickInput.foreground` for better visibility

## [0.2.1] - 2020-3-22

### Changed
* Updated Terminal Blacks for Original Theme
* Updated Dark Terminal
* Added All `ansiBright` Colors

## [0.2.0] - 2020-3-21

### Changed
* Added support for modified tab borders: `tab.activeModifiedBorder`, `tab.inactiveModifiedBorder`, `tab.unfocusedActiveModifiedBorder`, and `tab.unfocusedInactiveModifiedBorder`
* Add Dark Version of Theme `Cobalt Next Dark`
* Updated Readme for Dark Version

## [0.1.7] - 2019-12-28

### Changed
* Fix errors in readme

## [0.1.6] - 2019-11-27

### Changed
* Updated the active and inactive states in the activity bar.
* Updated Readme with settings for active and inactive states for window borders.

## [0.1.5] - 2019-##-##

### Changed
* Added Handlebars.hbs to the demo folder
* Remove `contrastBorder` and `contrastBorderActive` since they are only for high contrast themes and breaking the "Select Interpreter" panel
* Update Readme for suggested Handlebars extension

## [0.1.4] - 2019-6-7

### Changed
* Added new app icons to match VS Code's new icon

## [0.1.2]/[0.1.3] - 2019-6-4

### Changed
* Fixed `editorGutter.modifiedBackground` as suggested from #11
* Updated `editorOverviewRuler` colors to match merge and git colors

## [0.1.1] - 2019-3-21

### Changed
* Added recommended setting for Bracket Pair Colorizer 2 to README

## [0.1.0] - 2018-10-30

### Changed
* Update the Title Bar to be dark and and match the whole window.

### Added
* Added Code the make Title Bar silver again to the README

## [0.0.21] - 2018-10-24

### Added
* Update Inline Merge Conflict Border

## [0.0.20] - 2018-10-8

### Added
* Add Support for Input Validation (Closed Issue #6)

## [0.0.19] - 2018-9-5

### Added
* Add Support for New User Settings View
* Add theme colors for Breadcrumb

## [0.0.18] - 2018-7-6

### Added
* Add Theme Support for Grid editor layout

## [0.0.16 & 0.0.17] - 2018-6-4

### Changed
* Updated Readme with Recommended Settings
* Add Recommended Extensions for Theme to Readme
* Cleaned up Readme

## [0.0.15] - 2018-5-10

### Changed
* Updated Diff View
* Changed, Updated, and Added Overview Ruler Colors
* Added Git Merge Conflict Colors
* Update Border Colors

## [0.0.14] - 2018-5-4

### Changed
* Added indent highlighting

## [0.0.13] - 2018-4-5

### Changed
* Updated colors for search
* Added colors for notifications

## [0.0.12] - 2018-1-29

### Changed
* Closed 3 Issues on github.
* Changed git ingored resource color
* Changed whitespace foreground color
* Fixed search match highlight color
* Updated recommended settings README

## [0.0.11] - 2017-12-18

### Changed
* Add Ruler

## [0.0.10] - 2017-11-18

### Changed
* Fixed text color in JSX

## [0.0.9] - 2017-11-18

### Changed
* Better support for .scss

## [0.0.8] - 2017-11-18

### Changed
* Change color for this in JS

## [0.0.7] - 2017-11-18

### Changed
* Cleaned up theme JSON

## [0.0.6] - 2017-11-15

### Changed
* Update Extension Icon

## [0.0.5] - 2017-11-15

### Added
* VS Code app icons to match theme (located in images)
* Added links to the README to download icons

## [0.0.4] - 2017-11-8

### Added
* Git status in File Explorer colors

### Changed
* Updated "Recommended Settings" in README for git status styles

## [0.0.1]
* Initial release
