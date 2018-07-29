# Changelog
All notable changes to Agastya will be documented in this file. These include changes to both plugins and major APIs.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## 2018-07-30
### Added
- Caching of user agent information and geolocation, so tracking after the first event will be much faster.
### Changed
- Tracking endpoint changed after migrating from MariaDB to InfluxDB.

## 2018-07-30
### Fixed
- In dyslexia-friendly mode, `<i>`'s font is inherited instead of being overwritten (for icon fonts.)
### Added
- Link to "Learn how to enable" under Do Not Track on the settings page.
