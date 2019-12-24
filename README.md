# Changelog
All notable changes to Agastya will be documented in this file. These include changes to both plugins and major APIs.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## 4.16.1 - 2019-11-01

### Changed
- Get referrer URL when using Platform APIs

## 4.16.0 - 2019-10-20

### Added
- Support for initial Agastya service page setting

## 4.15.0 - 2019-10-17

### Added
- Support for custom button icons

### Changed
- Updated interface for "Get in touch" form

## 4.14.0 - 2019-09-20

### Added
- Support for tracking 5 "basic" custom values

### Changed
- Dialogflow integration now tracks response indent ID

## 4.13.0 - 2019-09-03

### Added
- Support for button size customization

## 4.12.0 - 2019-08-31

### Added
- Support for new Oswald Labs Platform APIs

### Changed
- CDN URL for Agastya app

## 4.11.0 - 2019-08-22

### Added
- Track mouse over on Agastya icon

## 4.10.0 - 2019-08-21

### Added
- Lexend font family in reading font

## 4.9.1 - 2019-08-14

### Changed
- Card open/close tracking in vocabulary helper
- Increased shadow in cards in dyslexia-friendly mode

## 4.9.0 - 2019-08-13

### Added
- Dictionary hover cards in dyslexia-friendly mode

## 4.8.0 - 2019-08-10

### Added
- New typeface available, Inter

## 4.7.2 - 2019-08-09

### Changed
- Updated "Powered by Agastya" text to logo

## 4.7.1 - 2019-08-08

### Changed
- Updated link to information about Do Not Track
- Updated link to details for "What we track"

## 4.7.0 - 2019-08-07

### Added
- Read Aloud language/accent setting
- Translation featured languages setting

## 4.6.0 - 2019-08-06

### Added
- Ignore duplicate tracking requests in 1 second

### Changed
- Use Tracking plugin to track SPA/PWA pageviews

### Removed
- Remove on page change communication in SPA/PWAs

## 4.5.2 - 2019-08-05

### Fixed
- Change ID of Agastya script to prevent collision with v4.4

## 4.5.1 - 2019-08-05

### Fixed
- Fixed bug with Uptime Robot card

## 4.5.0 - 2019-08-05

### Added
- New language-based voices in Read Aloud

### Fixed
- Fixed bug with Read Aloud not working multiple times on the same page

### Changed
- Significantly faster event tracking

## 4.4.0 - 2019-07-30

### Added
- Vocabulary helper mode to highlight difficult words

## 4.3.6 - 2019-07-26

### Fixed
- Internal bug fixes

## 4.3.5 - 2019-07-01

### Changed
- Better internal caching of static files

## 4.3 - 2019-06-28

### Added
- Internal updating utility to Platform APIs

### Fixed
- Fix bug with Do Not Track and battery levels

## 4.2 - 2019-06-24

### Added
- Internal toolkit for faster deployments

### Changed
- Updated deployment process to new servers

## 4.1.3 - 2019-06-13

### Added
- Support for landmark color customization

## 4.1.2 - 2019-06-06

### Changed
- Better local storage for user customizations

## 4.1 - 2019-05-28

### Added
- Support for custom elements

## [4.0](https://blog.oswald.foundation/introducing-agastya-4-augmenta11y-555b536f62df)

### Added

- User customization (fonts, colors, etc.)
- Agastya App Store
- Support for Agastya Admin

### Changed
- Brand new user interface for the plugin window
- More developer-friendly APIs and methods
- Event emitting and promise-based API

## 3.8.2 - 2019-02-13

### Changed
- Better session key (now adds year/month with useragent and hashed IP)

## 3.8.1 - 2018-12-27

### Changed
- Changed session and user agent unique keys
- Better EU detection for cookie law (specific countries not continent)

## 3.8.0 - 2018-12-14

### Added
- Built-in support for UTM parameters for tracking

## 3.7.2 - 2018-12-01

### Changed
- Migrate database from InfluxDB to ElasticSearch
- Change infinite limit to 24-hour for geolocation caching
- Update tracking endpoint to `secure-agastya-tracker`

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
