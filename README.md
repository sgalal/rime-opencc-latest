# rime-opencc-latest

Recipe: ℞ `sgalal/rime-opencc-latest`

Customize rime input schemata to use the latest [OpenCC](https://github.com/BYVoid/OpenCC) dictionaries

For 32-bit version, see [sgalal/rime-opencc-32bit-latest](https://github.com/sgalal/rime-opencc-32bit-latest).

## Why

The OpenCC shipped with rime installer is not the latest version. Using the latest version will improve the accuracy of OpenCC conversion.

## How

This repository contains the latest version of OpenCC dictionaries. These files will be copied to the rime user directory by the [plum](https://github.com/rime/plum) configuration manager.

## Usage

With plum installed:

```sh
$ bash rime-install sgalal/rime-opencc-latest
```

Without plum:

```sh
$ curl -fsSL https://git.io/rime-install | bash -s -- sgalal/rime-opencc-latest
```

## Build Script

See [CI Build](https://ci.appveyor.com/project/chromezh/opencc).

## Version

OpenCC [`8e8fb25`](https://github.com/BYVoid/OpenCC/commit/8e8fb25707b5ef5709e1a278149ce88217a5fbf6)
