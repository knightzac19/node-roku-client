# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [3.3.7](https://github.com/bschlenk/node-roku-client/compare/v3.3.6...v3.3.7) (2020-05-07)

### [3.3.6](https://github.com/bschlenk/node-roku-client/compare/v3.3.5...v3.3.6) (2020-05-07)

### [3.3.5](https://github.com/bschlenk/node-roku-client/compare/v3.3.4...v3.3.5) (2020-05-07)

### [3.3.4](https://github.com/bschlenk/node-roku-client/compare/v3.3.3...v3.3.4) (2020-05-07)

### [3.3.3](https://github.com/bschlenk/node-roku-client/compare/v3.3.2...v3.3.3) (2020-05-07)

### [3.3.2](https://github.com/bschlenk/node-roku-client/compare/v3.3.1...v3.3.2) (2020-05-07)

### [3.3.1](https://github.com/bschlenk/node-roku-client/compare/v3.3.0...v3.3.1) (2020-05-07)

## [3.3.0](https://github.com/bschlenk/node-roku-client/compare/v3.2.0...v3.3.0) (2020-05-07)


### Features

* added media player ([235b291](https://github.com/bschlenk/node-roku-client/commit/235b291fce018ae935e71201aba1412a41491cf3))

## [3.2.0](https://github.com/bschlenk/node-roku-client/compare/v3.1.7...v3.2.0) (2020-01-11)


### Features

* add default port to ip if not given ([e27cd8c](https://github.com/bschlenk/node-roku-client/commit/e27cd8c6b8510db88e63307e1e1d38f1d6a814cf))

### [3.1.6](https://github.com/bschlenk/node-roku-client/compare/v3.1.5...v3.1.6) (2019-08-07)

<a name="3.1.5"></a>
## [3.1.5](https://github.com/bschlenk/node-roku-client/compare/v3.1.4...v3.1.5) (2019-02-05)



<a name="3.1.4"></a>
## [3.1.4](https://github.com/bschlenk/node-roku-client/compare/v3.1.3...v3.1.4) (2019-02-04)



<a name="3.1.3"></a>
## [3.1.3](https://github.com/bschlenk/node-roku-client/compare/v3.1.2...v3.1.3) (2018-11-23)


### Bug Fixes

* **types:** allow KeyCommand types in keypress commands ([c2785f5](https://github.com/bschlenk/node-roku-client/commit/c2785f5))



<a name="3.1.1"></a>
## [3.1.1](https://github.com/bschlenk/node-roku-client/compare/v3.1.0...v3.1.1) (2018-11-23)



<a name="3.1.0"></a>
# [3.1.0](https://github.com/bschlenk/node-roku-client/compare/v3.0.0...v3.1.0) (2018-10-20)


### Features

* add exec method to commander ([3ed3342](https://github.com/bschlenk/node-roku-client/commit/3ed3342))
* add wait method to commander ([c790780](https://github.com/bschlenk/node-roku-client/commit/c790780))



<a name="3.0.0"></a>
# [3.0.0](https://github.com/bschlenk/node-roku-client/compare/v2.1.0...v3.0.0) (2018-10-16)


### Bug Fixes

* **tests:** add types in test ([1c591ae](https://github.com/bschlenk/node-roku-client/commit/1c591ae))


### Features

* remove tmp dependency & modify icon ([cbb5de1](https://github.com/bschlenk/node-roku-client/commit/cbb5de1))
* switch to fetch-ponyfill ([dd9d03a](https://github.com/bschlenk/node-roku-client/commit/dd9d03a))


### BREAKING CHANGES

* Icon method no longer downloads the icon to the tmp
directory, and instead returns an object with the image type, extension,
and fetch response. This will allow this package to be used in node and
the browser.



<a name="2.1.0"></a>
# [2.1.0](https://github.com/bschlenk/node-roku-client/compare/v2.0.1...v2.1.0) (2018-10-16)


### Bug Fixes

* **jest:** ignore index & keys ([dabd8ab](https://github.com/bschlenk/node-roku-client/commit/dabd8ab))


### Features

* add launchDtv method ([7ea4923](https://github.com/bschlenk/node-roku-client/commit/7ea4923))



<a name="2.0.1"></a>
## [2.0.1](https://github.com/bschlenk/node-roku-client/compare/v2.0.0...v2.0.1) (2018-08-14)



<a name="2.0.0"></a>
# [2.0.0](https://github.com/bschlenk/node-roku-client/compare/v1.2.3...v2.0.0) (2018-08-14)


### Features

* Make commander typesafe ([bccf13c](https://github.com/bschlenk/node-roku-client/commit/bccf13c))
* Split discover into discoverAll ([bd33c68](https://github.com/bschlenk/node-roku-client/commit/bd33c68))
* Update to typescript ([dea9a61](https://github.com/bschlenk/node-roku-client/commit/dea9a61))


### BREAKING CHANGES

* Removed the wait flag from discover and instead added a
separate method discoverAll which will wait for the given amount of time
for all devices on the network.
