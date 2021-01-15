---
title: Release notes & changelog
taxonomy:
    category: docs
shortcode-core:
    active: false
---

## meta-mender rocko-v2019.08

_Released 09.02.2019_

### Statistics

A total of 89 lines added, 121 removed (delta -32)

| Developers with the most changesets | |
|---|---|
| Lluis Campos | 8 (44.4%) |
| Kristian Amlie | 5 (27.8%) |
| Drew Moseley | 3 (16.7%) |
| Ole Petter Orhagen | 1 (5.6%) |
| Jonas Norling | 1 (5.6%) |

| Developers with the most changed lines | |
|---|---|
| Lluis Campos | 116 (63.7%) |
| Kristian Amlie | 51 (28.0%) |
| Drew Moseley | 13 (7.1%) |
| Ole Petter Orhagen | 1 (0.5%) |
| Jonas Norling | 1 (0.5%) |

| Developers with the most lines removed | |
|---|---|
| Lluis Campos | 71 (58.7%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 17 (94.4%) |
| GreenEggs AB | 1 (5.6%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 181 (99.5%) |
| GreenEggs AB | 1 (0.5%) |

| Employers with the most hackers (total 5) | |
|---|---|
| Northern.tech | 4 (80.0%) |
| GreenEggs AB | 1 (20.0%) |

### Changelogs

#### meta-mender (rocko-v2019.08)

New changes in meta-mender since rocko-v2019.05:

* Fix build failing in do_image_ubimg task
* Demo images now include Yocto LSB package.
  ([MEN-2421](https://tracker.mender.io/browse/MEN-2421))
* QEMU: Add inventory script for Docker IP and open port 80.
  ([MEN-2574](https://tracker.mender.io/browse/MEN-2574))
* u-boot-mender: Add define for MENDER_STORAGE_DEVICE
* Add recipes for mender 2.0.1 and mender-artifact 3.0.1
* Remap port 85 on host to 85 in qemu
* Add mender 2.1.0b1 and mender-artifact 3.1.0b1 recipes.
  Part of Mender 2.1.0 Beta release.


## meta-mender sumo-v2019.08

_Released 09.02.2019_

### Statistics

A total of 93 lines added, 124 removed (delta -31)

| Developers with the most changesets | |
|---|---|
| Lluis Campos | 7 (36.8%) |
| Kristian Amlie | 6 (31.6%) |
| Drew Moseley | 4 (21.1%) |
| Ole Petter Orhagen | 1 (5.3%) |
| Jonas Norling | 1 (5.3%) |

| Developers with the most changed lines | |
|---|---|
| Lluis Campos | 111 (59.7%) |
| Kristian Amlie | 57 (30.6%) |
| Drew Moseley | 16 (8.6%) |
| Ole Petter Orhagen | 1 (0.5%) |
| Jonas Norling | 1 (0.5%) |

| Developers with the most lines removed | |
|---|---|
| Lluis Campos | 71 (57.3%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 18 (94.7%) |
| GreenEggs AB | 1 (5.3%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 185 (99.5%) |
| GreenEggs AB | 1 (0.5%) |

| Employers with the most hackers (total 5) | |
|---|---|
| Northern.tech | 4 (80.0%) |
| GreenEggs AB | 1 (20.0%) |

### Changelogs

#### meta-mender (sumo-v2019.08)

New changes in meta-mender since sumo-v2019.05:

* Fix build failing in do_image_ubimg task
* Demo images now include Yocto LSB package.
  ([MEN-2421](https://tracker.mender.io/browse/MEN-2421))
* QEMU: Add inventory script for Docker IP and open port 80.
  ([MEN-2574](https://tracker.mender.io/browse/MEN-2574))
* u-boot-mender: Add define for MENDER_STORAGE_DEVICE
* Add recipes for mender 2.0.1 and mender-artifact 3.0.1
* Remap port 85 on host to 85 in qemu
* Add mender 2.1.0b1 and mender-artifact 3.1.0b1 recipes.
  Part of Mender 2.1.0 Beta release.


## mender-convert 1.1.1

_Released 07.01.2019_

### Statistics

A total of 26 lines added, 23 removed (delta 3)

| Developers with the most changesets | |
|---|---|
| Mirza Krak | 2 (40.0%) |
| Lluis Campos | 1 (20.0%) |
| Adam Podogrocki | 1 (20.0%) |
| Marek Belisko | 1 (20.0%) |

| Developers with the most changed lines | |
|---|---|
| Mirza Krak | 19 (47.5%) |
| Adam Podogrocki | 17 (42.5%) |
| Lluis Campos | 3 (7.5%) |
| Marek Belisko | 1 (2.5%) |

| Developers with the most lines removed | |
|---|---|
| Mirza Krak | 14 (60.9%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 3 (60.0%) |
| RnDity | 1 (20.0%) |
| open-nandra | 1 (20.0%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 22 (55.0%) |
| RnDity | 17 (42.5%) |
| open-nandra | 1 (2.5%) |

| Employers with the most hackers (total 4) | |
|---|---|
| Northern.tech | 2 (50.0%) |
| RnDity | 1 (25.0%) |
| open-nandra | 1 (25.0%) |


### Changelogs

#### mender-convert (1.1.1)

New changes in mender-convert since 1.1.0:

* rpi: Bump u-boot version to fix booting on rpi0w after raspi-config resize partition
  ([MEN-2436](https://tracker.mender.io/browse/MEN-2436))
* shrink expanded rootfs when running "from_raw_disk_image"
* Update mender-convert to for Mender v2.0.1 release


## meta-mender thud-v2019.07

_Released 07.01.2019_

### Statistics

A total of 64 lines added, 20 removed (delta 44)

| Developers with the most changesets | |
|---|---|
| Kristian Amlie | 6 (46.2%) |
| Lluis Campos | 3 (23.1%) |
| Drew Moseley | 3 (23.1%) |
| Jonas Norling | 1 (7.7%) |

| Developers with the most changed lines | |
|---|---|
| Kristian Amlie | 52 (81.2%) |
| Lluis Campos | 6 (9.4%) |
| Drew Moseley | 5 (7.8%) |
| Jonas Norling | 1 (1.6%) |

| Developers with the most report credits (total 1) | |
|---|---|
| Drew Moseley | 1 (100.0%) |

| Developers who gave the most report credits (total 1) | |
|---|---|
| Kristian Amlie | 1 (100.0%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 12 (92.3%) |
| GreenEggs AB | 1 (7.7%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 63 (98.4%) |
| GreenEggs AB | 1 (1.6%) |

| Employers with the most hackers (total 4) | |
|---|---|
| Northern.tech | 3 (75.0%) |
| GreenEggs AB | 1 (25.0%) |


### Changelogs

#### meta-mender (thud-v2019.07)

New changes in meta-mender since thud-v2019.05:

* Fix build failing in do_image_ubimg task
* Demo images now include Yocto LSB package.
  ([MEN-2421](https://tracker.mender.io/browse/MEN-2421))
* QEMU: Add inventory script for Docker IP and open port 80.
  ([MEN-2574](https://tracker.mender.io/browse/MEN-2574))
* grub-mender-grubenv: Fix broken 'debug-pause' `PACKAGECONFIG`.
* u-boot-mender: Add define for MENDER_STORAGE_DEVICE
* Add recipes for mender 2.0.1 and mender-artifact 3.0.1


## Mender 2.0.1

_Released 06.24.2019_

### Statistics

A total of 622 lines added, 284 removed (delta 338)

| Developers with the most changesets | |
|---|---|
| Manuel Zedel | 13 (48.1%) |
| Kristian Amlie | 8 (29.6%) |
| Michael Clelland | 2 (7.4%) |
| Oleksandr Miliukov | 2 (7.4%) |
| Eystein Måløy Stenberg | 1 (3.7%) |
| Lluis Campos | 1 (3.7%) |

| Developers with the most changed lines | |
|---|---|
| Kristian Amlie | 403 (60.0%) |
| Manuel Zedel | 185 (27.5%) |
| Oleksandr Miliukov | 61 (9.1%) |
| Lluis Campos | 13 (1.9%) |
| Michael Clelland | 6 (0.9%) |
| Eystein Måløy Stenberg | 4 (0.6%) |

| Developers with the most lines removed | |
|---|---|
| Michael Clelland | 2 (0.7%) |

| Developers with the most report credits (total 1) | |
|---|---|
| Cedric Veilleux | 1 (100.0%) |

| Developers who gave the most report credits (total 1) | |
|---|---|
| Kristian Amlie | 1 (100.0%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 27 (100.0%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 672 (100.0%) |

| Employers with the most hackers (total 6) | |
|---|---|
| Northern.tech | 6 (100.0%) |


### Changelogs

#### gui (2.0.1)

New changes in gui since 2.0.0:

* long device inventory texts are no longer cut off + visible on hover
* updated dependencies
* Bugfix for innaccurate offline devices on dashboard
* Bugfix to ensure pending device checkboxes work as expected
* Prevented blank page on no result release search
  ([MEN-2572](https://tracker.mender.io/browse/MEN-2572))

#### integration (2.0.1)

New changes in integration since 2.0.0:

* Upgrade gui to 2.0.1.
* Upgrade mender to 2.0.1.
* Upgrade mender-artifact to 3.0.1.
* Upgrade mender-conductor to 1.3.1.
* Upgrade mender-conductor-enterprise to 1.3.1.

#### mender (2.0.1)

New changes in mender since 2.0.0:

* module-artifact-gen: Fix inability to specify more than one device_type.
* single-file module: Make sure permissions are preserved.
  Also make sure that backup preserves permissions.
* Artifact gen: Support argument passthrough to `mender-artifact`.
  Use `--` to signal that remaining arguments should be passed directly
  to `mender-artifact`.
* Restore error code 2 behavior when there is nothing to commit.

#### mender-artifact (3.0.1)

New changes in mender-artifact since 3.0.0:

* Fix non-rootfs Artifacts being destroyed when signing them.
  ([MEN-2573](https://tracker.mender.io/browse/MEN-2573))

#### mender-conductor (1.3.1)

New changes in mender-conductor since 1.3.0:

* Timestamp added to send_email worker
* email-sender: fixed bug with wrong state reporting


## meta-mender rocko-v2019.05

_Released 05.15.2019_

### Statistics

A total of 14 lines added, 12 removed (delta 2)

| Developers with the most changesets | |
|---|---|
| Kristian Amlie | 2 (40.0%) |
| Mirza Krak | 1 (20.0%) |
| Ajith P Venugopal | 1 (20.0%) |
| Lluis Campos | 1 (20.0%) |

| Developers with the most changed lines | |
|---|---|
| Kristian Amlie | 9 (64.3%) |
| Ajith P Venugopal | 2 (14.3%) |
| Lluis Campos | 2 (14.3%) |
| Mirza Krak | 1 (7.1%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 4 (80.0%) |
| ajithpv@outlook.com | 1 (20.0%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 12 (85.7%) |
| ajithpv@outlook.com | 2 (14.3%) |

| Employers with the most hackers (total 4) | |
|---|---|
| Northern.tech | 3 (75.0%) |
| ajithpv@outlook.com | 1 (25.0%) |


### Changelogs

#### meta-mender (rocko-v2019.05)

New changes in meta-mender since rocko-v2019.04:

* Fix mender 2.0.x and mender-artifact 3.0.x recipes to use the
  correct branches when fetching the source.
* Add missing build dependency on "xz" in Mender Artifact recipe for 3.0.0b1 version
* Add recipes for mender-1.7.1 and mender-artifact-2.4.1.
* Add recipes for mender-2.0.0 and mender-artifact-3.0.0.
  Note that these recipes are not enabled by default in thud. If you
  want to use them, you have to add this to your build configuration:
  ```
  PREFERRED_VERSION_pn-mender = "2.%"
  PREFERRED_VERSION_pn-mender-artifact = "3.%"
  PREFERRED_VERSION_pn-mender-artifact-native = "3.%"
  ```
* Fix GRUB start-up on x86 by renaming "boot.efi" to "bootia32.efi"


## meta-mender sumo-v2019.05

_Released 05.15.2019_

### Statistics

A total of 13 lines added, 11 removed (delta 2)

| Developers with the most changesets | |
|---|---|
| Kristian Amlie | 2 (50.0%) |
| Lluis Campos | 1 (25.0%) |
| Ajith P Venugopal | 1 (25.0%) |

| Developers with the most changed lines | |
|---|---|
| Kristian Amlie | 9 (69.2%) |
| Lluis Campos | 2 (15.4%) |
| Ajith P Venugopal | 2 (15.4%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 3 (75.0%) |
| ajithpv@outlook.com | 1 (25.0%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 11 (84.6%) |
| ajithpv@outlook.com | 2 (15.4%) |

| Employers with the most hackers (total 3) | |
|---|---|
| Northern.tech | 2 (66.7%) |
| ajithpv@outlook.com | 1 (33.3%) |


### Changelogs

#### meta-mender (sumo-v2019.05)

New changes in meta-mender since sumo-v2019.04:

* Add missing build dependency on "xz" in Mender Artifact recipe for 3.0.0b1 version
* Fix mender 2.0.x and mender-artifact 3.0.x recipes to use the
  correct branches when fetching the source.
* Add recipes for mender-1.7.1 and mender-artifact-2.4.1.
* Add recipes for mender-2.0.0 and mender-artifact-3.0.0.
  Note that these recipes are not enabled by default in thud. If you
  want to use them, you have to add this to your build configuration:
  ```
  PREFERRED_VERSION_pn-mender = "2.%"
  PREFERRED_VERSION_pn-mender-artifact = "3.%"
  PREFERRED_VERSION_pn-mender-artifact-native = "3.%"
  ```


## mender-convert 1.1.0

_Released 05.08.2019_

### Statistics

A total of 1512 lines added, 996 removed (delta 516)

| Developers with the most changesets | |
|---|---|
| Mirza Krak | 19 (27.5%) |
| Adam Podogrocki | 16 (23.2%) |
| Eystein Måløy Stenberg | 13 (18.8%) |
| Lluis Campos | 9 (13.0%) |
| Marek Belisko | 4 (5.8%) |
| Simon Gamma | 3 (4.3%) |
| Max Bruckner | 1 (1.4%) |
| Adrian Cuzman | 1 (1.4%) |
| Dominik Adamski | 1 (1.4%) |
| Mika Tuupola | 1 (1.4%) |

| Developers with the most changed lines | |
|---|---|
| Adam Podogrocki | 853 (48.8%) |
| Eystein Måløy Stenberg | 359 (20.5%) |
| Mirza Krak | 301 (17.2%) |
| Lluis Campos | 186 (10.6%) |
| Marek Belisko | 37 (2.1%) |
| Simon Gamma | 7 (0.4%) |
| Max Bruckner | 1 (0.1%) |
| Adrian Cuzman | 1 (0.1%) |
| Dominik Adamski | 1 (0.1%) |
| Mika Tuupola | 1 (0.1%) |

| Developers with the most lines removed | |
|---|---|
| Mirza Krak | 164 (16.5%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 41 (59.4%) |
| RnDity | 17 (24.6%) |
| open-nandra | 4 (5.8%) |
| github@survive.ch | 3 (4.3%) |
| max@maxbruckner.de | 1 (1.4%) |
| adriancuzman@gmail.com | 1 (1.4%) |
| tuupola@appelsiini.net | 1 (1.4%) |
| denismosolov@gmail.com | 1 (1.4%) |

| Top lines changed by employer | |
|---|---|
| RnDity | 854 (48.9%) |
| Northern.tech | 846 (48.4%) |
| open-nandra | 37 (2.1%) |
| github@survive.ch | 7 (0.4%) |
| max@maxbruckner.de | 1 (0.1%) |
| adriancuzman@gmail.com | 1 (0.1%) |
| tuupola@appelsiini.net | 1 (0.1%) |
| denismosolov@gmail.com | 1 (0.1%) |

| Employers with the most hackers (total 11) | |
|---|---|
| Northern.tech | 3 (27.3%) |
| RnDity | 2 (18.2%) |
| open-nandra | 1 (9.1%) |
| github@survive.ch | 1 (9.1%) |
| max@maxbruckner.de | 1 (9.1%) |
| adriancuzman@gmail.com | 1 (9.1%) |
| tuupola@appelsiini.net | 1 (9.1%) |
| denismosolov@gmail.com | 1 (9.1%) |


### Changelogs

#### mender-convert (1.1.0)

New changes in mender-convert since 1.1.0b1:

* Expand existing environment '$PATH' variable instead of replacing it
* Use same environment '$PATH' variable when using sudo
* Fail the docker build when mandatory build-arg 'mender_client_version' is not set.
* Update Dockerfile to use latest stable mender-artifact, v2.4.0
* Use mender-artfact v3. Requires rebuild of device-image-shell container.
* Use LZMA for smaller Artifact size (but slower generation).
* Update mender-convert to use final Mender v2.0 release

New changes in mender-convert since 1.0.0:

* Fix syntax error when calling "mender-convert raw-disk-image-shrink-rootfs"
* Experimental device emulation environment
* Create repartitioned Mender compliant image from Yocto image for qemu x86-64
  ([MEN-2207](https://tracker.mender.io/browse/MEN-2207))
* Add commits check to mender-convert repo
  ([MEN-2282](https://tracker.mender.io/browse/MEN-2282))
* Provide systemd service for Raspberry Pi boards to resize data partition
  ([MEN-2254](https://tracker.mender.io/browse/MEN-2254))
* Install Mender related files to Mender image based on Yocto image for qemu x86-64
  ([MEN-2207](https://tracker.mender.io/browse/MEN-2207))
* Check a Linux ext4 file system before resizing 'primary' partition
  ([MEN-2242](https://tracker.mender.io/browse/MEN-2242))
* compile mender during docker image creation
* Switch to 1.6.0 Mender client as default for docker environment
* Add license check to mender-convert repo
  ([MEN-2282](https://tracker.mender.io/browse/MEN-2282))
* Use a toolchain tuned for ARMv6 architecture to maintain support for Raspberry Pi Zero
  ([MEN-2399](https://tracker.mender.io/browse/MEN-2399))
* Fix docker-mender-convert for paths with spaces
* Add version option for mender convert
  ([MEN-2257](https://tracker.mender.io/browse/MEN-2257))
* Fix permission denied error in when calling "mender-convert raw-disk-image-shrink-rootfs"
* Give container access to host's kernel modules
  ([MEN-2255](https://tracker.mender.io/browse/MEN-2255))
* Support compiling Mender client in mender-convert container.
* Document missing options in the scripts
  ([MEN-2248](https://tracker.mender.io/browse/MEN-2248))
* Store sector size in raw/mender disk image related arrays
  ([MEN-2242](https://tracker.mender.io/browse/MEN-2242))
* Avoid duplicate content in cmdline.txt
* rpi: update to 2018.07 U-boot
  ([MEN-2198](https://tracker.mender.io/browse/MEN-2198))
* Add --storage-total-size-mb option to mender-convert tool
  ([MEN-2242](https://tracker.mender.io/browse/MEN-2242))
* Make tool ready for handling input images containing 3 partitions
  ([MEN-2207](https://tracker.mender.io/browse/MEN-2207))
* Allow to use "--demo" flag with any given server type
* Use local (checked out) version of mender-convert inside container
* Support passing mender-convert arguments to docker-mender-convert directly
* remove expert commands
* Refactor mender-convert to use make install target
  ([MEN-2411](https://tracker.mender.io/browse/MEN-2411))
* Improve documentation
* Set production/demo intervals conditionally
  ([MEN-2248](https://tracker.mender.io/browse/MEN-2248))
* Optimizations to speed up conversion, utilizing sparse
  images.
* remove dependency on gcc6
* Install GRUB bootloader to Mender image based on Yocto image for qemu x86-64
  ([MEN-2207](https://tracker.mender.io/browse/MEN-2207))


## meta-mender thud-v2019.05

_Released 05.07.2019_

### Statistics

A total of 323 lines added, 204 removed (delta 119)

| Developers with the most changesets | |
|---|---|
| Kristian Amlie | 15 (68.2%) |
| Drew Moseley | 3 (13.6%) |
| Lluis Campos | 2 (9.1%) |
| Mirza Krak | 2 (9.1%) |

| Developers with the most changed lines | |
|---|---|
| Kristian Amlie | 396 (91.7%) |
| Mirza Krak | 17 (3.9%) |
| Drew Moseley | 16 (3.7%) |
| Lluis Campos | 3 (0.7%) |

| Developers with the most lines removed | |
|---|---|
| Mirza Krak | 13 (6.4%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 22 (100.0%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 432 (100.0%) |

| Employers with the most hackers (total 4) | |
|---|---|
| Northern.tech | 4 (100.0%) |


### Changelogs

#### meta-mender (thud-v2019.05)

New changes in meta-mender since thud-v2019.03:

* Add missing build dep on "xz" in Mender Artifact recipes for
  3.0.x versions
* Add recipes for mender-1.7.1 and mender-artifact-2.4.1.
* mender: Do not exclude missing directories.
* Add recipes for mender-2.0.0 and mender-artifact-3.0.0.
  Note that these recipes are not enabled by default in thud. If you
  want to use them, you have to add this to your build configuration:
  ```
  PREFERRED_VERSION_pn-mender = "2.%"
  PREFERRED_VERSION_pn-mender-artifact = "3.%"
  PREFERRED_VERSION_pn-mender-artifact-native = "3.%"
  ```
* Fix error message `Incorrect Usage: flag provided but not defined: -f`
* Add new liblzma dependency for the client.
* linux-raspberrypi-rt: Add mender settings for the PREEMPT_RT kernel.
* Fix mender 2.0.x and mender-artifact 3.0.x recipes to use the
  correct branches when fetching the source.


## Mender 2.0.0

_Released 05.07.2019_

### Statistics

A total of 52848 lines added, 37382 removed (delta 15466)

| Developers with the most changesets | |
|---|---|
| Manuel Zedel | 233 (34.0%) |
| Kristian Amlie | 190 (27.7%) |
| Marcin Chalczynski | 57 (8.3%) |
| Lluis Campos | 55 (8.0%) |
| Michael Clelland | 52 (7.6%) |
| Krzysztof Jaskiewicz | 39 (5.7%) |
| Ole Petter Orhagen | 19 (2.8%) |
| Eystein Måløy Stenberg | 10 (1.5%) |
| Oleksandr Miliukov | 8 (1.2%) |
| Adam Podogrocki | 4 (0.6%) |

| Developers with the most changed lines | |
|---|---|
| Manuel Zedel | 25958 (42.7%) |
| Kristian Amlie | 19328 (31.8%) |
| Krzysztof Jaskiewicz | 4561 (7.5%) |
| Marcin Chalczynski | 3028 (5.0%) |
| Ole Petter Orhagen | 2865 (4.7%) |
| Michael Clelland | 2299 (3.8%) |
| Lluis Campos | 1488 (2.4%) |
| Michael Zimmermann | 415 (0.7%) |
| Jeremy Trimble | 220 (0.4%) |
| Adam Podogrocki | 188 (0.3%) |

| Developers with the most lines removed | |
|---|---|
| Krzysztof Jaskiewicz | 2866 (7.7%) |
| Manuel Zedel | 312 (0.8%) |

| Developers with the most signoffs (total 4) | |
|---|---|
| Kristian Amlie | 4 (100.0%) |

| Developers with the most report credits (total 3) | |
|---|---|
| Mario Kozjak | 2 (66.7%) |
| Jeremy Trimble | 1 (33.3%) |

| Developers who gave the most report credits (total 3) | |
|---|---|
| Kristian Amlie | 3 (100.0%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 574 (83.8%) |
| RnDity | 100 (14.6%) |
| Two Six Labs, LLC | 3 (0.4%) |
| andreas@fatal.se | 2 (0.3%) |
| Systems Engineering & Assessment Ltd | 1 (0.1%) |
| jgitlin@goboomtown.com | 1 (0.1%) |
| pannen@gmail.com | 1 (0.1%) |
| yongjhih@gmail.com | 1 (0.1%) |
| grandcentrix GmbH | 1 (0.1%) |
| Election Systems & Software | 1 (0.1%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 52156 (85.8%) |
| RnDity | 7777 (12.8%) |
| grandcentrix GmbH | 415 (0.7%) |
| Two Six Labs, LLC | 220 (0.4%) |
| Systems Engineering & Assessment Ltd | 117 (0.2%) |
| andreas@fatal.se | 75 (0.1%) |
| yongjhih@gmail.com | 42 (0.1%) |
| Election Systems & Software | 16 (0.0%) |
| pannen@gmail.com | 3 (0.0%) |
| jgitlin@goboomtown.com | 1 (0.0%) |

| Employers with the most signoffs (total 4) | |
|---|---|
| Northern.tech | 4 (100.0%) |

| Employers with the most hackers (total 21) | |
|---|---|
| Northern.tech | 10 (47.6%) |
| RnDity | 3 (14.3%) |
| grandcentrix GmbH | 1 (4.8%) |
| Two Six Labs, LLC | 1 (4.8%) |
| Systems Engineering & Assessment Ltd | 1 (4.8%) |
| andreas@fatal.se | 1 (4.8%) |
| yongjhih@gmail.com | 1 (4.8%) |
| Election Systems & Software | 1 (4.8%) |
| pannen@gmail.com | 1 (4.8%) |
| jgitlin@goboomtown.com | 1 (4.8%) |


### Changelogs

#### deployments (1.7.0)

New changes in deployments since 1.7.0b1:

* artifact object extended with optional "size" field
* Update to latest mender-artifact dependency.

New changes in deployments since 1.6.0:

* Adjust go test files to reflect changes in API
  ([MEN-2309](https://tracker.mender.io/browse/MEN-2309))
* Updated the vendor dependency on mender-artifact
* Update deployments service with mender artifact v3 format changes
  ([MEN-2309](https://tracker.mender.io/browse/MEN-2309))
* The Dockerfile has been changed to build using the multi-stage container build
  pattern, and now builds the deployments binary in one build step, and then
  copies the binary over to the production environment based on alpine:3.6. This
  change should help keep builds consistent across all services.

#### deviceauth (2.0.0)

New changes in deviceauth since 1.7.0:

* Devauth management API v1 and admission API removed.

#### gui (2.0.0)

New changes in gui since 2.0.0b1:

* Device list times no longer change on expansion
  ([MEN-2366](https://tracker.mender.io/browse/MEN-2366))
* show total artifact size in ui + clarify uncompressed size

New changes in gui since 1.7.0:

* Allow to accept multiple pending devices at one time
* schedule a new deployment to all devices within a group, except just the first 100
* Bugfix: Ensure "already installed" displays correctly in deployment report
* Update to deviceauth API v2 and use device authsets for admit-on-request flow
* Fixed single device selection in the device list UI, which could remove device selection otherwise
* show ungrouped devices in a visibly separated list entry
* more device identity attributes are now able to select, depending on their popularity
* fix an issue that prevented deployments to filtered devices
* more device identity attributes are now able to select, depending on their popularity
* multiple payloads in an artifact are now shown in the artifact list
* schedule a new deployment to all devices within a group, except just the first 100
* Fixed bug where finished deployments continue to display "in progress" when report is kept open
* multiple payloads in an artifact are now shown in the artifact list
* Allow click-to-retry for deployments with failures
* Allow to accept multiple pending devices at one time
* introduced devices information on the dashboard
* Fixed bug where finished deployments continue to display "in progress" when report is kept open
* Make Artifact selector more scalable with autocomplete
* introduced devices information on the dashboard

#### integration (2.0.0)

New changes in integration since 2.0.0b1:

* Upgrade deployments to 1.7.0.
* Upgrade deviceauth to 2.0.0.
* Upgrade gui to 2.0.0.
* Upgrade inventory to 1.6.0.
* Upgrade mender to 2.0.0.
* Upgrade mender-api-gateway-docker to 2.0.0.
* Upgrade mender-artifact to 3.0.0.
* Upgrade mender-conductor to 1.3.0.
* Upgrade mender-conductor-enterprise to 1.3.0.
* Resolve docker credentials problems in integration
  ([MEN-2408](https://tracker.mender.io/browse/MEN-2408))

New changes in integration since 1.7.0:

* Add statistics generator script, and start doing statistics
  on code development for each release.
  ([MEN-2206](https://tracker.mender.io/browse/MEN-2206))
* logo pushed as in the case of mendersoftware/mender repo
* Upgrade deployments to 1.7.0b1.
* Upgrade deviceauth to 2.0.0b1.
* Upgrade gui to 2.0.0b1.
* Upgrade inventory to 1.6.0b1.
* Upgrade mender to 2.0.0b1.
* Upgrade mender-artifact to 3.0.0b1.
* Upgrade mender-conductor to 1.3.0b1.
* Upgrade mender-conductor-enterprise to 1.3.0b1.
* Ignore author's own signoff when generating release statistics.
* Integration tests for client DB migration.
  ([MEN-2311](https://tracker.mender.io/browse/MEN-2311))
* update conductor dependencies - elasticsearch and redis
* Fix docker version detection
* Added integration test for an Artifact without any compression.
  ([MEN-2224](https://tracker.mender.io/browse/MEN-2224))
* docker-compose: add mender-conductor to mender-device-auth dependencies

#### inventory (1.6.0)

New changes in inventory since 1.5.0:

* Allow filter with ":"

#### mender (2.0.0)

New changes in mender since 2.0.0b1:

* Version files are now allowed to contain a newline character. Also
  some minor changes, as readVersion now accepts an io.Reader, and files are
  opened outside of the function. This means that the error message is now
  consistent for all the uses of readVersion.
  ([MEN-2318](https://tracker.mender.io/browse/MEN-2318))
* file-install modules: Don't destroy original before we know we have a backup.
* Fix File Install UM to not wipe out dest_dir on single file installs
* standalone: Fix artifact committing not working after upgrading from 1.x.
  ([MEN-2465](https://tracker.mender.io/browse/MEN-2465))
* Deprecate old file-install Update Module and create instead
  two new ones: single-file-install and file-tree-install. These have a
  simpler logic and clearer scope. See for details.
  ([MEN-2442](https://tracker.mender.io/browse/MEN-2442))
* Don't push network interfaces without a mac address to inventory
* Disallow installing file trees on root destination dir for
  File Install Update Module
* Make sure ARM64 is included in bootloader integration inventory.
* Mender no longer misidentifies LVM volumes.
  ([MEN-2302](https://tracker.mender.io/browse/MEN-2302))
* Update modules: Implement `NeedsArtifactReboot` -> `Automatic`.
  ([MEN-2011](https://tracker.mender.io/browse/MEN-2011))

New changes in mender since 1.7.0:

* Bugfix: State-script error code in Sync-Enter causes infinite loop
  ([MEN-2195](https://tracker.mender.io/browse/MEN-2195))
* Allow rootfsPartA and rootfsPartB to be symlinks
* Rewrite AuthorizeWaitState to fix an infinite loop bug
  ([MEN-2195](https://tracker.mender.io/browse/MEN-2195))
* Modify design for exec.Cmd stdout/stderr logging
* Place UM generator scripts in a dedicated folder
  ([MEN-2371](https://tracker.mender.io/browse/MEN-2371))
* Write Update Module to do file(s) install
  ([MEN-2371](https://tracker.mender.io/browse/MEN-2371))
* Set StateScriptTimeout default to 1h
  ([MEN-2409](https://tracker.mender.io/browse/MEN-2409))
* Add source-installation instructions to README.md.
* Add `rootfs-image-v2` as a demonstration of how to
  reimplement Mender's `rootfs-image` update type as an update module.
  It's also useful as inspiration if users want to make their own
  slightly tweaked rootfs-image type.
  ([MEN-2392](https://tracker.mender.io/browse/MEN-2392))
* Swapped definition of StateScriptRetryTimeout and
  StateScriptRetryInterval for the names to represent what they are
  actually doing. This change breaks compatibility with current usage of
  these configurable parameters. See documentation for correct usage.
  ([MEN-2409](https://tracker.mender.io/browse/MEN-2409))
* Updated the copyright year to 2019 in LICENSE.
* Write update module for doing container setup
  ([MEN-2232](https://tracker.mender.io/browse/MEN-2232))
* Add example update modules for shell commands and pkg installs.
* Remove misleading warning message when ServerCert is missing.
* Remove jq dependency for file-install Update Module
* Implement initial version of update modules.
  ([MEN-2000](https://tracker.mender.io/browse/MEN-2000))
* Add support for Mender Artifact format version 3.
  ([MEN-2000](https://tracker.mender.io/browse/MEN-2000))
* Artifact name is now stored in the local database, and
  `/etc/mender/artifact_info` acts only as a fallback if no name has
  been stored yet. This is typically the case for devices provisioned
  directly from a disk image. Scripts should use the client
  `-show-artifact` argument instead of parsing the file.
  ([MEN-2000](https://tracker.mender.io/browse/MEN-2000))
* `-rootfs` argument has been removed and replaced with the
  `-install` argument, which works the same way.
  ([MEN-2000](https://tracker.mender.io/browse/MEN-2000))
* Mender now runs a stripped down set of state scripts when
  installing artifacts in standalone mode, and the `-f` flag is no
  longer required to install such artifacts, nor is it valid. The
  scripts that run are:
  * `Download` scripts
  * `ArtifactInstall` scripts
  * `ArtifactCommit` scripts
  * `ArtifactRollback` scripts
  * `ArtifactFailure` scripts
  Reboot scripts do not run, so these must be handled manually in
  standalone mode.
  ([MEN-2000](https://tracker.mender.io/browse/MEN-2000))
* Behavior change: `ArtifactCommit_Error` scripts now run
  after an `ArtifactCommit_Leave` script has returned an error.
  ([MEN-2000](https://tracker.mender.io/browse/MEN-2000))
* Bugfix in killing mechanism for State Scripts
  timing out ([MEN-2409](https://tracker.mender.io/browse/MEN-2409))
* Update vendored dependency net/http2 to latest version
* Support installing most files using Makefile `install` target.
  The device_type file is not supported, since it is highly hardware
  specific. Also the configuration will be very bare bones, and will
  require changes unless Hosted Mender is being used.
  ([MEN-2383](https://tracker.mender.io/browse/MEN-2383))
* Make output from `-show-artifact` easier to consume by limiting logging.
* Fix state logic for the case of actual wait
  ([MEN-2195](https://tracker.mender.io/browse/MEN-2195))
* Properly fail the update when writes to the underlying storage fail.
  ([MEN-2285](https://tracker.mender.io/browse/MEN-2285))
* Work around occasional OOM bug in mmc driver.
  ([MEN-2285](https://tracker.mender.io/browse/MEN-2285))
* Make sure state directory is created if it doesn't exist.

#### mender-artifact (3.0.0)

New changes in mender-artifact since 3.0.0b1:

* checking if fsck is on path and returing error if not.
* Fix name modify command for rootfs-image Artifacts
  ([MEN-2488](https://tracker.mender.io/browse/MEN-2488))
* `mender-convert` modify for Update Module Artifacts will only
  work for options that change the headers or meta-data of the Artifact;
  curently only the Artifact name.
  ([MEN-2487](https://tracker.mender.io/browse/MEN-2487))
* `mender-artifact modify` does not support anymore signing the
  Artifact after the modification. Use `mender-convert sign` after the
  modification to sign the Artifact.
  ([MEN-2486](https://tracker.mender.io/browse/MEN-2486))

New changes in mender-artifact since 2.4.0:

* add support for uncompressed updates
  ([MEN-2224](https://tracker.mender.io/browse/MEN-2224))
* mender-artifact tool now supports removing a file in either an sdimg,
  or in a Mender Artifact, with the rm command.
  ([MEN-2331](https://tracker.mender.io/browse/MEN-2331))
* FIX: mender-artifact cat now cleans up resources on write-errors.
* Implement reading and writing support for update modules.
  ([MEN-2004](https://tracker.mender.io/browse/MEN-2004))
* Change rootfs-image `-u` argument to `-f`.
  Similarly, change `--update` to `--file`.
  ([MEN-2286](https://tracker.mender.io/browse/MEN-2286))
* Due to some faulty logic in modify.go:modifyArtifact, the sdimg's
  provided were modified, but not repacked. This fix updates the logic, and added
  a test specifically for sdimg, as they we're non-existent.
  ([MEN-2294](https://tracker.mender.io/browse/MEN-2294))
* fixes issue when binary dependencies are not in PATH
  ([MEN-2180](https://tracker.mender.io/browse/MEN-2180))
* Validate the data update files names in payload filename
  ([MEN-2319](https://tracker.mender.io/browse/MEN-2319))
* Mender-artifactV3: Bump the artifact-version protocol to version 3.
* Report a human readable error in case the artifact payload is not ext4.
* Add support for compressing artifacts using LZMA.

#### mender-conductor (1.3.0)

New changes in mender-conductor since 1.2.0:

* upgrade conductor to the latest version (2.2.0)
* Timestamp changed to ISO8601

#### mender-conductor-enterprise (1.3.0)

New changes in mender-conductor-enterprise since 1.2.0:

* Debug logging added to email preparer
* Version update from 1.8.1 to 1.8.9 for python conductor client
* Complete time format added in entrypoint script
* Bugfix for email preparer


## meta-mender rocko-v2019.04

_Released 04.25.2019_

### Statistics

A total of 582 lines added, 209 removed (delta 373)

| Developers with the most changesets | |
|---|---|
| Kristian Amlie | 19 (67.9%) |
| Lluis Campos | 5 (17.9%) |
| Drew Moseley | 1 (3.6%) |
| Ole Petter Orhagen | 1 (3.6%) |
| Stoyan Bogdanov | 1 (3.6%) |
| Mirza Krak | 1 (3.6%) |

| Developers with the most changed lines | |
|---|---|
| Kristian Amlie | 575 (85.2%) |
| Lluis Campos | 56 (8.3%) |
| Mirza Krak | 21 (3.1%) |
| Drew Moseley | 14 (2.1%) |
| Stoyan Bogdanov | 8 (1.2%) |
| Ole Petter Orhagen | 1 (0.1%) |

| Developers with the most lines removed | |
|---|---|
| Lluis Campos | 35 (16.7%) |

| Developers with the most signoffs (total 2) | |
|---|---|
| Maciej Borzecki | 1 (50.0%) |
| Drew Moseley | 1 (50.0%) |

| Developers with the most report credits (total 1) | |
|---|---|
| Denis Mosolov | 1 (100.0%) |

| Developers who gave the most report credits (total 1) | |
|---|---|
| Kristian Amlie | 1 (100.0%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 27 (96.4%) |
| Konsulko Group | 1 (3.6%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 667 (98.8%) |
| Konsulko Group | 8 (1.2%) |

| Employers with the most signoffs (total 2) | |
|---|---|
| Northern.tech | 1 (50.0%) |
| RnDity | 1 (50.0%) |

| Employers with the most hackers (total 6) | |
|---|---|
| Northern.tech | 5 (83.3%) |
| Konsulko Group | 1 (16.7%) |


### Changelogs

#### meta-mender (rocko-v2019.04)

New changes in meta-mender since rocko-v2018.11.2:

* allow IMAGE_BOOTLOADER_BOOTSECTOR_OFFSET to be aligend to 512 bytes
  ([MEN-1845](https://tracker.mender.io/browse/MEN-1845))
* Fix missing wpa_supplicant in Raspberry Pi demo images.
* Add mender 1.6.1 and 1.7.0 recipes.
* Add mender-artifact 2.3.1 and 2.4.0 recipes.
* mender-helpers.bbclass: Add NVMe support
* Adapt to new flags in mender-artifact-3.0.0.
* Some core update modules can now be installed by adding
  `modules` to the `PACKAGECONFIG` variable of `mender`. They are
  included by default when using the meta-mender-demo layer.
  ([MEN-2383](https://tracker.mender.io/browse/MEN-2383))
* Install `mender-data-dir.service` to create `/data/mender` directory.
* Add mender-2.0.0b1 and mender-artifact-3.0.0b1.
* Add canary value to U-Boot env to catch bootloader/user-space mismatch.
* Fix error message `Incorrect Usage: flag provided but not defined: -f`


## meta-mender sumo-v2019.04

_Released 04.25.2019_

### Statistics

A total of 545 lines added, 720 removed (delta -175)

| Developers with the most changesets | |
|---|---|
| Kristian Amlie | 17 (63.0%) |
| Lluis Campos | 4 (14.8%) |
| Mirza Krak | 2 (7.4%) |
| Drew Moseley | 1 (3.7%) |
| Manuel Dipolt | 1 (3.7%) |
| Ole Petter Orhagen | 1 (3.7%) |
| Stoyan Bogdanov | 1 (3.7%) |

| Developers with the most changed lines | |
|---|---|
| Mirza Krak | 551 (47.4%) |
| Kristian Amlie | 533 (45.8%) |
| Lluis Campos | 55 (4.7%) |
| Drew Moseley | 14 (1.2%) |
| Stoyan Bogdanov | 8 (0.7%) |
| Manuel Dipolt | 1 (0.1%) |
| Ole Petter Orhagen | 1 (0.1%) |

| Developers with the most lines removed | |
|---|---|
| Mirza Krak | 550 (76.4%) |
| Lluis Campos | 36 (5.0%) |

| Developers with the most signoffs (total 1) | |
|---|---|
| Drew Moseley | 1 (100.0%) |

| Developers with the most report credits (total 1) | |
|---|---|
| Denis Mosolov | 1 (100.0%) |

| Developers who gave the most report credits (total 1) | |
|---|---|
| Kristian Amlie | 1 (100.0%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 25 (92.6%) |
| Konsulko Group | 1 (3.7%) |
| manuel@linux-home.at | 1 (3.7%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 1154 (99.2%) |
| Konsulko Group | 8 (0.7%) |
| manuel@linux-home.at | 1 (0.1%) |

| Employers with the most signoffs (total 1) | |
|---|---|
| Northern.tech | 1 (100.0%) |

| Employers with the most hackers (total 7) | |
|---|---|
| Northern.tech | 5 (71.4%) |
| Konsulko Group | 1 (14.3%) |
| manuel@linux-home.at | 1 (14.3%) |


### Changelogs

#### meta-mender (sumo-v2019.04)

New changes in meta-mender since sumo-v2018.12:

* mender-helpers.bbclass: Add NVMe support
* add 'rootwait' to bootargs
* Fix data directory not being empty on rootfs.
  ([MEN-2290](https://tracker.mender.io/browse/MEN-2290))
* Adapt to new flags in mender-artifact-3.0.0.
* Some core update modules can now be installed by adding
  `modules` to the `PACKAGECONFIG` variable of `mender`. They are
  included by default when using the meta-mender-demo layer.
  ([MEN-2383](https://tracker.mender.io/browse/MEN-2383))
* Install `mender-data-dir.service` to create `/data/mender` directory.
* Change variable to access ubi dataimg, points now to the symlink to prevent yocto rebuild error when timestamp/name of ubimg have changed
* Add mender-2.0.0b1 and mender-artifact-3.0.0b1.
* Add canary value to U-Boot env to catch bootloader/user-space mismatch.
* Fix error message `Incorrect Usage: flag provided but not defined: -f`


## meta-mender thud-v2019.03

_Released 03.28.2019_

### Statistics

A total of 358 lines added, 95 removed (delta 263)

| Developers with the most changesets | |
|---|---|
| Kristian Amlie | 12 (75.0%) |
| Lluis Campos | 2 (12.5%) |
| Manuel Dipolt | 1 (6.2%) |
| Mirza Krak | 1 (6.2%) |

| Developers with the most changed lines | |
|---|---|
| Kristian Amlie | 350 (97.8%) |
| Lluis Campos | 6 (1.7%) |
| Manuel Dipolt | 1 (0.3%) |
| Mirza Krak | 1 (0.3%) |

| Top changeset contributors by employer | |
|---|---|
| Northern.tech | 15 (93.8%) |
| manuel@linux-home.at | 1 (6.2%) |

| Top lines changed by employer | |
|---|---|
| Northern.tech | 357 (99.7%) |
| manuel@linux-home.at | 1 (0.3%) |

| Employers with the most hackers (total 4) | |
|---|---|
| Northern.tech | 3 (75.0%) |
| manuel@linux-home.at | 1 (25.0%) |


### Changelogs

#### meta-mender (thud-v2019.03)

New changes in meta-mender since thud-v2019.02:

* Some core update modules can now be installed by adding
  `modules` to the `PACKAGECONFIG` variable of `mender`. They are
  included by default when using the meta-mender-demo layer.
  ([MEN-2383](https://tracker.mender.io/browse/MEN-2383))
* Install `mender-data-dir.service` to create `/data/mender` directory.
* Change variable to access ubi dataimg, points now to the symlink to prevent yocto rebuild error when timestamp/name of ubimg have changed
* grub: ensure "test" module is builtin
* Add mender-2.0.0b1 and mender-artifact-3.0.0b1.
* Adapt to new flags in mender-artifact-3.0.0.


## meta-mender thud-v2019.02

### Statistics

A total of 11 lines added, 2 removed (delta 9)

| Developers with the most changesets |           |
|-------------------------------------|-----------|
| Kristian Amlie                      | 2 (50.0%) |
| Moritz Fischer                      | 1 (25.0%) |
| Stoyan Bogdanov                     | 1 (25.0%) |

| Developers with the most changed lines |           |
|----------------------------------------|-----------|
| Stoyan Bogdanov                        | 8 (72.7%) |
| Kristian Amlie                         | 2 (18.2%) |
| Moritz Fischer                         | 1 (9.1%)  |

| Developers with the most report credits (total 1) |            |
|---------------------------------------------------|------------|
| Denis Mosolov                                     | 1 (100.0%) |

| Developers who gave the most report credits (total 1) |            |
|-------------------------------------------------------|------------|
| Kristian Amlie                                        | 1 (100.0%) |

| Top changeset contributors by employer |           |
|----------------------------------------|-----------|
| Northern.tech                          | 2 (50.0%) |
| Konsulko Group                         | 1 (25.0%) |
| Ettus Research                         | 1 (25.0%) |

| Top lines changed by employer |           |
|-------------------------------|-----------|
| Konsulko Group                | 8 (72.7%) |
| Northern.tech                 | 2 (18.2%) |
| Ettus Research                | 1 (9.1%)  |

| Employers with the most hackers (total 3) |           |
|-------------------------------------------|-----------|
| Konsulko Group                            | 1 (33.3%) |
| Northern.tech                             | 1 (33.3%) |
| Ettus Research                            | 1 (33.3%) |

### Changelogs

_Released 02.08.2019_

#### meta-mender (thud-v2019.02)

New changes in meta-mender since thud-v2019.01:

* mender-helpers.bbclass: Add NVMe support


## meta-mender thud-v2019.01

_Released 01.04.2019_

### Statistics

A total of 80 lines added, 103 removed (delta -23)

| Developers with the most changesets |           |
|-------------------------------------|-----------|
| Kristian Amlie                      | 4 (66.7%) |
| Ole Petter Orhagen                  | 1 (16.7%) |
| Mirza Krak                          | 1 (16.7%) |

| Developers with the most changed lines |             |
|----------------------------------------|-------------|
| Kristian Amlie                         | 158 (92.9%) |
| Mirza Krak                             | 11 (6.5%)   |
| Ole Petter Orhagen                     | 1 (0.6%)    |

| Developers with the most lines removed |            |
|----------------------------------------|------------|
| Kristian Amlie                         | 34 (33.0%) |

| Top changeset contributors by employer |            |
|----------------------------------------|------------|
| Northern.tech                          | 6 (100.0%) |

| Top lines changed by employer |              |
|-------------------------------|--------------|
| Northern.tech                 | 170 (100.0%) |

| Employers with the most hackers (total 3) |            |
|-------------------------------------------|------------|
| Northern.tech                             | 3 (100.0%) |


### Changelogs

#### meta-mender (thud-v2019.01)

New changes in meta-mender since thud-v2018.12:

* part-images: add missing u-boot:deploy dependency for ARM
* Add grub-mender-grubenv 1.2.1 recipe.
* Fix grub-editenv invocation on platforms where it is called
  grub2-editenv.
* Fix data directory not being empty on rootfs.
  ([MEN-2290](https://tracker.mender.io/browse/MEN-2290))


## meta-mender sumo-v2018.12

_Released 12.14.2018_

### Statistics

A total of 31 lines added, 39 removed (delta -8)

| Developers with the most changesets |            |
|-------------------------------------|------------|
| Kristian Amlie                      | 3 (100.0%) |

| Developers with the most changed lines |             |
|----------------------------------------|-------------|
| Kristian Amlie                         | 56 (100.0%) |

| Developers with the most lines removed |           |
|----------------------------------------|-----------|
| Kristian Amlie                         | 8 (20.5%) |

| Developers with the most signoffs (total 3) |            |
|---------------------------------------------|------------|
| Kristian Amlie                              | 3 (100.0%) |

| Top changeset contributors by employer |            |
|----------------------------------------|------------|
| Northern.tech                          | 3 (100.0%) |

| Top lines changed by employer |             |
|-------------------------------|-------------|
| Northern.tech                 | 56 (100.0%) |

| Employers with the most signoffs (total 3) |            |
|--------------------------------------------|------------|
| Northern.tech                              | 3 (100.0%) |

| Employers with the most hackers (total 1) |            |
|-------------------------------------------|------------|
| Northern.tech                             | 1 (100.0%) |

### Changelogs

#### meta-mender (sumo-v2018.12)

New changes in meta-mender since sumo-v2018.11.2:

* Fix missing wpa_supplicant in Raspberry Pi demo images.
* Add mender 1.6.1 and 1.7.0 recipes.
* Add mender-artifact 2.3.1 and 2.4.0 recipes.


## meta-mender thud-v2018.12

_Released 12.13.2018_

### Statistics

A total of 3145 lines added, 2930 removed (delta 215)

| Developers with the most changesets |            |
|-------------------------------------|------------|
| Kristian Amlie                      | 76 (73.1%) |
| Drew Moseley                        | 9 (8.7%)   |
| Michael Davis                       | 5 (4.8%)   |
| Adam Podogrocki                     | 3 (2.9%)   |
| Mirza Krak                          | 2 (1.9%)   |
| Marcin Pasinski                     | 2 (1.9%)   |
| David Bensoussan                    | 2 (1.9%)   |
| Dominik Adamski                     | 1 (1.0%)   |
| Leon Anavi                          | 1 (1.0%)   |
| Ole Petter Orhagen                  | 1 (1.0%)   |

| Developers with the most changed lines |              |
|----------------------------------------|--------------|
| Kristian Amlie                         | 3919 (70.7%) |
| Mirza Krak                             | 635 (11.5%)  |
| Adam Podogrocki                        | 512 (9.2%)   |
| Michael Davis                          | 228 (4.1%)   |
| Drew Moseley                           | 113 (2.0%)   |
| Marcin Pasinski                        | 82 (1.5%)    |
| Eystein Måløy Stenberg                 | 41 (0.7%)    |
| Dominik Adamski                        | 4 (0.1%)     |
| David Bensoussan                       | 2 (0.0%)     |
| Leon Anavi                             | 2 (0.0%)     |

| Developers with the most lines removed |             |
|----------------------------------------|-------------|
| Mirza Krak                             | 616 (21.0%) |
| Adam Podogrocki                        | 293 (10.0%) |
| Marcin Pasinski                        | 72 (2.5%)   |
| Drew Moseley                           | 24 (0.8%)   |

| Developers with the most signoffs (total 107) |            |
|-----------------------------------------------|------------|
| Kristian Amlie                                | 77 (72.0%) |
| Drew Moseley                                  | 10 (9.3%)  |
| Michael Davis                                 | 5 (4.7%)   |
| Adam Podogrocki                               | 3 (2.8%)   |
| Mirza Krak                                    | 2 (1.9%)   |
| Marcin Pasinski                               | 2 (1.9%)   |
| David Bensoussan                              | 2 (1.9%)   |
| Leon Anavi                                    | 1 (0.9%)   |
| Thomas Preston                                | 1 (0.9%)   |
| Ole Petter Orhagen                            | 1 (0.9%)   |

| Developers with the most report credits (total 2) |           |
|---------------------------------------------------|-----------|
| Michael Davis                                     | 1 (50.0%) |
| Stoyan Bogdanov                                   | 1 (50.0%) |

| Developers who gave the most report credits (total 2) |           |
|-------------------------------------------------------|-----------|
| Drew Moseley                                          | 1 (50.0%) |
| Leon Anavi                                            | 1 (50.0%) |

| Top changeset contributors by employer |            |
|----------------------------------------|------------|
| Northern.tech                          | 91 (87.5%) |
| Election Systems & Software            | 5 (4.8%)   |
| RnDity                                 | 4 (3.8%)   |
| Synapticon                             | 2 (1.9%)   |
| Konsulko Group                         | 1 (1.0%)   |
| Codethink Ltd.                         | 1 (1.0%)   |

| Top lines changed by employer |              |
|-------------------------------|--------------|
| Northern.tech                 | 4791 (86.5%) |
| RnDity                        | 516 (9.3%)   |
| Election Systems & Software   | 228 (4.1%)   |
| Synapticon                    | 2 (0.0%)     |
| Konsulko Group                | 2 (0.0%)     |
| Codethink Ltd.                | 2 (0.0%)     |

| Employers with the most signoffs (total 107) |            |
|----------------------------------------------|------------|
| Northern.tech                                | 93 (86.9%) |
| RnDity                                       | 5 (4.7%)   |
| Election Systems & Software                  | 5 (4.7%)   |
| Synapticon                                   | 2 (1.9%)   |
| Konsulko Group                               | 1 (0.9%)   |
| Codethink Ltd.                               | 1 (0.9%)   |

| Employers with the most hackers (total 12) |           |
|--------------------------------------------|-----------|
| Northern.tech                              | 6 (50.0%) |
| RnDity                                     | 2 (16.7%) |
| Election Systems & Software                | 1 (8.3%)  |
| Synapticon                                 | 1 (8.3%)  |
| Konsulko Group                             | 1 (8.3%)  |
| Codethink Ltd.                             | 1 (8.3%)  |

### Changelogs

#### meta-mender (thud-v2018.12)

New changes in meta-mender since sumo-v2018.11.2:

* Add mender-artifact 2.4.0b1 recipe.
* Make mkfs.ubifs and ubinize arguments a bit more customizable.
  The new variables `MENDER_FLASH_MINIMUM_IO_UNIT` and
  `MENDER_MAXIMUM_LEB_COUNT` have been introduced, which maps directly
  to the corresponding arguments of the two tools.
* Beaglebone builds no longer compatible with builds from sumo and older.
  The reason is that bootloader switched to GRUB. The old build type can
  be restored by removing `mender-grub` and adding `mender-uboot` to
  `DISTRO_FEATURES` using the `MENDER_FEATURES` variables.
* Fix `IMAGE_ROOTFS_EXCLUDE_PATH` failing when listing a non-existent path.
* Increase default u-boot MTD partition size to 1MiB.
* Fix inability to patch old u-boot variants of MTDPARTS and
  MTDIDS correctly.
  ([MEN-1849](https://tracker.mender.io/browse/MEN-1849))
* Add mender 1.7.0b1 recipe.
* Fix images not being modifiable by mender-artifact in thud and later.
* Add mender 1.5.1 recipe.
* Add mender 1.6.0 recipe.
* Add mender-artifact 2.3.0 recipe.
* Remove support for `loadaddr` variable and
  `CONFIG_LOADADDR` config setting in U-Boot. This only affects boards
  that use U-Boot as a first stage boot loader in order to use UEFI to
  load GRUB as the second stage boot loader. For most boards it should
  not be problematic, since most support `kernel_addr_r`. If there is
  a problem however, it might be necessary to forward port [this
  patch](https://github.com/mendersoftware/meta-mender/blob/b39aa8aeecdf2b8cce3dbcce25ec044073568348/meta-mender-core/recipes-bsp/u-boot/patches/0007-distro_bootcmd-Switch-bootefi-to-use-loadaddr-by-def.patch)
  to the U-Boot version in question.
* Fix boot directory being excluded from thud images
* Add some debug functionality to GRUB booting process.
  To use it, enable either or both of `debug-log` and `debug-pause` in
  `PACKAGECONFIG` for `grub-mender-grubenv`. The former enables debug
  logging in GRUB, which can be tweaked further by setting the
  `DEBUG_LOG_CATEGORY` variable. The latter pauses the boot process at
  strategic points during the boot, so that screen output can be
  captured before it is cleared or scrolls by.
* Fix build error when using any hard drive besides sda/hda, such as sdb.
* Images partitioned with GPT or MSDOS partition tables are
  now padded up to the nearest alignment specified in
  `MENDER_PARTITION_ALIGNMENT`. Previously the last block might be
  shorter.
* Remove meta-mender-orangepi and meta-mender-toradex-nxp
  as these will be moved to meta-mender-community for the next stable
  branch (thud)
* Make sure mtdimg is not truncated, but has its full length.
* Enable EXTERNALSRC to be used with u-boot-fw-utils-mender-auto-provided.
* Allow disabling auto-generated /etc/fstab
* mender: Enable systemd in mender-systemd FEATURE handling.
  As long as `mender-systemd` feature is enabled, it is no longer
  necessary to include the block:
  ```
  DISTRO_FEATURES_append = " systemd"
  VIRTUAL-RUNTIME_init_manager = "systemd"
  DISTRO_FEATURES_BACKFILL_CONSIDERED = "sysvinit"
  VIRTUAL-RUNTIME_initscripts = ""
  ```
* Add canary value to U-Boot env to catch bootloader/user-space mismatch.
* GRUB: Fix error about devicetree command not being found.
* Change default storage on x86 to memory card (mmcblk0).
* Reduce partitioning overhead by default.
  The current value of 4 * alignment is excessive, since we now take
  alignment into account when calculating rootfs size. Instead, only
  count overhead lost to partition table, which is 2 * alignment.
* mender: Allow overrides for MENDER_STORAGE_TOTAL_SIZE_MB_DEFAULT.
* Allow boot partition to be populated with normal package recipes.
* Fix `MENDER_GRUB_STORAGE_DEVICE` variable not being respected.
  ([MEN-2048](https://tracker.mender.io/browse/MEN-2048))
* GRUB: Make kernel console argument configurable using "console_bootargs".
  One can set this variable in some "xx_*_grub.cfg" script with an index
  lower than 10, in the grub-mender-grubenv recipe.
* uboot_auto_patch: Switch kernel address from `loadaddr`
  back to `kernel_addr_r`. This was discussed with U-Boot developers and
  is the proper address variable going forward.
* Fix incorrect Flash bad PEB calculation which led to wrong total image size.
  ([MEN-1849](https://tracker.mender.io/browse/MEN-1849))
* Add mender 1.6.1 and 1.7.0 recipes.
* Add mender-artifact 2.3.1 and 2.4.0 recipes.
* Auto-select correct `MENDER_STORAGE_DEVICE_BASE` scheme.
  This should rarely need to be set by anyone anymore.
* Fix confusing warning flood when MENDER_MTDIDS is unset in a UBI build.
* Switch image names from containing `MACHINE` to containing
  `MENDER_DEVICE_TYPE`. So for example, if you have a build for the
  raspberrypi3 machine type, with device type of "prod_rpi3", the image
  will now be called `core-image-minimal-prod_rpi3.sdimg` instead of
  `core-image-minimal-raspberrypi3.sdimg`.
* Fix console logging for systemd on QEMU.
* Fix build error when using GRUB and /dev/mmcblk storage device.
* Add specific patches for u-boot-toradex_2016.11.
  ([MEN-1849](https://tracker.mender.io/browse/MEN-1849))
* grub: Remove restriction that the core.img be at sector 1
* mender-uboot: Use hex for dev/part numbers in U-Boot.
* Delete all components from pre-1.5 Mender releases.
  Remove Mender 1.4.0 and 1.4.1 and Mender artifact 2.2.0.
* Introduce support for a standardized boot method on ARM
  using UEFI and GRUB. The UEFI boot standard is fully supported on ARM
  in theory, but few board manufacturers implement it in practice.
  Therefore U-Boot is still utilized, but acts only as a UEFI loader,
  and hence no U-Boot integration is needed. All boot scripts are then
  handled by GRUB, which needs no patching.
  ([MEN-1595](https://tracker.mender.io/browse/MEN-1595), [MEN-1659](https://tracker.mender.io/browse/MEN-1659))
* Add support for PARTUUID in grub-mender-grubenv script.
* Remove colibri-imx7-mender MACHINE type, replaced by colibri-imx7.
* Fix regression that removed boot flag from boot partition.
* Fix regression that caused Beaglebone to not boot.
* QEMU: Always try to run with KVM enabled, only fall back to emulation.
* Fix license checksum sometimes failing in
  `u-boot-fw-utils-mender-auto-provided` recipe when U-Boot fork has a
  slightly different README file.
* Add PARTUUID generation and integration
* Change default boot loader to GRUB on all non-UBI platforms.
  U-Boot will still be used on ARM platforms to provide UEFI that GRUB
  can use, but it will not be used for Mender integration. To opt out,
  and keep using traditional U-Boot integration, remove `mender-grub`,
  and add `mender-uboot` using the `MENDER_FEATURES` variables.
* Fixed support for raspberrypi3-64 and aarch64
* mender-uboot: Allow multi-digit partition/device nums.
* Add mender 1.6.0b1 and mender-artifact 2.3.0b1 recipes.
* Remove obsolete mender pre-1.4 and mender-artifact pre-2.2 recipes.
* Fix regression in QEMU launching after changing image name in 897195ddc3f.
* Replaced default yocto cfg file for grub pre configuration by the proper cfg file without redundant and erroneous search command.
* rpi: update U-boot patch to get rid of warning
* Fix incorrect license tag for mender-artifact recipe.
  Little practical difference, since they are all permissive licenses.
* Fix missing wpa_supplicant in Raspberry Pi demo images.
* GRUB: Pass kernel arguments from bootargs variable instead of hard coded.
  This allows it to be overridden or modified by adding a script snippet
  which sets the variable.
  Also log kernel messages to both screen and serial port by default,
  and have systemd log to serial port (last "console" argument,
  apparently it cannot log to both).
* Add support for GPT BIOS images
* Boot script recipe for demoing OTA updates


## mender-convert 1.0.0

_Released 12.13.2018_

### Statistics

A total of 4848 lines added, 1459 removed (delta 3389)

| Developers with the most changesets |            |
|-------------------------------------|------------|
| Adam Podogrocki                     | 32 (45.1%) |
| Dominik Adamski                     | 18 (25.4%) |
| Eystein Måløy Stenberg              | 13 (18.3%) |
| Mirza Krak                          | 6 (8.5%)   |
| Mika Tuupola                        | 1 (1.4%)   |
| Pierre-Jean Texier                  | 1 (1.4%)   |

| Developers with the most changed lines |              |
|----------------------------------------|--------------|
| Adam Podogrocki                        | 4297 (87.0%) |
| Eystein Måløy Stenberg                 | 324 (6.6%)   |
| Dominik Adamski                        | 241 (4.9%)   |
| Mirza Krak                             | 74 (1.5%)    |
| Mika Tuupola                           | 1 (0.0%)     |
| Pierre-Jean Texier                     | 1 (0.0%)     |

| Developers with the most lines removed |           |
|----------------------------------------|-----------|
| Mirza Krak                             | 33 (2.3%) |

| Developers with the most signoffs (total 70) |            |
|----------------------------------------------|------------|
| Adam Podogrocki                              | 31 (44.3%) |
| Dominik Adamski                              | 18 (25.7%) |
| Eystein Måløy Stenberg                       | 13 (18.6%) |
| Mirza Krak                                   | 6 (8.6%)   |
| Mika Tuupola                                 | 1 (1.4%)   |
| Pierre-Jean Texier                           | 1 (1.4%)   |

| Top changeset contributors by employer |            |
|----------------------------------------|------------|
| RnDity                                 | 50 (70.4%) |
| Northern.tech                          | 19 (26.8%) |
| tuupola@appelsiini.net                 | 1 (1.4%)   |
| Lafon Technologies                     | 1 (1.4%)   |

| Top lines changed by employer |              |
|-------------------------------|--------------|
| RnDity                        | 4538 (91.9%) |
| Northern.tech                 | 398 (8.1%)   |
| tuupola@appelsiini.net        | 1 (0.0%)     |
| Lafon Technologies            | 1 (0.0%)     |

| Employers with the most signoffs (total 70) |            |
|---------------------------------------------|------------|
| RnDity                                      | 49 (70.0%) |
| Northern.tech                               | 19 (27.1%) |
| tuupola@appelsiini.net                      | 1 (1.4%)   |
| Lafon Technologies                          | 1 (1.4%)   |

| Employers with the most hackers (total 6) |           |
|-------------------------------------------|-----------|
| RnDity                                    | 2 (33.3%) |
| Northern.tech                             | 2 (33.3%) |
| tuupola@appelsiini.net                    | 1 (16.7%) |
| Lafon Technologies                        | 1 (16.7%) |

### Changelogs

#### mender-convert (1.0.0)

Initial release of mender-convert! Some developer versions were tested along the
way, so here is the changelog since then:

* Make tool ready for handling input images containing 3 partitions
  ([MEN-2207](https://tracker.mender.io/browse/MEN-2207))
* Support passing mender-convert arguments to docker-mender-convert directly
* Switch to 1.6.0 Mender client as default for docker environment
* Use local (checked out) version of mender-convert inside container
* Support compiling Mender client in mender-convert container.
* compile mender during docker image creation
* Install GRUB bootloader to Mender image based on Yocto image for qemu x86-64
  ([MEN-2207](https://tracker.mender.io/browse/MEN-2207))
* fix image paths printed at end of conversion
* Docker environment for running mender-convert
* Create repartitioned Mender compliant image from Yocto image for qemu x86-64
  ([MEN-2207](https://tracker.mender.io/browse/MEN-2207))
* Avoid duplicate content in cmdline.txt
* Install Mender related files to Mender image based on Yocto image for qemu x86-64
  ([MEN-2207](https://tracker.mender.io/browse/MEN-2207))
* Increase default server retry interval from 1 to 30 seconds.
* Add version option for mender convert
  ([MEN-2257](https://tracker.mender.io/browse/MEN-2257))


## Mender 1.7.0

_Released 12.13.2018_

### Release statistics
A total of 25446 lines added, 6653 removed (delta 18793)

| Developers with the most changesets |             |
|-------------------------------------|-------------|
| Marcin Chalczynski                  | 104 (34.0%) |
| Krzysztof Jaskiewicz                | 71 (23.2%)  |
| Kristian Amlie                      | 47 (15.4%)  |
| Michael Clelland                    | 36 (11.8%)  |
| Maciej Mrowiec                      | 14 (4.6%)   |
| Ole Petter Orhagen                  | 7 (2.3%)    |
| Alf-Rune Siqveland                  | 6 (2.0%)    |
| Don Cross                           | 5 (1.6%)    |
| Eystein Måløy Stenberg              | 4 (1.3%)    |
| Marcin Pasinski                     | 3 (1.0%)    |

| Developers with the most changed lines |              |
|----------------------------------------|--------------|
| Michael Clelland                       | 9832 (35.8%) |
| Kristian Amlie                         | 6660 (24.3%) |
| Marcin Chalczynski                     | 5180 (18.9%) |
| Krzysztof Jaskiewicz                   | 3594 (13.1%) |
| Alf-Rune Siqveland                     | 1184 (4.3%)  |
| Maciej Mrowiec                         | 367 (1.3%)   |
| Ole Petter Orhagen                     | 207 (0.8%)   |
| Don Cross                              | 186 (0.7%)   |
| Tobias Klauser                         | 56 (0.2%)    |
| Mirza Krak                             | 55 (0.2%)    |

| Developers with the most lines removed |           |
|----------------------------------------|-----------|
| Tobias Klauser                         | 51 (0.8%) |
| Eystein Måløy Stenberg                 | 28 (0.4%) |

| Developers with the most signoffs (total 310) |             |
|-----------------------------------------------|-------------|
| Marcin Chalczynski                            | 104 (33.5%) |
| Krzysztof Jaskiewicz                          | 71 (22.9%)  |
| Kristian Amlie                                | 48 (15.5%)  |
| Michael Clelland                              | 36 (11.6%)  |
| Maciej Mrowiec                                | 14 (4.5%)   |
| Ole Petter Orhagen                            | 8 (2.6%)    |
| Alf-Rune Siqveland                            | 6 (1.9%)    |
| Don Cross                                     | 5 (1.6%)    |
| Eystein Måløy Stenberg                        | 4 (1.3%)    |
| Marcin Pasinski                               | 3 (1.0%)    |

| Top changeset contributors by employer |             |
|----------------------------------------|-------------|
| RnDity                                 | 175 (57.2%) |
| Northern.tech                          | 122 (39.9%) |
| cosinekitty@gmail.com                  | 5 (1.6%)    |
| Amarula Solutions                      | 1 (0.3%)    |
| jgitlin@goboomtown.com                 | 1 (0.3%)    |
| tklauser@distanz.ch                    | 1 (0.3%)    |
| Election Systems & Software            | 1 (0.3%)    |

| Top lines changed by employer |               |
|-------------------------------|---------------|
| Northern.tech                 | 18415 (67.1%) |
| RnDity                        | 8774 (32.0%)  |
| cosinekitty@gmail.com         | 186 (0.7%)    |
| tklauser@distanz.ch           | 56 (0.2%)     |
| Election Systems & Software   | 16 (0.1%)     |
| Amarula Solutions             | 2 (0.0%)      |
| jgitlin@goboomtown.com        | 1 (0.0%)      |

| Employers with the most signoffs (total 310) |             |
|----------------------------------------------|-------------|
| RnDity                                       | 175 (56.5%) |
| Northern.tech                                | 126 (40.6%) |
| cosinekitty@gmail.com                        | 5 (1.6%)    |
| tklauser@distanz.ch                          | 1 (0.3%)    |
| Election Systems & Software                  | 1 (0.3%)    |
| Amarula Solutions                            | 1 (0.3%)    |
| jgitlin@goboomtown.com                       | 1 (0.3%)    |

| Employers with the most hackers (total 17) |            |
|--------------------------------------------|------------|
| Northern.tech                              | 10 (58.8%) |
| RnDity                                     | 2 (11.8%)  |
| cosinekitty@gmail.com                      | 1 (5.9%)   |
| tklauser@distanz.ch                        | 1 (5.9%)   |
| Election Systems & Software                | 1 (5.9%)   |
| Amarula Solutions                          | 1 (5.9%)   |
| jgitlin@goboomtown.com                     | 1 (5.9%)   |


### Changelogs

#### deployments (1.6.0)

New changes in deployments since 1.5.0:

* Change image download link validity to 24h from 1h.
* Change image download link validity to 24h from 1h.
  ([MEN-2054](https://tracker.mender.io/browse/MEN-2054))

#### deviceauth (1.7.0)

New changes in deviceauth since 1.7.0b1:

* document management API v2

New changes in deviceauth since 1.6.0:

* do not synchronize data with device admission service
* docs: introduce version 2 of the management API
* fix database migration
* fix database migration
* management API v2 endpoint for getting devices
* v2 of GET /devices/<id>
* actually run migration 1.5.0
* actually run migration 1.5.0
* API v2 POST /devices endpoint (for preauthorizing devices)
* v2 of GET /devices/<id>

#### gui (1.7.0)

New changes in gui since 1.7.0b1:

* Fixed bug where finished deployments continue to display "in progress" when report is kept open

New changes in gui since 1.6.0:

* Update node modules
* Introduce new tabbed deployment layout
* Added 'Copy to clipboard' function to error messages throughout UI
* Add a date range filter to past deployments tab
* Add "copy link to device" button on expanded device view
* Add group filter to past devices tab
* Make Artifact selector more scalable with auto-complete
* Bugfix: Ensure "already installed" displays correctly in deployment report
* Allow click-to-retry for deployments with failures
* Update to deviceauth API v2 and use device authsets for admit-on-request flow

#### integration (1.7.0)

New changes in integration since 1.7.0b1:

* Upgrade deployments to 1.6.0.
* Upgrade deviceauth to 1.7.0.
* Upgrade gui to 1.7.0.
* Upgrade inventory to 1.5.0.
* Upgrade mender to 1.7.0.
* Upgrade mender-api-gateway-docker to 1.6.0.
* Upgrade mender-artifact to 2.4.0.
* Upgrade mender-cli to 1.1.0.
* Upgrade mender-conductor to 1.2.0.
* Upgrade mender-conductor-enterprise to 1.2.0.
* Upgrade useradm to 1.7.0.
* Add statistics generator script, and start doing statistics
  on code development for each release.
  ([MEN-2206](https://tracker.mender.io/browse/MEN-2206))

New changes in integration since 1.6.0:

* Increase bandwidth limit to 3 MB/s per device for demo setup.
* remove admission service from the setup
* remove admission service from the setup
* client: Use KVM automatically if available. Remove "./demo --kvm" option.
* Fix docker version detection
* Upgrade deployments to 1.6.0b1.
* Upgrade deviceauth to 1.7.0b1.
* Upgrade gui to 1.7.0b1.
* Upgrade inventory to 1.5.0b1.
* Upgrade mender to 1.7.0b1.
* Upgrade mender-api-gateway-docker to 1.6.0b1.
* Upgrade mender-artifact to 2.4.0b1.
* Upgrade mender-cli to 1.1.0b1.
* Upgrade mender-conductor to 1.2.0b1.
* Upgrade mender-conductor-enterprise to 1.2.0b1.
* Upgrade useradm to 1.7.0b1.

#### mender (1.7.0)

New changes in mender since 1.7.0b1:

* Allow rootfsPartA and rootfsPartB to be symlinks

New changes in mender since 1.6.0:

* FIX: Enabling compiling ppc64le
* Fix active partition detection when using non-native
  filesystems.
* Add inventory scripts for rootfs type and bootloader integration.
  ([MEN-2059](https://tracker.mender.io/browse/MEN-2059))
* New feature: Fail-over Mender server(s)
  ([MEN-1972](https://tracker.mender.io/browse/MEN-1972))
* New inventory script for "os" attribute, installed by default.
  ([MEN-2060](https://tracker.mender.io/browse/MEN-2060))
* Mender client now loads configuration settings from
  both /etc/mender/mender.conf and (if it exists)
  /var/lib/mender/mender.conf. The second file is located
  on the data partition, so it allows any subset of configuration
  changes to survive upgrades.
  ([MEN-2073](https://tracker.mender.io/browse/MEN-2073))
* Print a message to the mender log when the
  mender client has confirmed the authenticity of an
  artifact's digital signature.
  ([MEN-2152](https://tracker.mender.io/browse/MEN-2152))
* Fix update check not working under BusyBox.
  ([MEN-2159](https://tracker.mender.io/browse/MEN-2159))
* Add Community Code of Conduct
* Detect if inactive part is mounted and unmount
  ([MEN-2084](https://tracker.mender.io/browse/MEN-2084))
* Improve error message when running mender as non-root user
  ([MEN-2083](https://tracker.mender.io/browse/MEN-2083))

#### mender-api-gateway-docker (1.6.0)

New changes in mender-api-gateway-docker since 1.5.0:

* nginx conf: redirect /api/management/v1/admission calls to devicauth service
* redirection to /ui/ fixed
* use exact openresty version (1.13.6.2-0-alpine) instead of floating tag (alpine)
* json access logs format option is added

#### mender-artifact (2.4.0)

New changes in mender-artifact since 2.3.0:

* FIX: mender-artifact cp no longer renames the artifact.
* FIX: remove leftover tmp files from mender-artifact cp.
* FIX: mender-artifact no longer changes the names of the updates in an artifact
* Updated the JSON format of header-info version 3.
* A command of the form
  "mender-artifact validate unsigned.mender -k public.key"
  was incorrectly succeeding for an unsigned artifact when a public key
  was supplied. Supplying a public key indicates that the caller requires
  the artifact to contain a signature that matches that key.
  Now this command fails (exits with a nonzero value) as expected.
  ([MEN-2155](https://tracker.mender.io/browse/MEN-2155))
* FIX: Renaming a file across devices now works.
  ([MEN-2166](https://tracker.mender.io/browse/MEN-2166))
* FIX: mender-artifact cat,cp,modify etc no longer removes the update.
  Previously an update present in a directory, with the same name as the
  update present in an update would be removed as a result of what the
  functions thought was tmp-files.
  ([MEN-2171](https://tracker.mender.io/browse/MEN-2171))
* Fixed a bug that caused a command like
  "mender-artifact cat signed.mender:/etc/mender/artifact_info"
  to fail with the error:
  "failed to open the partition reader: err: error validating signature"
  There was a similar problem with the "cp" command, and also
  the "modify" command when no "-k" was present to replace the
  existing signature.

#### mender-conductor-enterprise (1.2.0)

New changes in mender-conductor-enterprise since 1.1.0:

* Latest template from Ralph.

#### useradm (1.7.0)

New changes in useradm since 1.6.0:

* Recover from unsuccessful attempt to create user.
* Enable common logging stack adding request access log and response timings.


## Mender 1.6.1

_Released 12.13.2018_

### Statistics

A total of 4690 lines added, 96 removed (delta 4594)

| Developers with the most changesets |            |
|-------------------------------------|------------|
| Kristian Amlie                      | 21 (75.0%) |
| Ole Petter Orhagen                  | 3 (10.7%)  |
| Marcin Pasinski                     | 2 (7.1%)   |
| Josh Gitlin                         | 1 (3.6%)   |
| Don Cross                           | 1 (3.6%)   |

| Developers with the most changed lines |              |
|----------------------------------------|--------------|
| Kristian Amlie                         | 4649 (99.1%) |
| Ole Petter Orhagen                     | 30 (0.6%)    |
| Don Cross                              | 8 (0.2%)     |
| Marcin Pasinski                        | 5 (0.1%)     |
| Josh Gitlin                            | 1 (0.0%)     |

| Developers with the most lines removed |          |
|----------------------------------------|----------|
| Marcin Pasinski                        | 3 (3.1%) |

| Developers with the most signoffs (total 28) |            |
|----------------------------------------------|------------|
| Kristian Amlie                               | 21 (75.0%) |
| Ole Petter Orhagen                           | 3 (10.7%)  |
| Marcin Pasinski                              | 2 (7.1%)   |
| Josh Gitlin                                  | 1 (3.6%)   |
| Don Cross                                    | 1 (3.6%)   |

| Top changeset contributors by employer |            |
|----------------------------------------|------------|
| Northern.tech                          | 26 (92.9%) |
| cosinekitty@gmail.com                  | 1 (3.6%)   |
| jgitlin@goboomtown.com                 | 1 (3.6%)   |

| Top lines changed by employer |              |
|-------------------------------|--------------|
| Northern.tech                 | 4684 (99.8%) |
| cosinekitty@gmail.com         | 8 (0.2%)     |
| jgitlin@goboomtown.com        | 1 (0.0%)     |

| Employers with the most signoffs (total 28) |            |
|---------------------------------------------|------------|
| Northern.tech                               | 26 (92.9%) |
| cosinekitty@gmail.com                       | 1 (3.6%)   |
| jgitlin@goboomtown.com                      | 1 (3.6%)   |

| Employers with the most hackers (total 5) |           |
|-------------------------------------------|-----------|
| Northern.tech                             | 3 (60.0%) |
| cosinekitty@gmail.com                     | 1 (20.0%) |
| jgitlin@goboomtown.com                    | 1 (20.0%) |

### Changelogs

#### integration (1.6.1)

New changes in integration since 1.6.0:

* Upgrade deviceadm to 1.4.1.
* Upgrade mender to 1.6.1.
* Upgrade mender-artifact to 2.3.1.
* Add statistics generator script, and start doing statistics
  on code development for each release.
  ([MEN-2206](https://tracker.mender.io/browse/MEN-2206))
* Fix docker version detection

#### mender (1.6.1)

New changes in mender since 1.6.0:

* Fix update check not working under BusyBox.
  ([MEN-2159](https://tracker.mender.io/browse/MEN-2159))
* Print a message to the mender log when the
  mender client has confirmed the authenticity of an
  artifact's digital signature.
  ([MEN-2152](https://tracker.mender.io/browse/MEN-2152))

#### mender-artifact (2.3.1)

New changes in mender-artifact since 2.3.0:

* FIX: Renaming a file across devices now works.
  ([MEN-2166](https://tracker.mender.io/browse/MEN-2166))
* FIX: mender-artifact cat,cp,modify etc no longer removes the update.
  Previously an update present in a directory, with the same name as the
  update present in an update would be removed as a result of what the
  functions thought was tmp-files.
  ([MEN-2171](https://tracker.mender.io/browse/MEN-2171))



## meta-mender sumo-v2018.11.2

_Released 11.16.2018_

#### meta-mender (sumo-v2018.11.2)

New changes in meta-mender since sumo-v2018.11:

* Add mender 1.7.0b1 recipe.
* Add mender-artifact 2.4.0b1 recipe.


## meta-mender sumo-v2018.11

_Released 11.12.2018_

#### meta-mender (sumo-v2018.11)

New changes in meta-mender since sumo-v2018.10:

* QEMU: Always try to run with KVM enabled, only fall back to emulation.


## meta-mender sumo-v2018.10

_Released 10.03.2018_

#### meta-mender (sumo-v2018.10)

New changes in meta-mender since sumo-v2018.09:

* Make sure mtdimg is not truncated, but has its full length.
* Add specific patches for u-boot-toradex_2016.11.
  ([MEN-1849](https://tracker.mender.io/browse/MEN-1849))
* Fix incorrect Flash bad PEB calculation which led to wrong total image size.
  ([MEN-1849](https://tracker.mender.io/browse/MEN-1849))
* Make mkfs.ubifs and ubinize arguments a bit more customizable.
  The new variables `MENDER_FLASH_MINIMUM_IO_UNIT` and
  `MENDER_MAXIMUM_LEB_COUNT` have been introduced, which maps directly
  to the corresponding arguments of the two tools.
* Fix inability to patch old u-boot variants of MTDPARTS and
  MTDIDS correctly.
  ([MEN-1849](https://tracker.mender.io/browse/MEN-1849))
* Fix confusing warning flood when MENDER_MTDIDS is unset in a UBI build.


## meta-mender sumo-v2018.09

_Released 09.13.2018_

#### meta-mender (sumo-v2018.09)

New changes in meta-mender since sumo-v2018.08:

* Fix regression in QEMU launching after changing image name in 897195ddc3f.
* GRUB: Pass kernel arguments from bootargs variable instead of hard coded.
  This allows it to be overridden or modified by adding a script snippet
  which sets the variable.
  Also log kernel messages to both screen and serial port by default,
  and have systemd log to serial port (last "console" argument,
  apparently it cannot log to both).
* Introduce support for a standardized boot method on ARM
  using UEFI and GRUB. The UEFI boot standard is fully supported on ARM
  in theory, but few board manufacturers implement it in practice.
  Therefore U-Boot is still utilized, but acts only as a UEFI loader,
  and hence no U-Boot integration is needed. All boot scripts are then
  handled by GRUB, which needs no patching.
  ([MEN-1595](https://tracker.mender.io/browse/MEN-1595), [MEN-1659](https://tracker.mender.io/browse/MEN-1659))
* Auto-select correct `MENDER_STORAGE_DEVICE_BASE` scheme.
  This should rarely need to be set by anyone anymore.
* Add some debug functionality to GRUB booting process.
  To use it, enable either or both of `debug-log` and `debug-pause` in
  `PACKAGECONFIG` for `grub-mender-grubenv`. The former enables debug
  logging in GRUB, which can be tweaked further by setting the
  `DEBUG_LOG_CATEGORY` variable. The latter pauses the boot process at
  strategic points during the boot, so that screen output can be
  captured before it is cleared or scrolls by.
* GRUB: Fix error about devicetree command not being found.
* Images partitioned with GPT or MSDOS partition tables are
  now padded up to the nearest alignment specified in
  `MENDER_PARTITION_ALIGNMENT`. Previously the last block might be
  shorter.
* Fix build error when using GRUB and /dev/mmcblk storage device.
* Fix build error when using any hard drive besides sda/hda, such as sdb.
* Fix `IMAGE_ROOTFS_EXCLUDE_PATH` failing when listing a non-existent path.
* Fix `MENDER_GRUB_STORAGE_DEVICE` variable not being respected.
  ([MEN-2048](https://tracker.mender.io/browse/MEN-2048))
* Allow disabling auto-generated /etc/fstab
* Boot script recipe for demoing OTA updates
* mender: Allow overrides for MENDER_STORAGE_TOTAL_SIZE_MB_DEFAULT.
* mender-uboot: Use hex for dev/part numbers in U-Boot.
* Add mender 1.5.1 recipe.
* Add mender 1.6.0 recipe.
* Add mender-artifact 2.3.0 recipe.


## Mender 1.6.0

_Released 09.18.2018_

#### deviceauth (1.6.0)

New changes in deviceauth since 1.5.0:

* Device object returned by API exposes new boolean attribute: "decommissioning" signifying devices that are currently going through removal process.

#### gui (1.6.0)

New changes in gui since 1.6.0b1:

* Added 'Copy to clipboard' function to error messages throughout UI
* Introduce new tabbed deployment layout
* Update node modules
* Bugfix: Ensure "already installed" displays correctly in deployment report

New changes in gui since 1.5.0:

* Add preauthorize devices section
* Cleaned up URL for filtering device list by ID or group:
  ([MEN-1875](https://tracker.mender.io/browse/MEN-1875))
* Add a global setting to store and use user-selected device identity attribute throughout UI
* Fixup: Add a link to mender docs for enabling wifi in hosted image

#### integration (1.6.0)

New changes in integration since 1.6.0b1:

* Upgrade deviceauth to 1.6.0.
* Upgrade gui to 1.6.0.
* Upgrade inventory to 1.4.1.
* Upgrade mender to 1.6.0.
* Upgrade mender-artifact to 2.3.0.
* Upgrade mender-cli to 1.0.1.
* Upgrade mender-conductor to 1.1.0.
* Upgrade mender-conductor-enterprise to 1.1.0.
* Upgrade useradm to 1.6.0.

New changes in integration since 1.5.0:

* Add mender-cli as a versioned repository under the Mender umbrella.
* Upgrade deviceauth to 1.6.0b1.
* Upgrade gui to 1.6.0b1.
* Upgrade inventory to 1.4.1b1.
* Upgrade mender to 1.6.0b1.
* Upgrade mender-artifact to 2.3.0b1.
* Upgrade mender-cli to 1.0.1b1.
* Upgrade mender-conductor to 1.1.0b1.
* Upgrade mender-conductor-enterprise to 1.1.0b1.
* Upgrade useradm to 1.6.0b1.
* demo: suppress warning on newer docker-compose versions
* consolidate to single mongodb server instance
* Change mongo definitions to map the correct path. /data is being mapped, but /data/db needs to.
* test_security.py: Ignore return code of grep.
* use common mongodb server instance with tenantadm

#### mender (1.6.0)

New changes in mender since 1.6.0b1:

* Fix active partition detection when using non-native
  filesystems.
* New inventory script for "os" attribute, installed by default.
  ([MEN-2060](https://tracker.mender.io/browse/MEN-2060))
* FIX: Enabling compiling ppc64le
* Add inventory scripts for rootfs type and bootloader integration.
  ([MEN-2059](https://tracker.mender.io/browse/MEN-2059))

New changes in mender since 1.5.0:

* FIXED: HTTP error 401 is not handled by all states
  ([MEN-1854](https://tracker.mender.io/browse/MEN-1854))
* ArtifactReboot_Enter scripts are no longer rerun
  if interrupted by an unexpected reboot. It will be treated
  as if Mender itself rebooted.
* Enable user to force an update-check locally
  The user can now force an update check by either running mender with the
  -check-update option, or send a signal [SIGUSR1] to the running mender process.
  ([MEN-1905](https://tracker.mender.io/browse/MEN-1905))
* Add automatic check for canary value in U-Boot environment
  to try to detect if there is a problem in the environment setup of
  U-Boot and/or the u-boot-fw-utils tools.
* Mender client key generator script
* log active partition before and after reboot.
  ([MEN-1880](https://tracker.mender.io/browse/MEN-1880))

#### mender-artifact (2.3.0)

New changes in mender-artifact since 2.3.0b1:

* FIX: mender-artifact cp no longer renames the artifact.
* FIX: remove leftover tmp files from mender-artifact cp.
* FIX: mender-artifact no longer changes the names of the updates in an artifact

New changes in mender-artifact since 2.2.0:

* Add boot partition as a modify candidate for artifact cp
* Add mtools as a dependency before installing from source, and in travis
* Testify/require files added to the vendor directory
* Small cleanup of license text. No legal difference, just
  makes it easier for the tooling.
* Install function added
* Added uefiimg as an option to the cp and cat commands
* modify any file using the mender-artifact tool
  ([MEN-1741](https://tracker.mender.io/browse/MEN-1741))
* add testify/require to vendor
* modify any file using the mender-artifact tool
  ([MEN-1741](https://tracker.mender.io/browse/MEN-1741))
* Mender-artifact can now copy to and read from the data partition
  ([MEN-1953](https://tracker.mender.io/browse/MEN-1953))
* run fsck before modifying image.
  ([MEN-1798](https://tracker.mender.io/browse/MEN-1798))

#### mender-conductor (1.1.0)

New changes in mender-conductor since 1.0.0:

* Extend logging with messages from conductor client library to stdout.
* Update conductor client library to 1.8.9


## meta-mender sumo-v2018.08

_Released 08.03.2018_

#### meta-mender (sumo-v2018.08)

New changes in meta-mender since sumo-v2018.07:

* Add mender 1.6.0b1 and mender-artifact 2.3.0b1 recipes.
* Fixed support for raspberrypi3-64 and aarch64
* Fix incorrect license tag for mender-artifact recipe.
  Little practical difference, since they are all permissive licenses.
* mender-uboot: Allow multi-digit partition/device nums.
* Fix license checksum sometimes failing in
  `u-boot-fw-utils-mender-auto-provided` recipe when U-Boot fork has a
  slightly different README file.


## meta-mender sumo-v2018.07

_Released 07.12.2018_

#### meta-mender (sumo-v2018.07)
* Warn when mender.conf settings conflict with Bitbake variables.
* Make sure that new-style "enp" network devices get DHCP address in demo.
* Delete all components from pre-1.3 Mender releases.
  All pre-1.3 releases are EOL.
* Rename IMAGE_BOOTLOADER* variables to MENDER_IMAGE_BOOTLOADER*.
* Fix lockfile error due to using system lock directory.
* Licence checksum updated in mender-artifact
* mender: Allow for forcing a specific KERNEL_IMAGETYPE.
* mender-uboot: Add MENDER_UBOOT_POST_SETUP_COMMANDS config point.
* Fix occasional inode corruption issue when re-launching a
  previously launched and saved QEMU image.
* QEMU: Limit client setup steps to run on first boot only.
* mender-qemu: increase qemu memory size to 256MiB.
* Let colibri-imx7 and vf boards be handled by automatic patching.
* Fixed issue with build due to unknown image linux-firmware-raspbian-bcm43430
* Fix mender not building if build and host architecture is the same.
* meta-mender-orangepi: Fix up u-boot
* Fix Linux kernel hanging when loaded via U-Boot/UEFI/GRUB
  on vexpress-qemu*.
  ([MEN-1657](https://tracker.mender.io/browse/MEN-1657))
* Add mender-1.3.1 and mender-artifact-2.1.2 recipes.
* Implement `IMAGE_ROOTFS_EXCLUDE_PATH` support. It works the
  following way: It contains a space separated list of directories,
  relative to the rootfs root (no beginning slash), and any directory
  specified will be omitted from the rootfs. If the directory ends in a
  slash, only the contents will be omitted, not the directory itself
  (useful for mount points). One can then set
  `do_image_<imagetype>[respect_exclude_path] = "1"` for certain image
  builders to prevent the exclusion and then add them back as separate
  partitions there.
* Support for `MENDER_DATA_PART_DIR` has been removed. Use
  recipe files to add files directly to the `/data` directory instead.
* mender: Create bmap files.
* tests: Filter out the data partition as the latest build artifact.
* example-state-scripts: Explicitly return 0 from scripts.
* uboot_auto_patch: Simplify definition placement at the expense of beauty.
  The resulting patch is uglier because the definitions go into a cross
  platform section which is not appropriate for upstream submission. But
  it does fix the case where unwanted ifdefs were "hiding" the added
  definitions.
* rpi_0_w: Setup Mender required defconfigs
* Implement GRUB and x86-64 support.
  ([MEN-1430](https://tracker.mender.io/browse/MEN-1430), [MEN-1432](https://tracker.mender.io/browse/MEN-1432), [MEN-1433](https://tracker.mender.io/browse/MEN-1433), [MEN-1434](https://tracker.mender.io/browse/MEN-1434), [MEN-1435](https://tracker.mender.io/browse/MEN-1435), [MEN-1436](https://tracker.mender.io/browse/MEN-1436))
* Implement qemux86-64 machine target.
  ([MEN-1430](https://tracker.mender.io/browse/MEN-1430), [MEN-1432](https://tracker.mender.io/browse/MEN-1432), [MEN-1433](https://tracker.mender.io/browse/MEN-1433), [MEN-1434](https://tracker.mender.io/browse/MEN-1434), [MEN-1435](https://tracker.mender.io/browse/MEN-1435), [MEN-1436](https://tracker.mender.io/browse/MEN-1436))
* mender: Conditionally add /uboot mount only for SDCards.
* Increased the demo mender-retry-polling interval
  ([MEN-1006](https://tracker.mender.io/browse/MEN-1006))
* meta-mender-toradex-nxp: Adapt colibri-imx7-mender to U-Boot autopatching
* Fix 'depends upon non-existent task' error in U-Boot recipes without auto patching.
* Use timedatectl, if available, to determine with time is synchronized.
* mender upgraded to 1.4.0.
* mender-artifact upgraded to 2.2.0.
* mender-qemu: More robust detection of MACHINE setting.
* beaglebone: Rename to beaglebone-yocto.
* Add mtdimg image type.
  The mtdimg type is an image type meant to be flashed to the entire
  Flash device, unlike the ubimg, which should only be flashed to the
  ubi area of the mtd device. Either one can be used depending on need.
  vexpress-nor image, used in QEMU, was also changed to take advantage
  of the new mtdimg image.
  ([MEN-1597](https://tracker.mender.io/browse/MEN-1597))
* Add LAYERSERIES_COMPAT settings to all Mender layers.
* Replace `MENDER_PARTITION_ALIGNMENT_KB` with
  `MENDER_PARTITION_ALIGNMENT`, which is in bytes.
* Rename `MENDER_STORAGE_RESERVED_RAW_SPACE` to
  `MENDER_RESERVED_SPACE_BOOTLOADER_DATA`, to better reflect what it is
  used for.
* Enable wifi in the raspberry-pi demo image by default.
  ([MEN-1804](https://tracker.mender.io/browse/MEN-1804))
* mender: Only create vfat boot partition if size is non-zero
* meta-mender-toradex-nxp: increase layer priority to 91
* Fix creating ubifs image.
* tests: Respect user set SSTATE_DIR and DL_DIR variables.
* Make sure auto provided fw-utils use virtual/bootloader setting if present.
* QEMU: Raise systemd service timeout so that it boots properly on slow hosts.
* Fix fstab sometimes not containing boot partition entry.
* Fix build error if `IMAGE_FSTYPES` contains the same entry more than once.
* Implement x86 BIOS support together with GRUB.
  It can be enabled by inheriting the `mender-full-bios` class, or by
  enabling the `mender-grub` and `mender-bios` features using
  `MENDER_FEATURES_ENABLE`.
  ([MEN-1845](https://tracker.mender.io/browse/MEN-1845))
* Client container init scripts are modified to accept MAC address for qemu through env var, `RANDOM_MAC`.
* added layer dependency on mender layer
* uboot_auto_configure: Fail immediately if a define cannot be added.
  Better than failing later at runtime, where the problem is much harder
  to debug.
* Warn on unused MENDER_.* variables
  ([MEN-1603](https://tracker.mender.io/browse/MEN-1603))
* uboot_auto_patch: Switch kernel address from `kernel_addr_r` to `loadaddr`.
* Remove unused IMAGE_UENV_TXT_FILE variable.
* Add U-Boot auto patching support for Flash based devices.
  The autopatcher will use UBI as storage medium for both the
  filesystems and the U-Boot environment. Mender requires a minimum of
  configuration: the `MENDER_MTDIDS` needs to be set for the board, and
  will normally go in the `conf/machine/<MACHINE>.conf` file for the
  board in question. See documentation for variables `MENDER_MTDIDS`,
  `MENDER_IS_IN_MTDID` and `MENDER_MTDPARTS` for more information.
  ([MEN-1597](https://tracker.mender.io/browse/MEN-1597))
* Partition alignment (`MENDER_PARTITION_ALIGNMENT`) on Flash
  devices using UBI is now aligned to the UBI LEB size, which in general
  is not a multiple of KiB.
  ([MEN-1597](https://tracker.mender.io/browse/MEN-1597))
* Add Mender 1.4.1 recipe.
* Clear IMAGE_NAME_SUFFIX for all image types.
* Fix "No rule to make target 'envtools'" error in some U-Boot builds.
* Pregenerate SSH keys for all QEMU images.
* Since the "beaglebone" machine name has changed in upstream
  to "beaglebone-yocto", add "beaglebone" to the
  `MENDER_DEVICE_TYPES_COMPATIBLE` default, so that older devices can
  upgrade even if they have the old device type.
* mender: Copy data partition images to the deploy dir.
* mender: Append to fstab rather than replacing it.
* Fix failed uboot.env install when mender-uboot feature is disabled.
* tests: Also check ARTIFACTIMG_FSTYPE for compatible images.
* uboot_auto_patch: Update to support U-Boot v2018.05.
* uboot_auto_patch: Add support for new Kconfig based
  defines.
* mender-uboot: Add MENDER_UBOOT_PRE_SETUP_COMMANDS config point.
* Add Mender 1.5.0 Beta recipe.
* Add mender-1.4.0b1 and mender-artifact-2.2.0b1 recipes.
* Add 'dataimg' as an image type.
  It contains the data partition filesystem which is normally part of
  the complete partitioned image. To enable it, add `dataimg` to
  `IMAGE_FSTYPES`.
  ([MEN-1879](https://tracker.mender.io/browse/MEN-1879))
* mender: Use only the basename to load DTBs.
* Add Mender 1.5.0 recipe.
* Document SDIMG_ROOTFS_TYPE settings for Raspberry Pi.
* Change rootfs size calculation so it takes alignment into account.
  This should fix a few corner cases, where the filesystems may all fit
  in terms of bytes, but still would not actually fit because of
  partition alignment.
* Added new state script to wait for time sync to complete.
* Drop creation of `authtentoken` file, which is unneeded now.
* Added basic support for orangepi boards
* mender: Cleanup IMAGE_FSTYPES.
* uboot_auto_configure: Handle tabs in defines correctly.


## meta-mender rocko-v2018.07

_Released 07.10.2018_

#### meta-mender (rocko-v2018.07)
* Clear IMAGE_NAME_SUFFIX for all image types.
* Use timedatectl, if available, to determine with time is synchronized.
* Change rootfs size calculation so it takes alignment into account.
  This should fix a few corner cases, where the filesystems may all fit
  in terms of bytes, but still would not actually fit because of
  partition alignment.
  Backported to Morty. MENDER_PARTITION_ALIGNMENT_KB instead
  of MENDER_PARTITION_ALIGNMENT.
* Fix Linux kernel hanging when loaded via U-Boot/UEFI/GRUB
  on vexpress-qemu*.
  ([MEN-1657](https://tracker.mender.io/browse/MEN-1657))
* Fix occasional inode corruption issue when re-launching a
  previously launched and saved QEMU image.
* QEMU: Limit client setup steps to run on first boot only.
* tests: Filter out the data partition as the latest build artifact.
* Licence checksum updated in mender-artifact
* Fixed issue with build due to unknown image linux-firmware-raspbian-bcm43430
* tests: Respect user set SSTATE_DIR and DL_DIR variables.
* Warn when mender.conf settings conflict with Bitbake variables.
* example-state-scripts: Explicitly return 0 from scripts.
* Client container init scripts are modified to accept MAC address for qemu through env var, `RANDOM_MAC`.
* tests: Also check ARTIFACTIMG_FSTYPE for compatible images.
* meta-mender-core: Clean spaces out of UBOOT_MACHINE.


## meta-mender rocko-v2018.06

_Released 06.05.2018_

#### meta-mender rocko-v2018.06
* Add Mender 1.5.0 recipe.
* Add Mender 1.4.1 recipe.
* Enable wifi in the raspberry-pi demo image by default.
  ([MEN-1804](https://tracker.mender.io/browse/MEN-1804))


## Mender v1.5.0

_Released 06.07.2018_

#### integration (1.5.0)
* Add mender-cli as a versioned repository under the Mender umbrella.
* Upgrade deployments to 1.5.0.
* Upgrade deviceadm to 1.4.0.
* Upgrade deviceauth to 1.5.0.
* Upgrade gui to 1.5.0.
* Upgrade inventory to 1.4.0.
* Upgrade mender to 1.5.0.
* Upgrade mender-api-gateway-docker to 1.5.0.
* Add mender-cli 1.0.0.
* Add mender-conductor 1.0.0.
* Add mender-conductor-enterprise 1.0.0.
* Upgrade useradm to 1.5.0.

#### mender (1.5.0)
* FIXED: HTTP error 401 is not handled by all states
  ([MEN-1854](https://tracker.mender.io/browse/MEN-1854))
* Mender client key generator script


## Mender v1.4.2

_Released 06.07.2018_

#### gui (1.4.1)
* Fix elusive bug which sometimes caused GUI to restart over
  and over due to not finding uglifyjs.

#### integration (1.4.2)
* Upgrade gui to 1.4.1.


## Mender v1.4.1

_Released 06.04.2018_

#### integration (1.4.1)
* Switched to using Intel x86_64 hardware accelerated client
  instead of ARM emulator.
* Add --kvm option to demo scripts to run client VM hardware accelerated.
* Switch default client container type to qemux86-64.
* Upgrade mender to 1.4.1.

#### mender (1.4.1)
* FIXED: Log writes not flushed from memory
  ([MEN-1726](https://tracker.mender.io/browse/MEN-1726))
* Regenerate keys on all key errors, not just when keys are missing.
  ([MEN-1823](https://tracker.mender.io/browse/MEN-1823))
* Mender client key generator script


## meta-mender rocko-v2018.05

_Released 05.09.2018_

## meta-mender rocko-v2018.05
* mender: Copy data partition images to the deploy dir.
* Fix mender not building if build and host architecture is the same.
* Increased the demo mender-retry-polling interval
  ([MEN-1006](https://tracker.mender.io/browse/MEN-1006))
* Fix failed uboot.env install when mender-uboot feature is disabled.
* Implement GRUB and x86-64 support.
  ([MEN-1430](https://tracker.mender.io/browse/MEN-1430), [MEN-1432](https://tracker.mender.io/browse/MEN-1432), [MEN-1433](https://tracker.mender.io/browse/MEN-1433), [MEN-1434](https://tracker.mender.io/browse/MEN-1434), [MEN-1435](https://tracker.mender.io/browse/MEN-1435), [MEN-1436](https://tracker.mender.io/browse/MEN-1436))
* Implement qemux86-64 machine target.
  ([MEN-1430](https://tracker.mender.io/browse/MEN-1430), [MEN-1432](https://tracker.mender.io/browse/MEN-1432), [MEN-1433](https://tracker.mender.io/browse/MEN-1433), [MEN-1434](https://tracker.mender.io/browse/MEN-1434), [MEN-1435](https://tracker.mender.io/browse/MEN-1435), [MEN-1436](https://tracker.mender.io/browse/MEN-1436))
* Make sure auto provided fw-utils use virtual/bootloader setting if present.
* Add Mender 1.5.0 Beta recipe.
* mender: Use only the basename to load DTBs.
* mender: Conditionally add /uboot mount only for SDCards.
* Make sure that new-style "enp" network devices get DHCP address in demo.
* mender: Allow for forcing a specific KERNEL_IMAGETYPE.
* Remove unused IMAGE_UENV_TXT_FILE variable.


## Mender v1.5.0b1

_Released 05.15.2018_

#### deployments (1.5.0b1)
* display number of devices targeted when listing deployments
* possible to upload artifacts to specific tenant via internal API
  ([MEN-1775](https://tracker.mender.io/browse/MEN-1775))
* add ability to filter on deployment creation timestamps

#### deviceauth (1.5.0b1)
* trigger device provisioning workflow only if the device is not currently accepted
* device count endpoint handles preauthorized devices
* moved to globalsign/mgo

#### gui (1.5.0b1)
* Fix bug where recent deployment stats were being called repeatedly on dashboard
* Display version in UI
* Redesign Devices sections, added Rejected devices tab
* Display a dialog after first deployment as part of onboarding
* Move main navigation to be left aligned

#### integration (1.5.0b1)
* Switched to using Intel x86_64 hardware accelerated client
  instead of ARM emulator.
* Make the integration version available to the UI
  ([MEN-1767](https://tracker.mender.io/browse/MEN-1767))
* mender-conductor container is now based on
  github.com/mendersoftware/mender-conductor repository.
* Add --kvm option to demo scripts to run client VM hardware accelerated.
* Introduce optional mender-conductor container based on
  github.com/mendersoftware/mender-conductor-enterprise, for Enterprise
  installations.
* migrate to setup with mender-conductor-enterprise image
* Switch default client container type to qemux86-64.
* Upgrade deployments to 1.5.0b1.
* Upgrade deviceadm to 1.4.0b1.
* Upgrade deviceauth to 1.5.0b1.
* Upgrade gui to 1.5.0b1.
* Upgrade inventory to 1.4.0b1.
* Upgrade mender to 1.5.0b1.
* Upgrade mender-api-gateway-docker to 1.5.0b1.
* Add mender-conductor 1.0.0b1.
* Add mender-conductor-enterprise 1.0.0b1.
* Upgrade useradm to 1.5.0b1.
* migrate to setup with mender-conductor image

#### mender (1.5.0b1)
* Regenerate keys on all key errors, not just when keys are missing.
  ([MEN-1823](https://tracker.mender.io/browse/MEN-1823))
* cli: New client option to show installed artifact name
  ([MEN-1806](https://tracker.mender.io/browse/MEN-1806))
* Spontaneous-reboot hardening of the client
  ([MEN-1187](https://tracker.mender.io/browse/MEN-1187))
* FIXED: Log writes not flushed from memory
  ([MEN-1726](https://tracker.mender.io/browse/MEN-1726))
* Allow multiple digit partition numbers.
* log request-id in case of bad API requests
  ([MEN-1738](https://tracker.mender.io/browse/MEN-1738))
* Abort upgrade if artifact name is not retrievable from artifact_info
  ([MEN-1824](https://tracker.mender.io/browse/MEN-1824))

#### mender-api-gateway-docker (1.5.0b1)
* Allow cross-origin requests from hostnames listed in ALLOWED_HOSTS
* When a client exceeds its rate limit gateway returns 429 (Too
  Many Requests) instead of 503 (Service Temporarily Unavailable)

#### useradm (1.5.0b1)
* New internal endpoint for deleting authentication tokens.


## Mender v1.4.0

_Released 03.20.2018_

#### integration (1.4.0)
* Upgrade deployments to 1.4.0.
* Upgrade deviceadm to 1.3.0.
* Upgrade deviceauth to 1.4.0.
* Upgrade gui to 1.4.0.
* Upgrade inventory to 1.3.0.
* Upgrade mender to 1.4.0.
* Upgrade mender-api-gateway-docker to 1.4.0.
* Upgrade mender-artifact to 2.2.0.
* Upgrade useradm to 1.4.0.

#### mender (1.4.0)
* Allow multiple digit partition numbers.


## meta-mender rocko-v2018.03

_Released 03.19.2018_

#### meta-mender rocko-v2018.03
* mender upgraded to 1.4.0.
* mender-artifact upgraded to 2.2.0.
* Document SDIMG_ROOTFS_TYPE settings for Raspberry Pi.
* Fix creating ubifs image.
* mender-qemu: increase qemu memory size to 256MiB.
* meta-mender-toradex-nxp: increase layer priority to 91


## meta-mender rocko-v2018.02

_Released 02.02.2018_

#### meta-mender rocko-v2018.02
* mender: Append to fstab rather than replacing it.
* Add mender-1.4.0b1 and mender-artifact-2.2.0b1 recipes.
* Fix 'depends upon non-existent task' error in U-Boot recipes without auto patching.
* Add mender-1.3.1 and mender-artifact-2.1.2 recipes.
* QEMU: Raise systemd service timeout so that it boots properly on slow hosts.
* Added new state script to wait for time sync to complete.
* Fix "No rule to make target 'envtools'" error in some U-Boot builds.
* Pregenerate SSH keys for all QEMU images.


## Mender v1.4.0b1

_Released 02.09.2018_

#### deployments (1.4.0b1)
* updated aws-go-sdk to v1.12.27
* delete artifact from storage if parsing failed

#### deviceadm (1.3.0b1)
* PUT /devices/{id}/status (internal)

#### gui (1.4.0b1)
* Add checkbox option to remain logged in
* add progress bar for individual devices updates
  ([MEN-1558](https://tracker.mender.io/browse/MEN-1558))
* make it possible to decommission a device that has never sent inventory
* add request ID to snackbar
* Added deployments in progress to header bar
* Add Device notifications to top bar
* Fix for showing incorrect device IDs
  ([MEN-1536](https://tracker.mender.io/browse/MEN-1536))

#### integration (1.4.0b1)
* Upgrade Conductor to 1.8.1
* replace dynomite with redis
* fix http 404 on decommissioning
* Update integration version references to 1.4.x.
* Upgrade deployments to 1.4.0b1.
* Upgrade deviceadm to 1.3.0b1.
* Upgrade deviceauth to 1.4.0b1.
* Upgrade gui to 1.4.0b1.
* Upgrade inventory to 1.3.0b1.
* Upgrade mender to 1.4.0b1.
* Upgrade mender-api-gateway-docker to 1.4.0b1.
* Upgrade mender-artifact to 2.2.0b1.
* Upgrade useradm to 1.4.0b1.
* replace dynomite with redis

#### inventory (1.3.0b1)
* Get all devices in a group with a single api-call.
  ([MEN-811](https://tracker.mender.io/browse/MEN-811))

#### mender (1.4.0b1)
* Report update status for scripts and states
  ([MEN-1015](https://tracker.mender.io/browse/MEN-1015))
* Print detailed logs about authorization errors.
  ([MEN-1660](https://tracker.mender.io/browse/MEN-1660), [MEN-1661](https://tracker.mender.io/browse/MEN-1661))
* mender-device-identity: Check if file exists before reading
  Mender on orangepi fails to run because identity script exit with error like:
  /usr/share/mender/identity/mender-device-identity
  cat: can't open '/sys/class/net/bonding_masters/type': Not a directory
  Add check before reading type to avoid problems.
* Remove trailing slash from server URL configuration.
  ([MEN-1620](https://tracker.mender.io/browse/MEN-1620))

#### mender-artifact (2.2.0b1)
* Fix ECDSA failures while signing and verifying artifact.
  ([MEN-1470](https://tracker.mender.io/browse/MEN-1470))
* Fix broken header checksum verification.
  ([MEN-1412](https://tracker.mender.io/browse/MEN-1412))
* Add modify existing images and artifacts functionality.
  ([MEN-1213](https://tracker.mender.io/browse/MEN-1213))
* Artifact version 3 format documentation
  ([MEN-1667](https://tracker.mender.io/browse/MEN-1667))
* Mender-Artifact now returns an error code to the os on cli errors
  ([MEN-1328](https://tracker.mender.io/browse/MEN-1328))
* mender-artifact now fails with whitespace in the artifact-name
  ([MEN-1355](https://tracker.mender.io/browse/MEN-1355))

#### mender-api-gateway-docker (1.4.0b1)
* reload-when-hosts-changed: silence cmp output
* From now on it is possible to set rate limit per IP address
  for the API using environment variables.
  There are two variables:
  RATE_LIMIT_GLOBAL_RATE=limit - number of request per second
  RATE_LIMIT_GLOBAL_BURST=burst - burst parameter defines
  how many requests a client can make in excess
  of the rate specified by the limit.
  Both parameters, limit and burst, should be numbers.
* entrypoint: include mender-gui in monitored DNS names


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


## Mender v1.2.2

_Released 11.14.2017_

#### deployments (1.2.2)
* deployments: descending sort by created time when listing deployments

#### integration (1.2.2)
* Upgrade deployments to 1.2.2.
* Upgrade gui to 1.2.1.
* Upgrade mender-api-gateway-docker to 1.2.1.
* Fix Missing restart policy for some containers in
  docker-compose setup.
  ([MEN-1556](https://tracker.mender.io/browse/MEN-1556))

#### mender-api-gateway-docker (1.2.1)
* nginx: separate HTTP and HTTPS server scopes, redirect all HTTP requests to HTTPS


## Mender v1.2.1

_Released 10.02.2017_

#### deployments (1.2.1)
* Prevent artifacts with invalid checksums from
  being uploaded to the server.
  ([MEN-1412](https://tracker.mender.io/browse/MEN-1412))

#### integration (1.2.1)
* Upgrade deployments to 1.2.1.
* Upgrade mender to 1.2.1.
* Upgrade mender-artifact to 2.1.1.

#### mender (1.2.1)
* Improve error messages for state scripts errors.
  Rely on the full error description instead of just the error code.
* Fix checksum not being verified for headers, only
  payload. ([MEN-1412](https://tracker.mender.io/browse/MEN-1412))

#### mender-artifact (2.1.1)
* Fix broken header checksum verification.
  ([MEN-1412](https://tracker.mender.io/browse/MEN-1412))


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
