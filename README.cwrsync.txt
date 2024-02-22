cwRsync 6.2.10 - Rsync client for Windows
October 2023, provided by itefix.net - https://www.itefix.net/cwrsync

This archive contains a barebone distribution of Rsync for Windows.

- Unzip archive contents to a directory
- update the supplied batch file cwrsync.cmd.

That's all you need to be able to initiate rsync connectionsfrom
from a command line.

NB! In the case you run into -meaningless- permission issues, please
consult our FAQ https://www.itefix.net/node/15959

cwRsync FAQs(https://itefix.net/faqs?qt-faqs=1#qt-faqs) can also be helpful.

We provide paid versions of cwRsync with a helper GUI or setup as a server.
See https://www.itefix.net/cwrsync for more information.

ENJOY RSYNC!!

Version information:
Rsync 3.2.7
Cygwin 3.4.9
OpenSSH 9.4p
LibreSSL 3.7.3

Output of 'rsync --version':
----------------------------
rsync  version 3.2.7  protocol version 31
Copyright (C) 1996-2022 by Andrew Tridgell, Wayne Davison, and others.
Web site: https://rsync.samba.org/
Capabilities:
    64-bit files, 64-bit inums, 64-bit timestamps, 64-bit long ints,
    socketpairs, symlinks, symtimes, hardlinks, no hardlink-specials,
    hardlink-symlinks, IPv6, atimes, batchfiles, inplace, append, no ACLs,
    no xattrs, optional secluded-args, iconv, prealloc, stop-at, crtimes
Optimizations:
    no SIMD-roll, no asm-roll, openssl-crypto, no asm-MD5
Checksum list:
    xxh64 (xxhash) md5 md4 sha1 none
Compress list:
    zstd lz4 zlibx zlib none
Daemon auth list:
    sha512 sha256 sha1 md5 md4

rsync comes with ABSOLUTELY NO WARRANTY.  This is free software, and you
are welcome to redistribute it under certain conditions.  See the GNU
General Public Licence for details.

Output of 'ssh -V':
-------------------
OpenSSH_9.5p1, LibreSSL 3.7.3
