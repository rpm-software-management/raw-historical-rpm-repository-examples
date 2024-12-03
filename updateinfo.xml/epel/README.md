Real-world EPEL `updateinfo.xml` examples
=========================================

EPEL is part of the Fedora project.

As much as possible, this is the collection of (uncompressed) `updateinfo.xml`
files from [Fedora](https://fedoraproject.org/) EPEL repositories.

As per the [License of Fedora Linux](https://docs.fedoraproject.org/en-US/legal/fedora-linux-license/),
Fedora Linux is a compilation of software packages, each under its own licensing terms.
The compilation license for Fedora Linux is the MIT license.

File names are structured like so:

```
epel-<version>-<arch>-<filename>
```

For example, for the EPEL4 x86_64 `update.info.xml` file:

```
epel-4-x86_64-updateinfo.xml
```

Notes
-----

There are many repositories with a `updateinfo.xml` file with the same checksum as in others (e.g. all of the EPEL4 ones). Where this is the case, symlinks are used rather than duplicating the file contents.

EPEL4
-----

Retrieved 2024-12-02.

The repositories were last updated around 2012-03-01.

There are several variants: 4, 4AS, 4ES, 4WS

Architectures: SRPMS, i386, ppc, x86_64.

URLs:

 - https://archive.fedoraproject.org/pub/archive/epel/{4,4AS,4ES,4WS}/{SRPMS,i386,ppc,x86_64}/repodata/updateinfo.xml.gz

