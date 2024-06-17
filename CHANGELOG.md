# tap2junit changelog

## [0.2.0](https://github.com/MoLow/tap2junit/compare/v0.1.6...v0.2.0) (2024-06-17)


### Features

* add missing release-please files ([efaf634](https://github.com/MoLow/tap2junit/commit/efaf634126c82edb551b89391a86a9bf8d56dca5))


### Bug Fixes

* explicitly encode input file with utf-8 ([#45](https://github.com/MoLow/tap2junit/issues/45)) ([3527392](https://github.com/MoLow/tap2junit/commit/35273928126f59b125fe86540076ebf542712784))

### 0.1.6
* Support for parsing YAML blocks
* Add option to override test suite name
* Add support for TAP version 12
* Support TAP with nested tests
* Fix duration_ms to be milliseconds instead of seconds
* Explicitly encode input file as utf-8
* Use GitHub Actions for ci testing
* Replace Python linting tools with Ruff
* Add pypa/hatch for building and publishing

### 0.1.5
* Add support for Python 3
* Add automated testing on Travis CI
* Remove Pipfile.lock to support multiple Python versions
