# Changelog

## [2.2.0](https://github.com/npm/agent/compare/v2.1.1...v2.2.0) (2023-10-02)

### Features

* [`e24eb6c`](https://github.com/npm/agent/commit/e24eb6c042424e6a83d5fb37a7ff91f7daf6f6f2) [#59](https://github.com/npm/agent/pull/59) use agent-base (@lukekarrys)

### Bug Fixes

* [`d2608ea`](https://github.com/npm/agent/commit/d2608ea5ed6bf973a316c128ecf77601e4254f3e) [#59](https://github.com/npm/agent/pull/59) remove unnecessary utils and cleanup destructuring (@lukekarrys)
* [`4d4b70c`](https://github.com/npm/agent/commit/4d4b70c2a99011909b8f3b58f1e23fcb45cf2ff2) [#67](https://github.com/npm/agent/pull/67) set proxy from env vars based on truthiness (@lukekarrys)

## [2.1.1](https://github.com/npm/agent/compare/v2.1.0...v2.1.1) (2023-09-08)

### Bug Fixes

* [`9937e66`](https://github.com/npm/agent/commit/9937e6602d8448f65f05e17b4d5c2264caeae25e) [#55](https://github.com/npm/agent/pull/55) use current agent to determine secure proxy (@lukekarrys)

## [2.1.0](https://github.com/npm/agent/compare/v2.0.0...v2.1.0) (2023-08-30)

### Features

* [`707bff4`](https://github.com/npm/agent/commit/707bff49da5838c3c803e91c66c4959bc7672a45) [#50](https://github.com/npm/agent/pull/50) use third party proxy agents (@lukekarrys)

## [2.0.0](https://github.com/npm/agent/compare/v1.1.0...v2.0.0) (2023-08-15)

### ⚠️ BREAKING CHANGES

* support for node 14 has been removed

### Bug Fixes

* [`c18b8b3`](https://github.com/npm/agent/commit/c18b8b395faee9e0be78c29bca0d4e85be2424cd) [#47](https://github.com/npm/agent/pull/47) drop node14 support (@lukekarrys)
* [`5c59b3d`](https://github.com/npm/agent/commit/5c59b3df2a86b5ef3debab4c589ebf95f82f1259) [#47](https://github.com/npm/agent/pull/47) use lru-cache named export (@lukekarrys)

### Dependencies

* [`6a72624`](https://github.com/npm/agent/commit/6a72624a419a6aa75167d1c171fcde7cf5677e49) [#47](https://github.com/npm/agent/pull/47) bump lru-cache from 7.18.3 to 10.0.1

## [1.1.0](https://github.com/npm/agent/compare/v1.0.0...v1.1.0) (2023-05-16)

### Features

* [`93bdc11`](https://github.com/npm/agent/commit/93bdc118b3f0b3e627061f7c049aabf066741d8c) [#38](https://github.com/npm/agent/pull/38) implement getAgent function (#38) (@nlf)
* [`35bad06`](https://github.com/npm/agent/commit/35bad06f7bd8f6d3a69cd8e7d6ab7100b2ab2c5e) [#37](https://github.com/npm/agent/pull/37) implement socks proxy (#37) (@nlf)
* [`471f70b`](https://github.com/npm/agent/commit/471f70bed388ce8bbe2154bfc2e749fb55bfbc84) [#35](https://github.com/npm/agent/pull/35) implement the family flag for restricting tcp family (#35) (@nlf)
* [`ac89410`](https://github.com/npm/agent/commit/ac89410bd8b79b130b16c428ec5b2aa2a751c57f) [#34](https://github.com/npm/agent/pull/34) implement dns cache (#34) (@nlf)
* [`1f97e18`](https://github.com/npm/agent/commit/1f97e1800b712d51a0c16b183f64144656db3672) [#30](https://github.com/npm/agent/pull/30) implement granular timeouts (#30) (@nlf)

### Bug Fixes

* [`6eede82`](https://github.com/npm/agent/commit/6eede82b98468172e2f3db2724cc9bce5ae0bd54) [#41](https://github.com/npm/agent/pull/41) pass parameters into errors so we can attach context to them (#41) (@nlf)

### Documentation

* [`00a212a`](https://github.com/npm/agent/commit/00a212a0c3b43652f1331601e53b89b6c1443f11) [#42](https://github.com/npm/agent/pull/42) add a README (#42) (@nlf)

## [1.0.0](https://github.com/npm/agent/compare/v0.0.1...v1.0.0) (2022-12-08)

### ⚠️ BREAKING CHANGES

* `@npmcli/agent` is now compatible with the following semver range for node: `^14.17.0 || ^16.13.0 || >=18.0.0`

### Features

* [`0c17ff4`](https://github.com/npm/agent/commit/0c17ff4730d838769f883323713c00067a4a314b) [#9](https://github.com/npm/agent/pull/9) postinstall for dependabot template-oss PR (@lukekarrys)
* [`eb1fbfc`](https://github.com/npm/agent/commit/eb1fbfc701725664243d46e0f7b7022bec34b2aa) initial commit (@nlf)

### Bug Fixes

* [`f06b8ea`](https://github.com/npm/agent/commit/f06b8ead5d5ad486cd696b07b93858686e7169f7) dont use an agent for the CONNECT request (@nlf)
