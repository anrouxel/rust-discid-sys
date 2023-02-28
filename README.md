# Unsafe FFI bindings for MusicBrainz libdiscid
[![crates.io](https://img.shields.io/crates/v/discid-sys.svg)](https://crates.io/crates/discid-sys)
[![Documentation](https://docs.rs/discid-sys/badge.svg)](https://docs.rs/discid-sys)
[![License](https://img.shields.io/crates/l/discid-sys.svg)](https://crates.io/crates/discid-sys)
[![builds.sr.ht status](https://builds.sr.ht/~phw/rust-discid-sys/commits/main/.svg)](https://builds.sr.ht/~phw/rust-discid-sys/commits/main/?)

## About
discid-sys provides automatically generated, unsafe Rust bindings for
MusicBrainz [libdiscid](http://musicbrainz.org/doc/libdiscid).

You usually don't want to use these bindings directly but instead use the
safe [discid](https://crates.io/crates/discid) wrapper library.

## Requirements
- libdiscid >= 0.6.0

## Contribute
The source code for discid-sys is available on
[SourceHut](https://git.sr.ht/~phw/rust-discid-sys).

Please report any issues on the
[issue tracker](https://todo.sr.ht/~phw/discid-bindings).

Patches can be submitted to the [mailing list](https://lists.sr.ht/~phw/musicbrainz).
You can clone the repository directly on SourceHut and submit your changes
with the "Prepare patchset" button. Please see SourceHut's
[documentation for sending patches upstream](https://man.sr.ht/git.sr.ht/#sending-patches-upstream)
for details.

## License
discid-sys Copyright (c) 2019-2023 by Philipp Wolfer <ph.wolfer@gmail.com>

discid-sys is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Lesser General Public License for more details.

See [LICENSE](./LICENSE) for details.
