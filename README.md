# Zycore - Zyan Core Library for C

This is a `build2` package repository for [`zycore-c`](https://github.com/zyantific/zycore-c).

This file contains setup instructions and other details that are more appropriate for development rather than consumption. If you want to use `zycore` in your `build2`-based project, then instead see the accompanying [`PACKAGE-README.md`](libzycore/PACKAGE-README.md) file.

The development setup for `zycore` uses the standard `bdep`-based workflow. For example:

```
git clone .../zycore.git
cd zycore

bdep init -C @gcc cc config.cxx=g++
bdep update
bdep test
```
