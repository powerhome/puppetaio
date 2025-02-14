# Changelog
Please document all notable changes to this project in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## Unreleased

## v3.1.0
### Fixed
- Configure choria allow_unconfigured because default changed in choria-plugins/action-policy 3.1.0

## v3.0.2
### Fixed
- Fix openssl dependency in ruby request-cert scripts

## v3.0.1
### Changed
- puppetserver and puppetdb Dockerfile can now build other versions via build-args
- Update r10k components to current versions
- Update nats components, add nats to gitlab-ci
- Update README

### Added
- gitlab-ci config to build and push to dockerhub
- gitlab-ci config for haproxy
- gitlab-ci for postgres build

### Removed
- Support for legacy PuppetDB API
- Puppet 4 Server Dockerfile
- Remains of Puppet 3.8 and more legacy API

## v2.4.0
### Added
- manage maximum-pool-size setting, default value 25

### Changed
- Update PuppetDB from 5.1.3 to 5.1.5

## v2.3.1
### Fixed
- Fix gettext-setup issue, puppetlabs/SERVER-1912

## v2.3.0
### Added
- Implement certificate-whitelist for PuppetDB

## v2.2.0
### Fixed
- Incompatible versions of mcoclient and r10k choria plugin

### Added
- r10k cli rpc agent for mco

## v2.1.0
### Added
- Make CA CN and TTL configurable

## v2.0.0 - 2018-02-05
### Changed
- Removed deprecated PuppetDB settings
- Removed Puppet 3.8

### Added
- Make PuppetDB node-ttl configurable
- Add Dockerfile for Puppet4 with PuppetDB5

## v1.2.0 - 2018-01-04
### Added
- Updated all components to Puppet 5
- Environment variable to configure number of JRuby instances of puppetserver

## v1.0.0 - 2017-07-03
### Added
- Initial releas
