# Copyright (c) 2015 Nuxi, https://nuxi.nl/
#
# This file is distributed under a 2-clause BSD license.
# See the LICENSE file for details.

package(
    name='fribidi',
    version='0.19.7',
    homepage='http://fribidi.org/',
    maintainer='info@nuxi.nl',
    lib_depends={'c-runtime'},
    build_cmd=build_autoconf_automake,
)

distfile(
    name='fribidi-0.19.7.tar.bz2',
    checksum='08222a6212bbc2276a2d55c3bf370109ae4a35b689acbc66571ad2a670595a8e',
    master_sites={'http://fribidi.org/download/'},
    unsafe_string_sources={'charset/fribidi-char-sets-cap-rtl.c'},
)
