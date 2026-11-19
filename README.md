# camoufox-mirror

Linux x86_64 build of [Camoufox](https://camoufox.com) (MPL-2.0), mirrored because github.com/daijro, where the
official builds were published, is unavailable since 2026-11-19.

| Release | Pairs with | sha256 of the zip here |
|---|---|---|
| v156.0.1-beta.36 | `camoufox` 0.5.8 (Python) | `0c9c128d1c9fc918f0bc12fbbe04d0b22a26652afbc4861885e77ddb7d043f6b` |

The zip was repacked from an install that `camoufox fetch` made on 2026-10-18 and verified at the time against
daijro's published sha256 for `camoufox-156.0.1-beta.36-lin.x86_64.zip`
(`72637885ee67c93466ad377831c647192f8f08fb5c6fd9279de1320b49dd2b53`). The repacked zip has the same files
(without `version.json`, which the installer writes) and therefore its own sha256.

Source code and license: the Camoufox project. This repo only redistributes the binaries.
