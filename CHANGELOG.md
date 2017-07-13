#Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]
### Added
- Testing on Ruby 2.3.0 & 2.4.1

## [1.0.0] - 2016-06-13
### Added
- add long options for commands to improve readability
- add descriptions to commands
- parameter for port
- parameter to disable use of TLS encryption
- added Ruby 2.3.0 to test matrix

### Removed
- removed support for Ruby < 2.0.0

### Changed
- change default call to check via TLS on port 993
- upgrade RuboCop to 0.40, clean up code accordingly

## [0.0.2] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## 0.0.1 - 2015-06-27
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-imap/compare/1.0.0...HEAD
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-imap/compare/0.0.2...1.0.0
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-imap/compare/0.0.1...0.0.2
