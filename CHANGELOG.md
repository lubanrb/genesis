# Change log

## Version 0.4.8 (Jan 09, 2017)

Minor enhancements:
  * Separated package installations by application instead of by project

## Version 0.4.7 (Jan 04, 2017)

Minor enhancements:
  * Relocated packages installation path to luban root

## Version 0.4.6 (Dec 17, 2016)

Minor enhancements:
  * Genesis branch/tag in bootstrap can be specified thru environment variable, GENESIS_TAG
    * For instance, GENESIS_TAG="v0.4.1"
    * By default, GENESIS_TAG is set to "master"
  * Uber branch/tag in bootstrap can be specified thru environment variable, UBER_TAG
    * For instance, UBER_TAG="v0.3.3"
    * By default, UBER_TAG is set to "master"
  * Refactored environment variables setup for bootstrap as a result
  * Added flag, SKIP_PROMPTLESS_AUTHEN, to control if need to setup promptless authentication
  * Supported set Genesis configurations thru environment variables
    * Precedence of Genesis configurations: config file > environment variables > default values
  * Added default path for Luban deployment projects to be /opt/luban/projects
  * Bump up Ruby version to 2.3.3
  * Configured Ruby without Tcl/Tk and static library
  * Configured Ruby with "--enable-shared" to build shared Ruby library
  * Removed static Ruby library manually
  * Updated Genesis configuration exapmles

Bug fixes:
  * Disabled document generation for Rubygems

## Version 0.4.0 (Nov 21, 2016)

New features:
  * Used bundler to manage gem dependencies in Uber

## Version 0.3.6 (Nov 17, 2016)

Minor enhancements:
  * Deprecated Rubygems-update and setup Rubygems directly for Rubygems upgrade
  * Upgraded Ruby to version 2.3.2

## Version 0.3.5 (Nov 01, 2016)

Minor enhancements:
  * Upgraded Rubygems-update to version 2.6.8

## Version 0.3.4 (Oct 31, 2016)

Bug fixes:
  * Corrected AUTHORIZED_KEYS_FILE_PATH checking for its existence

## Version 0.3.3 (Oct 27, 2016)

New features:
  * Used Rubygems-update to ensure Rubygems up-to-date after Ruby installation
  * Setup promptless authentication and cleanup installation for Lubbase in Uber
    * Hence, Lubbase provision could be done directly
    * AUTHEN_KEY_TYPE is added to configure SSH key type

Minor enhancements:
  * bootstrap script in Genesis now can be executed locally
    * This is handy especially when Genesis development

## Version 0.3.2 (Oct 13, 2016)

Minor enhancements:
  * Upgraded OpenSSL to version 1.0.2j
  * Handled download current and old OpenSSL versions properly

## Version 0.3.1 (Sept 26, 2016)

Minor enhancements:
  * Added command line argument to specify the uber stage with default value of "development"

## Version 0.3.0 (May 10, 2016)

Minor enhancements: 
  * Supported gems installation via Gemfile in Uber
  * Changed openssl source download url to ftp site
  * Upgraded Ruby to 2.3.1

## Version 0.2.6 (May 09, 2016)

Minor enhancements:
  * Upgraded OpenSSL to 1.0.2h for Ruby installation

## Version 0.2.5 (Apr 15, 2016)

New features:
  * Integrated with Uber deployment project to manage Uber environment in a long run
  * Added instructions to complete Uber setup

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
