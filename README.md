
Harry - Similarity Measures for Strings
==

Description
-- 

Harry is a small tool for comparing strings. The tool supports several
common distance and kernel functions for strings as well as some excotic
similarity measures.  The focus of Harry lies on implicit similarity
measures, that is, comparison functions that do not give rise to an explicit
vector space, such as the Levenshtein distance.  Harry complements the tool
Sally that embeds strings in vector spaces, where explicit similarity
measures can be computed, such as bag-of-word kernels.

Dependencies
--

    >= zlib-1.2.1
    >= libconfig-1.4
    >= libarchive-2.70

Corresponding packages

+ Debian and Ubuntu Linux: `libz-dev libconfig9-dev libarchive-dev`
+ MacOS X with Homebrew:   `libconfig libarchive (homebrew-dupes)`
+ MacOS X with MacPorts:   `libconfig-hr libarchive`

The source code of the libraries is available here:

+ zlib        <http://www.zlib.net/>
+ libconfig   <http://www.hyperrealm.com/libconfig/>
+ libarchive  <http://libarchive.github.com/>

Compilation & Installation
--

From GIT repository first run

    ./bootstrap

From tarball run

    ./configure [options]
    make
    make check
    make install

Options for configure

    --prefix=PATH           Set directory prefix for installation

By default Harry is installed into /usr/local. If you prefer a different
location, use this option to select an installation directory.

Copyright (C) 2013 Konrad Rieck (konrad@mlsec.org)