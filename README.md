# rime-opencc-latest

Recipe: ℞ `sgalal/rime-opencc-latest`

Customize rime input schemata to use the latest [OpenCC](https://github.com/BYVoid/OpenCC) dictionaries

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

## Version

OpenCC [`086834c`](https://github.com/BYVoid/OpenCC/commit/086834c983396f75ee0a83e10b67014e4f1e6ef7)
