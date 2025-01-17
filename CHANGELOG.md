# Changelog

This changelog is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

promise-android-tools versioning started at 1.0.0, but this changelog was not added until 4.0.6.

## [Unreleased]

## [4.0.10] - 2022-03-24

### Fixed

- Handle protocol fault / connection reset error in adb ([#63](https://github.com/ubports/promise-android-tools/pull/63))

### Changed

- Update dependencies ([145a0e28bc61ea1cc359b4e3d82d911db3fc83dc](https://github.com/ubports/promise-android-tools/commit/145a0e28bc61ea1cc359b4e3d82d911db3fc83dc))

## [4.0.9] - 2022-03-20

### New

- Adb: add getprop() and getSystemImageCapability() ([#61](https://github.com/ubports/promise-android-tools/pull/61))

### Changed

- Update dependencies ([6d47250c40bdf9dc1a24d748e72b13f8d50ae36d](https://github.com/ubports/promise-android-tools/commit/6d47250c40bdf9dc1a24d748e72b13f8d50ae36d))

## [4.0.8] - 2022-03-10

### New

- Fastboot: add command to wipe super ([#58](https://github.com/ubports/promise-android-tools/pull/58))
- Fastboot: add reboot commands for fastbootd and recovery mode ([#57](https://github.com/ubports/promise-android-tools/pull/57))

## [4.0.7] - 2021-10-02

### Changed

- Update dependencies ([fae268b54af6ab941a2129e670a6e582b0e48815](https://github.com/ubports/promise-android-tools/commit/fae268b54af6ab941a2129e670a6e582b0e48815))

## [4.0.6] - 2021-04-16

### Fixed

- Prevent downstream race conditions in `adb.startServer()` ([#56](https://github.com/ubports/promise-android-tools/pull/56))
