# Changelog

## [1.1.0](https://github.com/apoordev/kernel-cache/compare/v1.0.0...v1.1.0) (2024-12-22)


### Features

* add kernel-bazzite to cache ([#29](https://github.com/apoordev/kernel-cache/issues/29)) ([390dd59](https://github.com/apoordev/kernel-cache/commit/390dd59a09012154a1160c3cf3a15fd5344821a3))
* add pull bot config ([2e7b099](https://github.com/apoordev/kernel-cache/commit/2e7b0991afd40a708ac811eecd424f3b216b44a5))
* Add support for fsync-ba, an "LTS" version of the fsync kernel. ([fc01d3e](https://github.com/apoordev/kernel-cache/commit/fc01d3eddffe7115b7e18027493b571a163caf53))
* Cache all the kernels. No Akmods Bootstrap ([#5](https://github.com/apoordev/kernel-cache/issues/5)) ([83fa7e7](https://github.com/apoordev/kernel-cache/commit/83fa7e7f92b9912d9ee0cf02ebf59d3056b84ef0))
* **ci:** Add version and kernel release as build tag ([#25](https://github.com/apoordev/kernel-cache/issues/25)) ([fd5909c](https://github.com/apoordev/kernel-cache/commit/fd5909c0012ff6e4facc633b84a84992d263b840))
* enable coreos-stable on F41 ([#39](https://github.com/apoordev/kernel-cache/issues/39)) ([89d9c6c](https://github.com/apoordev/kernel-cache/commit/89d9c6cf1985af06709d00bb9c70544bc76f8019))
* enable Fedora 41 builds ([#27](https://github.com/apoordev/kernel-cache/issues/27)) ([a768ce0](https://github.com/apoordev/kernel-cache/commit/a768ce0a789a638f05746dcad46735197597735b))
* initial implementation ([45ecfc7](https://github.com/apoordev/kernel-cache/commit/45ecfc7d8418d7decc5b17da4f37ac6af16a02fd))
* kernel signing cache kernels ([#9](https://github.com/apoordev/kernel-cache/issues/9)) ([425026e](https://github.com/apoordev/kernel-cache/commit/425026e978ad379940d5417c80bb5cc8b2ec8f03))


### Bug Fixes

* add x86 to bazzite kernel version check ([#35](https://github.com/apoordev/kernel-cache/issues/35)) ([87cd090](https://github.com/apoordev/kernel-cache/commit/87cd090422d9cb54966ef205bb4b4d37c5b23c08))
* **ci:** version sort copr provided kernels ([#22](https://github.com/apoordev/kernel-cache/issues/22)) ([c535a68](https://github.com/apoordev/kernel-cache/commit/c535a6808b9c06261cbe563f29a23bd0ab873d4b))
* correct invalid variable use on image version label ([#10](https://github.com/apoordev/kernel-cache/issues/10)) ([a1018ec](https://github.com/apoordev/kernel-cache/commit/a1018ecf85a991339cecda2044ee1fb544bb5403))
* correct repo url ([45ecfc7](https://github.com/apoordev/kernel-cache/commit/45ecfc7d8418d7decc5b17da4f37ac6af16a02fd))
* correct tag generation ([45ecfc7](https://github.com/apoordev/kernel-cache/commit/45ecfc7d8418d7decc5b17da4f37ac6af16a02fd))
* correct url ([45ecfc7](https://github.com/apoordev/kernel-cache/commit/45ecfc7d8418d7decc5b17da4f37ac6af16a02fd))
* cron ([45ecfc7](https://github.com/apoordev/kernel-cache/commit/45ecfc7d8418d7decc5b17da4f37ac6af16a02fd))
* don't try to pull scratch ([45ecfc7](https://github.com/apoordev/kernel-cache/commit/45ecfc7d8418d7decc5b17da4f37ac6af16a02fd))
* fix tag ([45ecfc7](https://github.com/apoordev/kernel-cache/commit/45ecfc7d8418d7decc5b17da4f37ac6af16a02fd))
* only use test keys for PR builds ([#19](https://github.com/apoordev/kernel-cache/issues/19)) ([ae4d5b3](https://github.com/apoordev/kernel-cache/commit/ae4d5b340499b793aa34e892f65ae16cb8a7aaee))
* ostree.linux label should not be quoted ([#14](https://github.com/apoordev/kernel-cache/issues/14)) ([78555fe](https://github.com/apoordev/kernel-cache/commit/78555feb55ef9b5576b84b12d00d44e0fcbfe32d))
* pull main kernel version from base-atomic ([#46](https://github.com/apoordev/kernel-cache/issues/46)) ([1e906bb](https://github.com/apoordev/kernel-cache/commit/1e906bb29bf17bdc074e2ae0c9015844c6e294ce))
* remove F39 builds ([#41](https://github.com/apoordev/kernel-cache/issues/41)) ([9638ec7](https://github.com/apoordev/kernel-cache/commit/9638ec7067922ed407c2775a4e911502132bb72b))
* signing key must be used on 'schedule' events ([#15](https://github.com/apoordev/kernel-cache/issues/15)) ([941e10e](https://github.com/apoordev/kernel-cache/commit/941e10e8a35a1199a94796769f00a8444f248411))
* spelling ([45ecfc7](https://github.com/apoordev/kernel-cache/commit/45ecfc7d8418d7decc5b17da4f37ac6af16a02fd))
* switch to ostree-desktop base ([45ecfc7](https://github.com/apoordev/kernel-cache/commit/45ecfc7d8418d7decc5b17da4f37ac6af16a02fd))
* unpin coreos kernel ([#42](https://github.com/apoordev/kernel-cache/issues/42)) ([295e5e6](https://github.com/apoordev/kernel-cache/commit/295e5e69316dcbc79e34c1b189cbfe134db1aea8))

## 1.0.0 (2024-06-30)


### Features

* initial implementation ([45ecfc7](https://github.com/ublue-os/fsync/commit/45ecfc7d8418d7decc5b17da4f37ac6af16a02fd))
