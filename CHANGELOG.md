# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [21.10] (unreleased)

### Added
- Add mqtt, example, handler for create, modify and get target [4](https://github.com/greenbone/eulabeia/pull/4)
- Add scan, sensor aggregate; extend sensor to register and deregister itself [5](https://github.com/greenbone/eulabeia/pull/5)
### Changed
- Split cmds and info messages into own module [8](https://github.com/greenbone/eulabeia/pull/8)
- Normalized topic structure to `group/aggregate/event/destination`; setting topic based on return message rather than configuration [8](https://github.com/greenbone/eulabeia/pull/8)
- Simplified block until sigterm handling [11](https://github.com/greenbone/eulabeia/pull/11)
### Fixed
### Removed
