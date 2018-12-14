# Changelog
All notable changes to Agastya will be documented in this file. These include changes to both plugins and major APIs.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## 3.8.0 - 2018-12-14
### Added
- Built-in support for UTM parameters for tracking

## 3.7.2 - 2018-12-01
### Changed
- Migrate database from InfluxDB to ElasticSearch
- Change infinite limit to 24-hour to geolocation caching
- Update tracking endpoint to `agastya-secure-tracker`

## 3.7.1 - 2018-11-26
### Changed
- Update "Do not track" link to new usage guidelines

## 3.7.0 - 2018-11-10
### Added
- Switch between accessibility and chat icons when live chat is enabled
- Add built-in usage guidelines
### Changed
- List user inteface for advanced options

## 3.6.0 - 2018-11-05
### Added
- Introducing support for Drift live chat
### Fixed
- Fixed iOS Safari iframe scrolling bug

## 3.5.3 - 2018-08-27
### Changed
- Force black color for active read aloud text

## 3.5.2 - 2018-08-26
### Added
- Added link to Oswald Labs' accessibility policy
### Fixed
- Fixed rounded corners for the plugin (force border-radius)

## 3.5.1 - 2018-08-01
### Changed
- Link to learn how to turn Do Not Track on migrated to Oswald Labs Help website
- Preload "loading" image for faster-feeling UX on clicking the Agastya button
- Better read aloud panel design for mobile devices

## 3.5.0 - 2018-07-30
### Added
- Caching of user agent information and geolocation, so tracking after the first event will be much faster.
### Changed
- Tracking endpoint changed after migrating from MariaDB to InfluxDB.

## 3.4.0 - 2018-07-30
### Fixed
- In dyslexia-friendly mode, `<i>`'s font is inherited instead of being overwritten (for icon fonts.)
### Added
- Link to "Learn how to enable" under Do Not Track on the settings page.

## 3.3.0 - 2018-07-19
### Added
- Built-in plugin support for 50+ more languages with auto-detection.
- Native + fallback notifications to tell users when something is going on in the background.
### Changed
- Instead of redirecting to form for GDPR requests, export and delete are added as part of plugin window.

## 3.2.0 - 2018-07-15
### Added
- Brand new universal read aloud. [Learn more](https://blog.oswald.foundation/introducing-universal-screen-reader-on-agastya-827e88a67ce).

## 3.1.0 - 2018-06-30
### Added
- New Agastya JavaScript client API for developers using `window.agastya.api()`

## 3.0.1 - 2018-06-26
### Changed
- Make plugin window smaller on mobile to reflect changes on the website in background.

## [3.0.0](https://blog.oswald.foundation/introducing-the-new-agastya-privacy-first-and-universal-9a67ef66cb19) - 2018-06-09
### Added
- Built-in support for multiple languages with auto-detection.
- CSS class modes like dyslexia-friendly mode and night mode now support custom classes.
- Option to change the primary color (header, button, etc.) for the plugin.
- EU support for GDPR and cookie law.
### Changed
- Brand new user interface for the plugin window.
- Better support for single-page apps and progressive web apps.
