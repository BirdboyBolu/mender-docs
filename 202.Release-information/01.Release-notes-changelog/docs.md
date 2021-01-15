---
title: Release notes & changelog
taxonomy:
    category: docs
shortcode-core:
    active: false
---

## v1.1.3

_Released 10.02.2017_

#### integration (1.1.3)
* Fix incorrectly set service version references.


## v1.1.2

_(Never released publicly)_

#### deployments (1.1.1)
* Prevent artifacts with invalid checksums from
  being uploaded to the server.
  ([MEN-1412](https://tracker.mender.io/browse/MEN-1412))

#### integration (1.1.2)
* Upgrade deployments to 1.1.1.
* Upgrade mender to 1.1.2.
* Upgrade mender-artifact to 2.0.2.

#### mender (1.1.2)
* Fix checksum not being verified for headers, only
  payload. ([MEN-1412](https://tracker.mender.io/browse/MEN-1412))

#### mender-artifact (2.0.2)
* Fix broken header checksum verification.
  ([MEN-1412](https://tracker.mender.io/browse/MEN-1412))


## v1.1.1

_Released 09.05.2017_

#### mender
* Fix - Now throws an error when committing nothing.
  ([MEN-505](https://tracker.mender.io/browse/MEN-505))
* Changed the errormessage to more closely reflect the issue.
  ([MEN-1215](https://tracker.mender.io/browse/MEN-1215))
* Improve error message when manifest field/file cannot be read.
* Logs an error when device_type file not found.
  ([MEN-505](https://tracker.mender.io/browse/MEN-505))
* Fixed behaviour when no sys-cert is available on the system.
  ([MEN-1151](https://tracker.mender.io/browse/MEN-1151))
* installer: improve incompatible image error message

#### mender-artifact
* Sign existing artifacts using mender-artifact CLI
  ([MEN-1220](https://tracker.mender.io/browse/MEN-1220))
* mender-artifact now fails with whitespace in the artifact-name
  ([MEN-1355](https://tracker.mender.io/browse/MEN-1355))
* Mender-Artifact now returns an error code to the os on cli errors
  ([MEN-1328](https://tracker.mender.io/browse/MEN-1328))


## v1.1.0

_Released 06.16.2017_

#### gui

* Remove shortened device IDs, now useless due to incremental SHAs
* Fix for [MEN-1233](https://tracker.mender.io/browse/MEN-1233) - create deployment from single device

#### mender

* Fix misleading version being displayed for non-tagged builds. ([MEN-1178](https://tracker.mender.io/browse/MEN-1178))


## v1.1.0 Beta 1

_Released 05.24.2017_

#### deployments
* Increase file upload request validity when pushing artifact to remote file storage.
* Update artifact handling reflecting changes in mender-artifact.
* Support for signed images introduced, but with no signature
  verification yet. ([MEN-1022](https://tracker.mender.io/browse/MEN-1022))
* Add device decommissioning support in the deployments service.
* Update artifact description when updating artifact data.
* images/s3: unmarshal S3 errors when uploading image
* Artifact upload error handling fixed.
* Update artifact description when updating artifact data. ([MEN-1093](https://tracker.mender.io/browse/MEN-1093))
* travis: bump required Go version to 1.8

#### deviceadm
* Support for listing device authentication data sets with device ID
  filter using GET /devices?device_id=<devid>

#### deviceauth
* New feature: decommissioning device
* devauth: improve logging when rejecting or giving out tokens
* Decommission device endpoint implemented (without
  decommission job submit).
* api/management: management API is publicly available, update misleading description
* api: add tenant_token as an optional attribute in authentication request

#### gui
* Artifact signed field and improvements ([MEN-230](https://tracker.mender.io/browse/MEN-230))
* Bugfix: hide placeholder when past deployments is not empty ([MEN-229](https://tracker.mender.io/browse/MEN-229))
* Device blocking & decommissioning ([MEN-226](https://tracker.mender.io/browse/MEN-226))
* Implement pagination UI on pending & in progress deployment lists ([MEN-222](https://tracker.mender.io/browse/MEN-222))

#### integration
* Upgrade all server components to 1.1 series
* Upgrade client to 1.1
* Upgrade mender-artifact to 2.0

#### inventory
* No changes

#### mender-api-gateway-docker
* nginx: log and pass X-MEN-RequestID

#### mender-artifact
* Switch default artifact format version to 2. ([MEN-1183](https://tracker.mender.io/browse/MEN-1183))
* Add CLI support for signing and verifying images.
* Add implementation of RSA and ECDSA signatures.
* Fix returning and printing errors form artifact library.
* Fix overwriting artifact if new one is invalid.
* Add basic signing functionality and rewrite the library.

#### mender
* Add support for using signed mender-artifact library.
* Add support for verifying artifact signature. ([MEN-1020](https://tracker.mender.io/browse/MEN-1020))

#### useradm
* Added `create-user` and `server` commands to useradm. Running
  `useradm server` will start useradm service (just like running `useradm` did),
  also if no command is passed `server` is used a default. `create-user` will add
  given user to DB. Examples: `useradm create-user --username foo@bar.com
  --password foobarbarbar` (creates a user with username foo@bar.com and password
  foobar...), `useradm create-user --username foo@bar.com` (same as before, but
  password is read from terminal). See `--help` for details.


## v1.0.1
_Released 04.05.2017_

### Notable changes

#### deployments

* Update artifact description when updating artifact data. (MEN-1093)
* Fix log flag not being set for device deployment after log been uploaded.
  (MEN-1078)

#### gui

* Bugfix: open correct deployment report dialog from dashboard
* Update node modules, add drag+drop artifact, allow edit
  artifact description
* Move user token from local storage to cookie, add react-cookie module (#217)
* Update node modules, add drag+drop & cookie functionality (#219)
* Replace artifact upload dialog with drag-and-drop
* Remove cookie when receiving unauthorized response
* Edit artifact description in UI

#### mender

* Fix bug that caused the update not to be retried after failing during
  previous attempt (#193)

---

## v1.0.0 
_Released 02.20.2017_

---
