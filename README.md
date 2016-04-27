# GnuWin
The GnuWin project provides Win32-versions of GNU tools, or tools with a similar open source licence. The ports are native ports, that is they rely only on libraries provided with any standard 32-bits MS-Windows operating system, such as MS-Windows 95 / 98 / ME / NT / 2000 / XP / 2003 / Vista. Unlike CygWin or Msys, native ports do not rely on some kind of Unix emulation, so that there is no need to install additional emulation libraries. At present, all developments have been done under MS-Windows-XP, using the Mingw port of the GNU C and C++ (GCC) compilers. Utilities and libraries provided by GnuWin, are used and distributed with packages such as GNU Emacs and KDE-Windows.

The packages that have been ported, fall into four broad categories:

    GNU utilities: bc, bison, chess, compface, cpio, coreutils (fileutils, sh-utils, stat, textutils), diffutils, doschk, ed, findutils, flex, gawk, gdbm, gcal, gengetopt, gettext, gperf, grep, groff, gsl, gzip, hello, help2man, iconv, jwhois, less, m4, miscfiles, patch, readline, regex, rx, sed, sharutils, tar, texinfo, tree, units, unrtf, wget, which
    Archivers and compressors: arc, arj, bsdtar, bzip2, gzip, lha, libarchive, unzip / zip, zlib
    Other utilities: byacc, cpuid, cygutils, file, ntfsprogs, openssl, pcre, popt, re2c, rpl, sgrep, tree, x86info
    Graphics packages: asciichart, compface, gd, jpeg, jbigkit, liburt, libungif, libpng and png utilities, libwmf, netpbm, piechart, plotutils, tiff, xpm, zimg
    Textprocessing- and postscript-related packages: a2ps, barcode, bm2font, deroff, dvidj, enscript, freetype, grap, gri, groff, indent, libxml, nenscript, pdflib,  polyglotman, psutils, scribe2latex, src-highlite, t1lib, t1utils, troff2latex, ttf2pt1, unrtf
    Mathematical and statistical packages: bc, calc, crypt, fdlibm, gsl, units

Some other characteristics of GnuWin are:

    GnuWin always provides the source, which usually is also required by the license of the original package, with any changes from the original source in the form of a diff.
    GnuWin always provides the documentation in a 'compiled' form, i.e. as PDF, HTML, PS, DVI, CHM, and HLP.
    GnuWin provides import libraries for MSVC and BCC wherever possible.

Libraries

In general, static and import C libraries from GnuWin should be interoperable with other libraries compiled with Mingw, MSVC and BCC, although the options with which the library files have been compiled might differ; in particular, most libraries, and binaries, from GnuWin have been compiled without debug option. C++ libraries from different compilers are not in general interoperable.
Patches

The patches to the source code are given in unified diffs, usually in files ending in -diffs or .diff. In particular for packages whose source is infrequently updated, we try to keep track of the patches for FreeBSD, NetBSD, OpenBSD, Debian, Fedora, Red Hat, and Suse.
