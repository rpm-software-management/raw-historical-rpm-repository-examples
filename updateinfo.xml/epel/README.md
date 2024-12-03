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

EPEL6
-----

Architectures: SRPMS, i386, ppc64, x86_64.

There are repositories for 6 and 6.2017-11-07.

Last updated:

 - 6.2017-11-07: 2019-05-26 for `ppc64` and 2019-05-29 for SRPMs, i386, and x86_64
 - 6: 2019-05-26 for `ppc64` and 2020-11-30 for SRPMs, i386, and x86_64

EPEL6 is the second EPEL release to use `repodata` where a checksum is included in the file names of each file. Where there are duplicates, symlinks are used. We only have a limited number of checksums archived. Checksums changed when repository updates were made.

Checksums:

 - Release 6.2017-11-07, Arches SPRMS, i386, x86_64: 804c7236e6d341cbb68a257bf8b984a140c1f1d2006e35ba9f6d2383b1a50ab0-updateinfo.xml.bz2
 - Release 6 and 6.2017-11-07, Arches ppc64: 8199ff1f5548b7cf5f052dd55e7586dcd40b48eb39855b5a706d069a44dec202-updateinfo.xml.bz2
 - Release 6, Arches SRPMS, i386, x86_64: 8c154dfbca035f5f6981648a6f390ffcd8c209878e9b4b3e293378ca01cd48c6-updateinfo.xml.bz2

URLs:

 - https://archive.fedoraproject.org/pub/archive/epel/6.2017-11-07/{SRPMS,i386,x86_64}/repodata/804c7236e6d341cbb68a257bf8b984a140c1f1d2006e35ba9f6d2383b1a50ab0-updateinfo.xml.bz2
 - https://archive.fedoraproject.org/pub/archive/epel/{6,6.2017-11-07}/ppc64/repodata/8199ff1f5548b7cf5f052dd55e7586dcd40b48eb39855b5a706d069a44dec202-updateinfo.xml.bz2
 - https://archive.fedoraproject.org/pub/archive/epel/6/{SRPMS,i386,x86_64}/repodata/8c154dfbca035f5f6981648a6f390ffcd8c209878e9b4b3e293378ca01cd48c6-updateinfo.xml.bz2

