# HISTORY

## Unreleased

## [v0.3.0 - 2019-05-27](https://github.com/se7entyse7en/pydockenv/compare/v0.2.3...v0.3.0)

### Added

- Added possibility to specify the python interpreted to use through the `PYDOCKENV_INTERPRETER` environment variable.
- Added `-y/--yes` flag to `uninstall` command.
- [internal] Added some others integration tests.

### Changed

- Refactored code in order to make it more suitable for being used programmatically as a library.

### Fixed

- Avoided bashism in `pydockenv` binary.
- Fixed installation from source tarball.
- Fixed missing network argument when creating port mapper that was supposed to be added in `v0.2.0` due to the ad-hoc network.

## [v0.2.3 - 2019-05-04](https://github.com/se7entyse7en/pydockenv/compare/v0.2.2...v0.2.3)

### Added

- Added support to python 3.6.
- Added possibility to specify environments' configuration file location using `PYDOCKENV_CONF_FILE_DIR` env var.
- [internal] Added testing with python 3.6.
- [internal] Added some others integraion tests.

### Changed

- [internal] Cleaned `.travis.yml`.

### Fixed

- Fixed removal of key from environments configuration file when an environment is removed.
- Fixed update of environments configuration file that prevents some commands to work.


## [v0.2.2 - 2019-05-03](https://github.com/se7entyse7en/pydockenv/compare/v0.2.1...v0.2.2)

### Fixed

- Fixed bug in `pydockenv` binary that makes it exit from parent when sourced introduced in `v0.2.1`.

## [v0.2.1 - 2019-04-29 [YANKED]](https://github.com/se7entyse7en/pydockenv/compare/v0.2.0...v0.2.1)

### Added

- Exits with status code `1` when called with unsupported shells.
- Added printing of environment variables when running `pydockenv` if `PYDOCKENV_DEBUG` is set.
- [documentation] Added `Development` section in `README.md`.
- [internal] Added some integration tests.
- [internal] Added CI on travis.

### Fixed

- Fixed exit code of `pydockenv`.
- [documentation] Fixed images url in `README.md` by using absolute urls.

## [v0.2.0 - 2019-04-01](https://github.com/se7entyse7en/pydockenv/compare/v0.1.0...v0.2.0)

### Added

- Marked with `*` the active environment when listing.
- Change `PS1` when activating and deactivating environment.
- Added an ad-hoc network for each environment.
- [internal] Added `publish-test` Makefile target.
- [internal] Added publishing of git tag when publishing.

### Changed

- [documentation] Updated `README.md` by adding some documentation and examples.
- [internal] Changed bumpversion to include the release date in `HISTORY.md`.

### Fixed

- [internal] Fixed `.bumpversion.cfg` by making each version a subsection.
- [internal] Fixed description field in `setup.py`.
- [internal] Added missing `twine` dev dependency.


## [v0.1.0 - 2019-04-01](https://github.com/se7entyse7en/pydockenv/compare/958fdb9099a2fa0ce21cb8b9c1836b8a751d8311...v0.1.0)

- First version!
