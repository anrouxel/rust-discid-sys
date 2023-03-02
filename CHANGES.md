# Changelog

## 0.5.0 (2022-03-02)
- Fix compilation with standard discid.h for libdiscid 0.6.4

Features from the features enum now must be cast when passing to
`discid_read_sparse` by calling `into()`.

## 0.4.1 (2022-02-28)
- Build with bindgen 0.64.0
- Moved sources to https://git.sr.ht/~phw/rust-discid-sys

## 0.4.0 (2020-01-24)
Use bitfield_enum for `discid_feature`

## 0.3.0 (2019-05-27)
Blacklisted version constants `DISCID_VERSION_MAJOR`, `DISCID_VERSION_MINOR`,
`DISCID_VERSION_PATCH` and `DISCID_VERSION_NUM`.

These constants do not represent the actual libdiscid being used, but the one
present at build time. `discid_get_version_string()` should be used instead.

## 0.2.1 (2019-05-27)
Revert black listing `DISCID_FEATURE_LENGTH`, which is needed to properly
call `discid_get_features`.

## 0.2.0 (2019-05-07)
Changed feature constants to be inside a module. This changed the syntax
to access features from `discid_feature_DISCID_FEATURE_READ` to
`discid_feature::DISCID_FEATURE_READ`.

This works better with parts of code that expect integers directly
(`discid_read_sparse`), but reads nicer than the default constants.

## 0.1.1 (2019-05-07)
- Added example `readdisc.rs`

## 0.1.0 (2019-05-03)
Initial release
