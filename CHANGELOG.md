# Changelog

## [Unreleased]

## [1.4.0] - 2020-07-22
### Changed
- [browser/node] `notify` now includes the `url` property on the returned
                 `INotice` object
                 ([#780](https://github.com/airbrake/airbrake-js/pull/780))

## [1.3.0] - 2020-06-19
### Changed
- [browser/node] Deprecate `keysBlacklist` in favor of `keysBlocklist`

## [1.2.0] - 2020-05-29
### Added
- [node] New method to filter performance metrics
         ([#726](https://github.com/airbrake/airbrake-js/pull/726))

## [1.1.3] - 2020-05-26
### Changed
- [browser/node] Remove onUnhandledrejection parameter type

## [1.1.2] - 2020-05-05
### Fixed
- [browser] Add guard for window being undefined
            ([#684](https://github.com/airbrake/airbrake-js/pull/684))
- [node] Report URL using `req.originalUrl` instead of `req.path` in Express
         apps ([#691](https://github.com/airbrake/airbrake-js/pull/691))

## [1.1.1] - 2020-04-28
### Fixed
- [node] Express route stat reporting
         ([#671](https://github.com/airbrake/airbrake-js/pull/671))

## [1.1.0] - 2020-04-22
### Changed
- [browser/node] Build process updates. Bumping minor version for this. See
                 [#646](https://github.com/airbrake/airbrake-js/pull/646)
- [browser/node] Documentation updates

## [1.0.7] - 2020-04-08
### Added
- [node] New config option to disable performance stats

### Changed
- [browser/node] Build config updates
- [browser/node] Update dependencies
- [browser/node] Documentation updates
- [browser/node] Update linting config

### Fixed
- [browser] Fix stacktrace test for node v10
- [browser/node] Fix linting errors

## [1.0.6] - 2019-11-18

## [1.0.4] - 2019-11-12

## [1.0.3] - 2019-11-07

## [1.0.2] - 2019-10-28

## [1.0.1] - 2019-10-28

## [1.0.0] - 2019-10-21

[Unreleased]: https://github.com/airbrake/airbrake-js/compare/v1.4.0...master
[1.4.0]: https://github.com/airbrake/airbrake-js/releases/tag/v1.4.0
[1.3.0]: https://github.com/airbrake/airbrake-js/releases/tag/v1.3.0
[1.2.0]: https://github.com/airbrake/airbrake-js/releases/tag/v1.2.0
[1.1.3]: https://github.com/airbrake/airbrake-js/releases/tag/v1.1.3
[1.1.2]: https://github.com/airbrake/airbrake-js/releases/tag/v1.1.2
[1.1.1]: https://github.com/airbrake/airbrake-js/releases/tag/v1.1.1
[1.1.0]: https://github.com/airbrake/airbrake-js/releases/tag/v1.1.0
[1.0.7]: https://github.com/airbrake/airbrake-js/releases/tag/v1.0.7
[1.0.6]: https://github.com/airbrake/airbrake-js/releases/tag/v1.0.6
[1.0.4]: https://github.com/airbrake/airbrake-js/releases/tag/v1.0.4
[1.0.3]: https://github.com/airbrake/airbrake-js/releases/tag/v1.0.3
[1.0.2]: https://github.com/airbrake/airbrake-js/releases/tag/v1.0.2
[1.0.1]: https://github.com/airbrake/airbrake-js/releases/tag/v1.0.1
[1.0.0]: https://github.com/airbrake/airbrake-js/releases/tag/v1.0.0
