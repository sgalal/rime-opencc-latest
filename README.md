# rime-opencc-latest

Recipe: ℞ `sgalal/rime-opencc-latest`

Customize rime input schemata to use the latest OpenCC dictionaries

## Why

The OpenCC shipped with rime installer is not updated regularly. However, using newer versions of OpenCC dictionaries will improve the accuracy of OpenCC conversion.

## How

This repository contains the latest version of OpenCC dictionaries. These files will be copied to the rime user directory by the [plum](https://github.com/rime/plum) configuration manager.

## Usage

```sh
$ bash rime-install sgalal/rime-opencc-latest
```

## Version

OpenCC 1.0.6
