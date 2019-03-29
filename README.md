BuildTools
==========

## Description

This repository contains tools used for building projects stored at https://github.com/gildor2/. It contains a stripped binary set from MSys2 (bash, perl etc,
exe and dll files in bin directory) and a few custom scripts. If you already have MSys2 or Git for Windows installed and referenced in PATH environment variable,
you'd probably won't need exe and dll files from bin directory.

A tool which should be mentioned separately is [Jom](https://wiki.qt.io/Jom) - a Microsoft nmake replacement with support for running multiple build tasks in
parallel. Originally it was a part of Qt library, but later became a separate tool. This repository uses nmake to speedup builds a few times, it is selected
by vc32tools automatically when available.

## Tools

- [vc32tools](bin/vc32tools) - a helper script which can find and launch Visual C++ compiler
- [vcfilt](bin/vcfilt) - a helper script which colorizes Visual C++ output

## License

All binary files from MSys2 directory are covered with GNU Public License. Tools represented in this repository are public domain.
