# Changelog

## [3.8.0](https://github.com/redsift/mailparser/compare/v3.7.1...v3.8.0) (2024-05-13)


### Features

* **events:** Emit a new headerLines event to gain access the raw headers ([#364](https://github.com/redsift/mailparser/issues/364)) ([d33d7ec](https://github.com/redsift/mailparser/commit/d33d7ec4b8e32a4eb7a9a664cec5fdb545c274af))


### Bug Fixes

* :arrow_up: update nodemailer dependency to resolve security issue GHSA-9h6g-pr28-7cqp ([#357](https://github.com/redsift/mailparser/issues/357)) ([8bc4225](https://github.com/redsift/mailparser/commit/8bc42251fca6f538ece599f0a5bebe09b0aeff4f))
* 150 ([919f69a](https://github.com/redsift/mailparser/commit/919f69a49eb1326431c27c7034050498ca504822))
* 272: Throw TypeError for invalid input. ([abd7e43](https://github.com/redsift/mailparser/commit/abd7e43d90e533921c13ed8044a892761ef0535d))
* 34, bump version ([09aa0bd](https://github.com/redsift/mailparser/commit/09aa0bd59c1a70229567ff830adfd44c01605c2f))
* capture decoder end event to use on cleanup ([4e367f7](https://github.com/redsift/mailparser/commit/4e367f7fda2505b9edb8e195eb5b1a8e1d1531fc))
* **deploy:** added auto-deployment ([d6eb56f](https://github.com/redsift/mailparser/commit/d6eb56fe09fe8b415e5bbf2e53704f6788ca0fee))
* **deps:** Bumped deps ([db842ad](https://github.com/redsift/mailparser/commit/db842addd36e2fe94d0c4b466da80719a36f47ac))
* **deps:** Replaced 'punycode' with 'punycode.js' module ([4a15157](https://github.com/redsift/mailparser/commit/4a15157dc9a815aa0e756d9e6ae0e8631842c447))
* error on ks_c_5601-1987 ([89572e0](https://github.com/redsift/mailparser/commit/89572e000d815704378261c753f59442397b8564))
* Fix produced text address list string according to rfc 2822 ([#340](https://github.com/redsift/mailparser/issues/340)) ([6bae600](https://github.com/redsift/mailparser/commit/6bae600a3f4a0452ee7ca43634a11939de7bcc6d))
* handle simpleParser input stream error ([faf9fc5](https://github.com/redsift/mailparser/commit/faf9fc5d8a27c1f88b7a126782d84ce2fef4d4bd))
* **punycode:** Fixes [#355](https://github.com/redsift/mailparser/issues/355) Deprecation warning of the punycode module ([#356](https://github.com/redsift/mailparser/issues/356)) ([0f35330](https://github.com/redsift/mailparser/commit/0f35330c87d715d38e8c853ae6c2f64d098b971d))
* **simple-parser:** Buffer.from(string) default encode is utf-8,when input string‘s encode is gbk,result has some garbled ([633e436](https://github.com/redsift/mailparser/commit/633e4369c93dc5122c8c8bee0fd2b057761e1223))
* **test:** updated test matrix (18, 20, 21) ([a2ba9c2](https://github.com/redsift/mailparser/commit/a2ba9c236dcd7f990c9d53a386ffaa5b564181b3))

## [3.7.1](https://github.com/nodemailer/mailparser/compare/v3.7.0...v3.7.1) (2024-04-25)


### Bug Fixes

* **deps:** Replaced 'punycode' with 'punycode.js' module ([4a15157](https://github.com/nodemailer/mailparser/commit/4a15157dc9a815aa0e756d9e6ae0e8631842c447))

## [3.7.0](https://github.com/nodemailer/mailparser/compare/v3.6.9...v3.7.0) (2024-04-01)


### Features

* **events:** Emit a new headerLines event to gain access the raw headers ([#364](https://github.com/nodemailer/mailparser/issues/364)) ([d33d7ec](https://github.com/nodemailer/mailparser/commit/d33d7ec4b8e32a4eb7a9a664cec5fdb545c274af))

## [3.6.9](https://github.com/nodemailer/mailparser/compare/v3.6.8...v3.6.9) (2024-02-29)


### Bug Fixes

* **deps:** Bumped deps ([db842ad](https://github.com/nodemailer/mailparser/commit/db842addd36e2fe94d0c4b466da80719a36f47ac))

## [3.6.8](https://github.com/nodemailer/mailparser/compare/v3.6.7...v3.6.8) (2024-02-29)


### Bug Fixes

* **punycode:** Fixes [#355](https://github.com/nodemailer/mailparser/issues/355) Deprecation warning of the punycode module ([#356](https://github.com/nodemailer/mailparser/issues/356)) ([0f35330](https://github.com/nodemailer/mailparser/commit/0f35330c87d715d38e8c853ae6c2f64d098b971d))

## [3.6.7](https://github.com/nodemailer/mailparser/compare/v3.6.6...v3.6.7) (2024-02-01)


### Bug Fixes

* :arrow_up: update nodemailer dependency to resolve security issue GHSA-9h6g-pr28-7cqp ([#357](https://github.com/nodemailer/mailparser/issues/357)) ([8bc4225](https://github.com/nodemailer/mailparser/commit/8bc42251fca6f538ece599f0a5bebe09b0aeff4f))

## [3.6.6](https://github.com/nodemailer/mailparser/compare/v3.6.5...v3.6.6) (2024-01-04)


### Bug Fixes

* **deploy:** added auto-deployment ([d6eb56f](https://github.com/nodemailer/mailparser/commit/d6eb56fe09fe8b415e5bbf2e53704f6788ca0fee))
* Fix produced text address list string according to rfc 2822 ([#340](https://github.com/nodemailer/mailparser/issues/340)) ([6bae600](https://github.com/nodemailer/mailparser/commit/6bae600a3f4a0452ee7ca43634a11939de7bcc6d))
* **test:** updated test matrix (18, 20, 21) ([a2ba9c2](https://github.com/nodemailer/mailparser/commit/a2ba9c236dcd7f990c9d53a386ffaa5b564181b3))
