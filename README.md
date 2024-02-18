# Zip of Total Death (ZoTD)
This is a decompression bomb (also known as zip of death or zip bomb) designed t
o crash or render useless the program or system reading it.

It is usually a small file for ease of transport and to avoid suspicion.
However, when the file is unpacked, its contents are more than the system can
handle. It is often employed to disable antivirus software, in order to create
an opening for more traditional viruses.

Rather than hijacking the normal operation of the program, a zip bomb allows the
program to work as intended, but the archive is carefully crafted so that
unpacking it (e.g. by a virus scanner in order to scan for viruses) requires
inordinate amounts of time, disk space or memory.

*Most modern antivirus programs can detect whether a file is a zip bomb, to
avoid unpacking it.*

### `128.zip`
This repository contains the `9.zip` zip bomb, which is a zip file consisting
of the `128.zip` zip bomb, containing fifteen layers of nested zip files
in sets of 16, each bottom layer archive containing a 4.3 gigabyte
(4 294 967 295 bytes; ~ 3.99 GiB) file for a total of 7515.24441 of uncompressed data.

So, if you extract all the files, you will hopefully run out of space.

### PASSWD
ZoTD!
