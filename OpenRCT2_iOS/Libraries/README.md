libpng for iOS
=========================

libpng for iOS provides a Xcode project, which compiles libpng (http://www.libpng.org/pub/png/libpng.html) to a Cocoa Touch Static Library.

The current version uses libpng version 1.6.26.

Building
=========================
libpng itself requires zlib. This dependency is provided by OS X via the -lz linker flag (see Project -> Build Settings -> Other Linker Flags).

libpng for iOS has been tested to work with Xcode 8.1 (8B62).
