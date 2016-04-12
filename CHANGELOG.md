# Change log

## Version 0.2.5 (Apr 12, 2016)

New features:
  * Integrated with Uber deployment project to manage Uber environment in a long run

Bug fixes:
  * Setup the correct download path for Ruby and OpenSSL

Minor enhancements:
  * Changed DEPLOY_USER, UBER_ENV and UBER_STAGE to become system options instead of custom options
  * Renamed LUBAN_INSTALL_PATH to LUBAN_ROOT_PATH to be consistent with naming in Ruby gem Luban
  * Updated simple and complete Genesis config files


## Version 0.2.1 (Apr 11, 2016)

Minor enhancements:
  * Added Luban downloads path to store downloaded third-party source packages if any
  * Install OpenSSL before instead of inside Ruby installation
  * Fixed a few minor typos

## Version 0.2.0 (Apr 01, 2016)

Minor enhancements:
  * Removed support for YAML installation because Ruby has bundled YAML since version 2.1.2
  * Bundled OpenSSL when setup Ruby

## Version 0.1.1 (May 26, 2015)

Minor enhancements:
  * Add bootstrap script to simplify the overall Genesis setup

## Version 0.1.0 (May 26, 2015)

New features:
  * Initialize Genesis
  * Bootstrap Genesis environment
  * Setup Ruby
    * Setup YAML
    * Setup gem Bundler
