# Esri Rollup Example Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## Unreleased
## v0.1.9
### Support
- bump dependencies, add repo to package.json

## v0.1.9
### Changed
- using Rollup to uglify source and generate sourcemaps
- update to JSAPI 4.0
- update to latest rollup and rollup-plugin-uglify to fix build errors

### Support
- only bundle app, startup app in index, drop main

## v0.1.8

### Changed
- only bundle app, startup app in index, drop main

## v0.1.7

### Added
- added missing `this.inherited(arguments)` to side panel widget

### Support
- Use Rollup's `useStrict: false` option instead of gulp-replace on the bundled output.

## v0.1.6

### Added
- importing capitalize() from ES2015 build of lodash

### Support
- better sourcemaps (not inlined)

## v0.1.5

### Changed
- only include the bootstrap components used by the app

## v0.1.4

### Added
- added chevron icon to collapsing panel and dynamically update (up/down) using jQuery global

### Support
- lint bfore script tasks in live reload

## v0.1.3

### Added
- added bootstrap JS and jquery for collapsing panel

## v0.1.2

### Changed
- copy vendor fonts to dist before serving

## v0.1.1

### Added
added Sass and loading Calcite Bootstrap via Sass

### Changed
- minor tweaks to and comments for gulp tasks
- minor tweaks to README

## v0.1.0

### Added
- added gh-pages deploy
- added gulp build

## v0.0.8

### Changed
- fleshed out README

### Added
- added basemap toggle
- added CHANGELOG

## v0.0.7

### Added
- re-build whenever src changes

## v0.0.6

### Changed
- using JSAPI v4 Beta 3 instead of v3.16
- map service can add layer and manages map state

## v0.0.5

### Added
- added calcite bootstrap and side panel widget

## v0.0.4

### Added
- added linting w/ semistandard

### Added
- added a custom dijit to show current time

## v0.0.3

### Added
- minify bundled output

## v0.0.2

### Changed
- babel actually transpiles

### Added
- added a custom dijit to show current time

## v0.0.1

### Added
- first working rollup build!
