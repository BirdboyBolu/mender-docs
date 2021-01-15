---
title: Release notes & changelog
taxonomy:
    category: docs
shortcode-core:
    active: false
---

## meta-mender rocko-v2018.02

_Released 02.02.2018_

#### . (rocko-v2018.02)
* mender: Append to fstab rather than replacing it.
* Add mender-1.4.0b1 and mender-artifact-2.2.0b1 recipes.
* Fix 'depends upon non-existent task' error in U-Boot recipes without auto patching.
* Add mender-1.3.1 and mender-artifact-2.1.2 recipes.
* QEMU: Raise systemd service timeout so that it boots properly on slow hosts.
* Added new state script to wait for time sync to complete.
* Fix "No rule to make target 'envtools'" error in some U-Boot builds.
* Pregenerate SSH keys for all QEMU images.


## Mender v1.3.1

_Released 02.09.2018_

#### integration (1.3.1)
* Upgrade gui to 1.3.1.
* Upgrade mender to 1.3.1.
* Upgrade mender-artifact to 2.1.2.

#### mender (1.3.1)
* Print detailed logs about authorization errors.
  ([MEN-1660](https://tracker.mender.io/browse/MEN-1660), [MEN-1661](https://tracker.mender.io/browse/MEN-1661))

#### mender-artifact (2.1.2)
* Fix ECDSA failures while signing and verifying artifact.
  ([MEN-1470](https://tracker.mender.io/browse/MEN-1470))


## meta-mender rocko-v2018.01

_Released 01.04.2018_

* meta-mender-core: Allow dtbos in KERNEL_DEVICETREE

## meta-mender rocko-v2017.12

_Released 12.20.2017_

* mender-artifact: Fix build failure due to poky golang source directory changes.
* Catch up with latest poky U-Boot v2017.05.
* Fix build failure after poky switched to checking out Go
  sources under the full GOPATH.
* rpi-u-boot-scr: Switch to boot.cmd.in style recipe.
* sato: Set NETWORK_MANAGER to systemd.
* Update example-state-scripts to use standard logging.
* Add Mender 1.3.0b1 recipe.
* Work around bug in libpseudo regarding file owners on data partition.
* Add machine configuration for Mender on colibri-imx7
* u-boot: update mender_boot_part_name when mender_boot_part changes
* Remove meta-mender-beaglebone layer. This layer is not
  needed anymore for compiling for Beaglebone and should be removed from
  all build configurations.
  ([MEN-1387](https://tracker.mender.io/browse/MEN-1387))
* Add example recipe to show how to deploy files into Mender persistent data partition
* mender-artifact: Fix build failure due to poky golang support changes.
* meta-mender-raspberrypi: increase layer priority to 10
* Fix bug where MENDER_DEVICE_TYPES_COMPATIBLE would only accept one entry.
* mender: Adjust patches for U-Boot v2017.09
* mender: Use GO environment variable to launch the compiler
* Implement heuristic automatic patching of U-Boot.
  It can be turned on and off by setting `MENDER_UBOOT_AUTO_CONFIGURE`
  to `1` and `0`, respectively, in a `u-boot.bbappend` file. It is on by
  default. If the automatic patching is unsuccessful, there is a special
  bitbake target that can be used to extract the generated patch and use
  it as a basis for a manual patch. It can be invoked with `bitbake -c
  save_mender_auto_configured_patch <u-boot-recipe>`, where
  `<u-boot-recipe>` is either `u-boot` or the fork of U-Boot that your
  board uses. ([MEN-1387](https://tracker.mender.io/browse/MEN-1387))
* Bump mender and mender-artifact to version 1.1.0 and 2.0.0, respectively.
* Remove recipes for Mender 1.0.x series.
* Add Mender 1.3.0 build recipe.


## meta-mender pyro-v2017.12

_Released 12.20.2017_

* Fix bug where MENDER_DEVICE_TYPES_COMPATIBLE would only accept one entry.
* Add Mender 1.3.0 build recipe.
* u-boot: update mender_boot_part_name when mender_boot_part changes
* Update example-state-scripts to use standard logging.
* meta-mender-raspberrypi: increase layer priority to 10
* sato: Set NETWORK_MANAGER to systemd.
* Add machine configuration for Mender on colibri-imx7


## Mender v1.3.0

_Released 12.21.2017_

#### integration (1.3.0)
* Upgrade deployments to 1.3.0.
* Upgrade deviceadm to 1.2.0.
* Upgrade deviceauth to 1.3.0.
* Upgrade gui to 1.3.0.
* Upgrade inventory to 1.2.0.
* Upgrade mender to 1.3.0.
* Upgrade mender-api-gateway-docker to 1.3.0.
* Upgrade useradm to 1.3.0.

#### mender (1.3.0)
* Remove trailing slash from server URL configuration.
  ([MEN-1620](https://tracker.mender.io/browse/MEN-1620))


## meta-mender pyro-v2017.11

_Released 11.14.2017_

* Add Mender 1.3.0b1 recipe.
* Upstream image has grown significantly, increase to 608MB sdimg.
  The noticeably non-round number is to make sure the calculated rootfs
  size is divisible by the partition alignment.


## Mender v1.3.0b1

_Released 11.14.2017_

#### deployments (1.3.0b1)
* docs: dump expire parameter from artifact download endpoint
* deployments/controller: handle substate field in device status updates
* images: make artifact download links valid for 15 minutes only
* deployments: descending sort by created time when listing deployments
* deployments/controller: status report substate field length limited to 200 characters
* Additional MongoDB configuration options: mongo_ssl, mongo_ssl_skipverify, mongo_username, mongo_password
* docs/management: return device state and substate in device deployment info
* limits: add GET /limits/storage management endpoint
* deployments: make artifact download links valid for 1 hour only
* Prevent artifacts with invalid checksums from
  being uploaded to the server.
  ([MEN-1412](https://tracker.mender.io/browse/MEN-1412))
* docs/internal: spec for GET /tenants/:id/limits/storage
* Additional MongoDB configuration options: mongo_ssl, mongo…
* docs: document that expire on /artifacts/{id}/download is silently ignored
* POST /api/v1/internal/tenants ep
* docs/devices: add optional substate field in status ported

#### deviceadm (1.2.0b1)
* middleware: accommodate changes in request{id,log} middleware and enable request logger update
* Additional MongoDB configuration options: mongo_ssl, mongo_ssl_skipverify, mongo_username, mongo_password
* Additional MongoDB configuration options: mongo_ssl, mongo…
* store/mongo: move single tenant migration to separate func
* main: add 'migrate [--tenant=<tenant ID>]' command

#### deviceauth (1.3.0b1)
* GET /devices/count?status endpoint
* devauth: only one accepted authset
  When accepting an auth set, reject all other accepted auth sets of a particular
  device. This way we make sure that only one auth set is accepted at a time. In
  case when key rotation is used, old key cannot be used to obtain the token.
  ([MEN-1417](https://tracker.mender.io/browse/MEN-1417))
* store/mongo: properly setup context for migrations in multi tenant
* api/http: support for internal endpoint for setting per-tenant limits
  Add support for PUT operation on a new internal endpoint
  `/api/internal/v1/devauth/tenant/:id/limits/:name`. The endpoint is used for
  setting per tenant limits.
* store/mongo: make UpdateAuthSet() operate on multiple auth sets
* store, store/mongo: add collection for keeping 'Limits'
* devauth: ignore store.ErrAuthSetNotFound when rejecting auth sets during accept
* devauth: set Authorization field in  device decommissioning requests
* devauth: support for saving per-tenant limits
* devauth: log a message when the token is does not have a mender.device claim
* docs: include Authorization header in spec of authset status PUT endpoint
* Additional MongoDB configuration options: mongo_ssl, mongo_ssl_skipverify, mongo_username, mongo_password
* migrate --tenant=... cli
* store/mongo: raise store.ErrAuthSetNotFound when no auth sets were updated
* model: add Limit wrapper, add predefined limit name - max_device_count
* jwt: add mender.device claim, type bool, defaults to false
* docs/internal: remove 404 status on PUT /tenant/:id/limits/max-device-count
* middleware: repacking of logger and request ID to context is no longer needed
* docs: add spec for GET /limits/max_devices
* devauth: set and verify mender.device claim
  Device tokens given out by deviceauth service will now have 'mender.device'
  claim set to true. Tokens without the claim will fail verification and will be
  rejected. Device is expected to request a new token.
* client/orchestrator: pass 'authorization' parameter in device decommission request

#### gui (1.3.0b1)
* Fix logout issues, only timeout user when inactive
* Fix for showing incorrect device IDs
  ([MEN-1536](https://tracker.mender.io/browse/MEN-1536))
* Added onboarding helptips that toggle on/off per user
* Added API connection error messaging and timeouts to Deployments tab
* Added API timeouts and disconnection error retry messages to devices and artifacts tabs
* disable decommissioning button while request is in progress
* API connection error and retry for deployments on dashboard

#### integration (1.3.0b1)
* compose, template: set mender-inventory command to `server --automigrate`
  Ensure that inventory service starts in daemon mode and automatically applies DB
  migrations.
* Fix Missing restart policy for some containers in
  docker-compose setup.
  ([MEN-1556](https://tracker.mender.io/browse/MEN-1556))
* Update conductor to 1.7.7
* allow access to https://localhost in test environment
* Update conductor to 1.7.7
* Upgrade deployments to 1.3.0b1.
* Upgrade deviceadm to 1.2.0b1.
* Upgrade deviceauth to 1.3.0b1.
* Upgrade gui to 1.3.0b1.
* Upgrade inventory to 1.2.0b1.
* Upgrade mender to 1.3.0b1.
* Upgrade mender-api-gateway-docker to 1.3.0b1.
* Upgrade useradm to 1.3.0b1.
* conductor: include Authorization header in decommissioning workflow

#### inventory (1.2.0b1)
* main: add server [--automigrate] command, drop previous command line flags
  Command line invocation and parameters are changed. See --help output for
  details.
  `server` subcommand will start the services in 'daemon' mode (sans the forking
  part). Optional `--automigrate` argument enables automatic DB migration,
  otherwise then a migration is needed the service will exit logging an error.
* Additional MongoDB configuration options: mongo_ssl, mongo_ssl_skipverify, mongo_username, mongo_password
* main: add 'migrate [--tenant=<tenant ID>]' command
* middleware: accommodate changes in request{id,log} middleware and enable request logger update
* dockerfile: update entrypoint to match currently supported command line arguments
* Additional MongoDB configuration options: mongo_ssl, mongo…

#### mender (1.3.0b1)
* Mender now logs whatever a state-script outputs to stderr
  ([MEN-1349](https://tracker.mender.io/browse/MEN-1349))
* mender-device-identity: only collect MAC from ARPHRD_ETHER types
* Fix 'unexpected EOF' error when downloading large updates.
  ([MEN-1511](https://tracker.mender.io/browse/MEN-1511))
* Implement ability for client to resume a download from
  where it left off if the connection is broken.
  ([MEN-1511](https://tracker.mender.io/browse/MEN-1511))
* Improve error messages for state scripts errors.
  Rely on the full error description instead of just the error code.
* Fix compile for ARM64.
* set return code = 2, when there is nothing to commit
* Added retry-later functionality on top of the state-script functionality
* Correctly fail state script execution if stderr can not be opened.
  It would not be impossible to continue execution in this case, but it
  is bad to lose log output, and not being able to open stderr is a
  pretty uncommon case that might indicate a more serious issue like
  resource starvation.

#### mender-api-gateway-docker (1.3.0b1)
* Introduce static content caching for /ui routing.
* Make browser side UI caching configurable though CACHE_UI env. Disabled by default.
* Include request time in gateway access logs.
* nginx: separate HTTP and HTTPS server scopes, redirect all HTTP requests to HTTPS
* nginx: align gateway URLs with useradm API
* Introduce static content caching for /ui routing.
* deployments service routing
* gateway dns cache reloading for improved recovery from service restarts
  ([MEN-1227](https://tracker.mender.io/browse/MEN-1227))
* Include request time in gateway access logs.

#### useradm (1.3.0b1)
* docs: add undocumented X-Original-URI, X-Original-Method on internal /auth/verify
* store/mongo: TenantDataStore uses a store with automigrations enabled
* commands: add 'migrate [--tenant=<id>]' command
* middleware: accommodate changes in request{id,log} middleware and enable request logger update
* jwt: add mender.user claim, bool
  Add 'mender.user' claim to tokens given out bu useradm. The claim indicates that
  the token is assigned to a user and a 'sub' claim corresponds to user ID.
* store/mongo: With*() helpers return a new instance of store with correct property modified
* docs: spec for an endpoint for setting up tenants
* commands: propagate new user to tenantadm
  ([MEN-1311](https://tracker.mender.io/browse/MEN-1311))
* store/mongo: move migration of single tenant to separate func
* api/http: update internal URLs, align them with API URL schema
  Internal URLs are now available with /api/internal/v1/useradm/ prefix
* store: introduce tenant keeper
* docs: align internal URLs with API URL scheme
* useradm: add mender.user claim to given out tokens
  Append 'mender.user' claim to all given out tokens. All tokens that do not have
  this claim will fail verification and be rejected forcing the user to log in again.
* set correct header when sending token
* useradm: add CreateTenant operation
* api/http: add endpoint for creating tenants


## Mender v1.2.0

_Released 09.05.2017_

#### deployments (1.2.0)
* Deployment creation process changed. From now on artifacts are
  assigned to device deployments on update request handling.
* Return 422 - Unprocessable Entity on attempt of creating deployment without artifacts
* Deployments no longer require inventory to create deployments.
* New optional array field: 'artifacts' in deployment object returned by API containing list of artifact ids used by deployment.

#### deviceauth (1.2.0)
* Introduce 'server' subcommand that is also default command. Supports '--automigrate' parameter to enable automatic database version migration on startup.
* Increase orchestrater request timeout to 30s

#### gui (1.2.0)
* Bugfix for multiplying GET devices requests
* Add ‘create user’ functionality
* Change root API url to docker.mender.io
* Removed user creation UI incl password strength check (#231)
* Added user management edit functionality
* Updated node modules
* Remove shortened device IDs, now useless due to incremental SHAs
* create deployment from single device ([MEN-1233](https://tracker.mender.io/browse/MEN-1233))
* Allow user to remove artifacts via the GUI
* Added self user management

#### integration (1.2.0)
* Move interactive flags for client container to main docker file.
  Makes it available for debugging on all client containers, not just
  dev containers.
* allow access to https://localhost in test environment

#### mender (1.2.0)
* Refactored all store implementations into /store
* Improve error message when manifest field/file cannot be read.
* Fixed format check to conform to the expected artifact-file-format
  ([MEN-1289](https://tracker.mender.io/browse/MEN-1289))
* installer: improve incompatible image error message
* Client will not run state scripts from cmd-line except when forced.
  ([MEN-1235](https://tracker.mender.io/browse/MEN-1235))
* Fixed behaviour when no sys-cert is available on the system.
  ([MEN-1151](https://tracker.mender.io/browse/MEN-1151))
* Mender now logs whatever a state-script outputs to stderr
  ([MEN-1349](https://tracker.mender.io/browse/MEN-1349))
* Fix misleading version being displayed for non-tagged builds.
  ([MEN-1178](https://tracker.mender.io/browse/MEN-1178))
* Changed the errormessage to more closely reflect the issue.
  ([MEN-1215](https://tracker.mender.io/browse/MEN-1215))
* Removed the DeviceKey option in menderConfig.
* Fix - Now throws an error when committing nothing.
  ([MEN-505](https://tracker.mender.io/browse/MEN-505))
* Introduction of state script feature. State scripts can be
  used to execute scripts at various stages of Mender's execution. See
  documentation for more information.
* Introduce experimental support for writing to UBI volumes
* Logs an error when device_type file not found.
  ([MEN-505](https://tracker.mender.io/browse/MEN-505))
* remove no longer referenced client certificate code

#### mender-api-gateway-docker (1.2.0)
* Return additional headers for improved security: X-XSS-Protection, Cache-Control, Pragma. ([MEN-1316](https://tracker.mender.io/browse/MEN-1316))
* Validate Origin header if present. ([MEN-1287](https://tracker.mender.io/browse/MEN-1287))
* Add a configurable Host whitelist to gateway configuration, denying requests with unknown Hosts. Configured through ALLOWED_HOSTS env var on gateway startup. ([MEN-1262](https://tracker.mender.io/browse/MEN-1262))

#### mender-artifact (2.1.0)
* Sign existing artifacts using mender-artifact CLI
  ([MEN-1220](https://tracker.mender.io/browse/MEN-1220))
* Improve error message when private signing key can't be loaded.
* Fix misleading version being displayed for non-tagged builds.
  ([MEN-1178](https://tracker.mender.io/browse/MEN-1178))
* Mender-Artifact now returns an error code to the os on cli errors
  ([MEN-1328](https://tracker.mender.io/browse/MEN-1328))
* mender-artifact now fails with whitespace in the artifact-name
  ([MEN-1355](https://tracker.mender.io/browse/MEN-1355))

#### useradm (1.2.0)
* Improve log messages when opening connection to MongoDB.
* Additional MongoDB configuration options: mongo_ssl, mongo_ssl_skipverify, mongo_username, mongo_password
* Remove 'initial user' login logic, including 'POST /users/initial' API. Now initial user need to be created by administrator using cli ([MEN-1034](https://tracker.mender.io/browse/MEN-1034))
* New cli subcommand for creating users: 'useradm create-user. ([MEN-1034](https://tracker.mender.io/browse/MEN-1034))
* New API for listing users: 'GET https://localhost/api/management/v1/useradm/users' and 'GET https://localhost/api/management/v1/useradm/users/:userid'
* New API for creating additional users: 'POST https://localhost/api/management/v1/useradm/users'
* New API for editing user email and password: 'PUT https://localhost/api/management/v1/useradm/users/:userid'
* New API for removing user: 'DELETE https://localhost/api/management/v1/useradm/users/:userid'


## Mender v1.1.0

_Released 06.16.2017_

#### gui

* Remove shortened device IDs, now useless due to incremental SHAs
* Fix for [MEN-1233](https://tracker.mender.io/browse/MEN-1233) - create deployment from single device

#### mender

* Fix misleading version being displayed for non-tagged builds. ([MEN-1178](https://tracker.mender.io/browse/MEN-1178))


## Mender v1.1.0 Beta 1

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


## Mender v1.0.1
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

## Mender v1.0.0 
_Released 02.20.2017_

---
