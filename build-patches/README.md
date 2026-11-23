Patched copies of files from the generated build tree (`src/op25`, produced by the op25 build scripts) needed to build on
GNU Radio 3.10 / Python 3.14 / Boost 1.90 (Ubuntu 26.04): Boost::system removed from CMake, cmake_minimum_required 3.5 for
imbe_vocoder, `#define _DEFAULT_SOURCE` in mbelib.c. Copy over the generated tree after generating it, then build.
