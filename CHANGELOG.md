# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.1.0]
### Added
- add support for Parrot OS (thanks @qdii), fixes #85
### Fixed
- fix bookworm /etc/default/locale target

## [4.0.2]
### Added
- add initial tests (#82)
### Fixed
- fix default_file on Debian Bookworm (#82)

## [4.0.1]
### Fixed
- fix $default_file definition on Ubuntu > 24.04 and Debian < 13 (#80)

## [4.0.0]
### Added
- Add support for Pop!_OS (#75)
- Add support for Debian >12 and Ubuntu >=24.04 (#77, #78)
### Changed
- BREAKING CHANGE: Drop Puppet 6 support (#76)

## [3.2.0]
### Fixed
- Add support for Linuxmint with Puppet 7 (#65)
### Added
- Add Puppet 8 support (#72)
- Add LICENSE file (#73)
- Add support for Sangoma (#67)

## [3.1.1]
### Fixed
- Fix warning on Gentoo systems (#64)

## [3.1.0]
### Added
- Support Rocky linux (#60)

## [3.0.0]
### Added
- Support AlmaLinux (#58)
- Support Puppet 7 (#56)
- Support Raspbian (#55)
- Added types to parameters
- Added `manage_package` parameter (#51)
- Added CHANGELOG.md (only for new releases), fixes #43
### Changed
- BREAKING CHANGE: Testing for Puppet < 6 has been dropped
- Switched from Travis to Github Actions
- Dependencies updated to support the newest releases
- Fixed gentoo config_file path (#50)
- Some linting changes
