# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

## Unreleased

## 1.1.0 - 2018-03-22

### Added

- Use `roave/security-advisories` package to prevent installing packages with known vulnerabilities
- Add `WP_CACHE_KEY_SALT` constant to allow object cache isolation

### Changed

- Update `rarst/laps` package to next major version (2.0)
- Update all packages, sync `composer.lock`
- Micro-optimisation: replace `dirname( __FILE__ )` with `__DIR__`
- Remove unnecessary parentheses from language constructs (`require`, `require_once`)
- Update README

## 1.0.0 - 2017-08-08

### Added

- added WP-CLI support
- added support for `.env` files via `vlucas/phpdotenv`
- added `.env.example`
- added post create-project command to copy `.env.example` to `.env` and generate WordPress salts with WP-CLI
- added keywords and support (issues) link to package metadata
- added requirement for PHP 7.0 and up
- added requirement for native `gettext` PHP extension
- added Level 2/A: Authoritative class maps autoload optimisation to `composer.json`
- added post create-project command to symlink current default WordPress theme (Twenty Seventeen)

### Changed

- updated README

### Removed

- removed redundant version from package metadata

## 0.1.0 - 2017-08-03

### Added

- added complete set of rules to `.gitignore`
- started tracking `composer.lock`
- added this CHANGELOG

### Changed

- replaced `.gitkeep` files with WP's empty `index.php`
- updated README
