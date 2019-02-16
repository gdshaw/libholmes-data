# libholmes-data

## Purpose

The data in this repository is part of libholmes, which is a library for
the forensic analysis of files and network traffic. The content includes
signatures and other information used by libholmes at runtime. It is
published separately from the remainder of the source code because it is
expected to change more rapidly.

## Building

The data files are built by executing the script:

./build.sh

This merges the small JSON files which are the preferred format for
editing into larger JSON files which are in a suitable format for use
by the library.

## Copyright and licensing

libholmes is copyright 2018-2019 Graham Shaw.

Distribution and modification are permitted within the terms of the
GNU General Public License (version 3 or any later version).

Please refer to the file [LICENCE.md](LICENCE.md) for details.

Third-party contributions are not currently being accepted into the
upstream project.
