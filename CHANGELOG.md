Change Log
==========

All notable changes to this project will be documented in this file, which
follows the conventions of [keepachangelog.com](http://keepachangelog.com/).
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

...


## [0.10.0] - 2019-03-26

### Changed
- Update BouncyCastle to 1.61.
  [#18](//github.com/greglook/clj-pgp/pull/18)

### Added
- A new `clj-pgp.message/reduce-messages` function allows for consuming
  encrypted data without buffering the entire message in memory. This makes it
  possible to handle very large messages in a streaming fashion.
  [#19](//github.com/greglook/clj-pgp/pull/19)


## [0.9.0] - 2017-11-04

### Changed
- Make private and public keyrings encodable.
- Simplify fuzzing tool.
- Improve coverage generation.


## [0.8.3] - 2015-12-30

Start of CHANGELOG.

[Unreleased]: https://github.com/greglook/clj-pgp/compare/0.10.0...HEAD
[0.10.0]: https://github.com/greglook/clj-pgp/compare/0.9.0...0.10.0
[0.9.0]: https://github.com/greglook/clj-pgp/compare/0.8.3...0.9.0
[0.8.3]: https://github.com/greglook/clj-pgp/compare/0.8.2...0.8.3
