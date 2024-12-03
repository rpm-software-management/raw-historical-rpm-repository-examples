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
epel-<version>-<arch>-[CHECKSUM-]<filename>
```

For example, for the EPEL4 x86_64 `update.info.xml` file:

```
epel-4-x86_64-updateinfo.xml
```

When we get to EPEL5, a checksum is added due to the repository format changing to one where file names included a checksum. For example:

```
epel-5-x86_64-6f41b252fdd98804bf8726c41ee0b29f778581a1-updateinfo.xml
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

EPEL5
-----

Retrieved 2024-12-02.

The repositories were last updated around 2017-03-30.

There are three variants: 5, 5Client, 5Server.

Architectures: SRPMS, i386, ppc, x86_64.

All variants and architectures share the same `updateinfo.xml` file (checksum matches).

EPEL5 is the first EPEL release to use `repodata` where a checksum is included in the file names of each file. Currently, we only have an archive of one checksum

Filename: 6f41b252fdd98804bf8726c41ee0b29f778581a1-updateinfo.xml.gz

URLs:

 - https://archive.fedoraproject.org/pub/archive/epel/{5,5Client,5Server}/{SRPMS,i386,ppc,x86_64}/repodata/6f41b252fdd98804bf8726c41ee0b29f778581a1-updateinfo.xml.gz