# habitat CHANGELOG

This file is used to list changes made in each version of the habitat cookbook.

<!-- latest_release unreleased -->
## Unreleased

<!-- latest_release -->

## 0.67.0 (2018-11-01)

- Update README with accurate maintainer info
- bug fixes for windows on newer chef versions and path seperators
- Update to habitat 0.67.0 (#146)

## 0.63.0 (2018-09-18)

*  Update to habitat 0.63.0


## 0.62.1 (2018-09-07)

* Update hab version to 0.62.1 and pin supervisor version to 8380
* Refactor cookbook resources for 0.62.1 compatibility
* Add user_toml resource
* Add remote supervisor support
* Add multiple peer support
* Add auth token support to package resource
* Add basic support for Windows

#### Merged Pull Requests
- Refactor hab_service resource [#124](https://github.com/chef-cookbooks/habitat/pull/124) ([wduncanfraser](https://github.com/wduncanfraser))
- Update to 0.62.1 and launcher 8380 [#129](https://github.com/chef-cookbooks/habitat/pull/129) ([jonlives](https://github.com/jonlives))
- Added auth token support to package resource [#125](https://github.com/chef-cookbooks/habitat/pull/125) ([wduncanfraser](https://github.com/wduncanfraser))
- Updated Supervisor Resource for 0.56 and to Support Auth Token [#123](https://github.com/chef-cookbooks/habitat/pull/123) ([wduncanfraser](https://github.com/wduncanfraser))
- Added user-toml resource [#121](https://github.com/chef-cookbooks/habitat/pull/121) ([wduncanfraser](https://github.com/wduncanfraser))
- Change expeditor notification channel [#128](https://github.com/chef-cookbooks/habitat/pull/128) ([mivok](https://github.com/mivok))
- adding supervisor and service multiple peering support [#101](https://github.com/chef-cookbooks/habitat/pull/101) ([jkerry](https://github.com/jkerry))
- Basic support for windows platform [#89](https://github.com/chef-cookbooks/habitat/pull/89) ([skylerto](https://github.com/skylerto))
- Allow any channel in a service [#120](https://github.com/chef-cookbooks/habitat/pull/120) ([jsirex](https://github.com/jsirex))
- fix hashbang in expeditor update script [#118](https://github.com/chef-cookbooks/habitat/pull/118) ([joshbrand](https://github.com/joshbrand))

## Unreleased

## 0.59.0 (2018-07-17)

- Update README to reflect new version of Hab
- address chef 14.3.x shell_out deprecations
- fix shell_out_compact deprecation
- move to after tempfile creation
- Update CHANGELOG.md with details from pull request #111
- Use the new kitchen config file names
- Cookstyle fixes

#### Merged Pull Requests
- address chef 14.3.x shell_out deprecations [#111](https://github.com/chef-cookbooks/habitat/pull/111) ([lamont-granquist](https://github.com/lamont-granquist))

## 0.57.0 (2018-06-19)

- Fix #103
- Add @jonlives as a maintainer
- Source helper functions script

#### Merged Pull Requests
- Source helper functions script [#105](https://github.com/chef-cookbooks/habitat/pull/105) ([jtimberman](https://github.com/jtimberman))
- Fix #103 and remove options from svc start [#104](https://github.com/chef-cookbooks/habitat/pull/104) ([jonlives](https://github.com/jonlives))

## 0.56.1 (2018-06-06)

- Support passing TMPDIR attribute to Habitat install.sh script.  Addresses Issue #90
- Add: bldr_url property for hab_sup
- Fix hab_svc when using custom ip:port for supervisor
- Include toml in the bundle
- Update CHANGELOG.md with details from pull request #96

#### Merged Pull Requests

- Fix hab_svc when using custom ip:port for supervisor [#96](https://github.com/chef-cookbooks/habitat/pull/96) ([JonathanTron](https://github.com/JonathanTron))
- Add: bldr_url property for hab_sup [#93](https://github.com/chef-cookbooks/habitat/pull/93) ([Atalanta](https://github.com/Atalanta))
- Support passing TMPDIR attribute to Habitat install.sh script.  #90 [#91](https://github.com/chef-cookbooks/habitat/pull/91) ([qubitrenegade](https://github.com/qubitrenegade))
- Include toml in the bundle [#100](https://github.com/chef-cookbooks/habitat/pull/100) ([jtimberman](https://github.com/jtimberman))

## 0.56.0 (2018-06-05)

- Update for 0.56.0
- Cookstyle fix
- Disable FC113 for now
- Update the platforms we test
- Update CHANGELOG.md with details from pull request #97

## 0.55.0 (2018-03-22)

- Adding ability to use local repos
- Add expeditor configuration
- update for 0.55.0

## 0.54.0 (2018-02-22)

- Add auto_update property to hab_sup resource.
- update for 0.54.0 release

## 0.53.0 (2018-02-07)

- Set supervisor service to enable
- Remove the legacy version property
- Update copyrights and format
- Test on the latest Fedora
- Remove the suite from dokken.
- Move installation into config and package
- Use a non-deprecated Fauxhai mock
- Remove author info from the test recipe
- Remove the install test recipe
- Remove the ChefSpec matchers
- Make sure package and curl are installed in the install resource
- Add Debian 7+ to the readme as supported
- Allow nameless hab_install resource
- Turns out we don't even need to install before installing the sup
- Update the hab_install readme examples
- update to habitat 0.53.0

## 0.52.0 (2018-01-23)

- Remove Debian 7 testing
- Remove stove gem that's in ChefDK now
- Align Chef in readme with Chef in metadata
- Format readme markdown
- Remove implementation detail
- Actions are symbols so document them that way
- Remove reference to old Hab since we require the latest now
- update to habitat 0.52.0

## 0.51.0 (2018-01-08)

- Update for Habitat version 0.51.0

## 0.50.3 (2017-12-04)

- Update for Habitat version 0.50.3

## 0.40.0 (2017-11-30)

- Update for Habitat version 0.40.0

## 0.39.2 (2017-11-28)

- Add Supervisor service support for non-Systemd platforms

Development environment/CI changes:

- need to install toml gem for travis
- Ignore failure when installing from acceptance

## 0.39.1 (2017-11-27)

- update for 0.39.1
- fix rubocop findings too

## 0.39.0 (2017-11-17)

- Install version 0.39.0
- Defer running check to a predicate method in service resource

## 0.38.0 (2017-10-30)

- update version to install for habitat 0.38.0

## 0.37.1 (2017-10-26)

- create user in `hab_install`

## 0.37.0 (2017-10-19)

- update for habitat 0.37.0 release

## 0.36.0 (2017-10-09)

- Simplify `Chef::Provider::Package::Hart#current_versions`.
- honor options from package provider
- update for habitat 0.36.0

## 0.34.3 (2017-10-06)

- Clarify in the README about action-specific properties

## 0.34.2 (2017-10-06)

- Add `hab_config` resource
- Add `toml` gem to metadata for older versions of Chef that don't have it
- Require Chef 12.20.3 or higher to make use of helper methods and classes in newer versions of Chef

## 0.34.1 (2017-10-04)

- Add `version_compare` method to work with latest Chef

## 0.34.0 (2017-10-03)

- Update `hab_install` to Habitat version 0.34.1

## 0.33.0 (2017-09-25)

**Breaking change**

This version is a compatibility change. All users of this cookbook must upgrade the cookbook to use current versions of Habitat.

- Fix to account for [habitat-sh/habitat#3239](https://github.com/habitat-sh/habitat/pull/3239) - do not provide `/v1/depot` to Depot URL.
- Pin the version of this cookbook along with the version of Habitat we install. This should match minor, but not necessarily patch versions.

## 0.28.0 (2017-09-19)

- Add channel support to sup load/start

## 0.27.0 (2017-09-11)

- Add hab_version and hab_channel to the sup service
- Support multiple binds with hab_service

## 0.26.1 (2017-07-21)

- `hab_package` now properly selects latest version from the specified channel.

## 0.26.0 (2017-07-17)

### Breaking Changes

This cookbook was updated to be compatible with the changes made in Habitat 0.26. With these updates the cookbook now requires Habitat 0.26 or later. The version has been updated to match that of habitat. In the event of future breaking habitat changes the version of this cookbook will be updated to reflect the new minimum habitat release.
  - The cookbook now correctly parses the process status returned by the hab sup services endpoint
  - Packages now pull from the 'stable' channel by default. If you need to pull from another channel there is a new 'channel' property in the package resource that accepts a string.

### Other Changes
  - Resolves deprecation warnings introduced in Chef 13.2
  - Removed references in the readme to Chefstyle and simplified some of the requirements information
  - Added maintainer information to the readme and removed the maintainers file

## v0.4.0 (2017-04-26)

- Backwards incompatible version, requires habitat 0.20 or higher
- Add `hab_sup` resource for managing Habitat supervisor. See readme for usage.
- Rewrite `hab_service` resource to manage services in Habitat supervisor

## v0.3.0 (2017-02-21)

- Add property for ExecStart options. See readme for usage
- Add property for depot_url. See readme for usage
- Added restart action to the resource

## v0.2.0 (2016-11-30)

- Added `version` and `channel` properties to install resource
- Added `depot_url` property to hab_package resource

## v0.1.1 (2016-11-10)

- Removed Chef 11 compatibility in the metadata
- Resolved Chefstyle warnings
- Resolved foodcritic warnings
- Added a chefignore file
- Updated the gitignore file
- Improve the readme format and add badges
- Update all test deps to current
- Remove the apt testing dependency
- Add integration testing in Travis using kitchen-dokken

## v0.1.0 (2016-11-08)

- add `hab_service` resource
- make the `hab_package` resource convergent
- add chefspec and inspec tests
- better documentation through README updates

## v0.0.3 (2016-07-14)

- Initial release, includes `hab_package` and `hab_install` resources