# Copyright (c) 2015 Nuxi, https://nuxi.nl/
#
# This file is distributed under a 2-clause BSD license.
# See the LICENSE file for details.


def build(ctx):
    build = ctx.extract().gnu_configure()
    build.make(['dist_doc_DATA='])
    build.make_install(['dist_doc_DATA=', 'install']).install()

host_package(
    name='flex',
    version='2.6.0',
    homepage='http://flex.sourceforge.net/',
    maintainer='info@nuxi.nl',
    build_depends={'bison', 'm4', 'texinfo'},
    build_cmd=build,
)

distfile(
    name='flex-2.6.0.tar.xz',
    checksum='d39b15a856906997ced252d76e9bfe2425d7503c6ed811669665627b248e4c73',
    master_sites=sites_sourceforge('flex'),
)
