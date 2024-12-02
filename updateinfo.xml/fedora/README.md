Real-world Fedora `updateinfo.xml` examples
===========================================

As much as possible, this is the collection of (uncompressed) `updateinfo.xml`
files from [Fedora](https://fedoraproject.org/) repositories.

As per the [License of Fedora Linux](https://docs.fedoraproject.org/en-US/legal/fedora-linux-license/),
Fedora Linux is a compilation of software packages, each under its own licensing terms.
The compilation license for Fedora Linux is the MIT license.

File names are structured like so:

```
<distro-name>-<repo>-<distro-version>-<arch>-<filename>
```

For example, for the Fedora Core 5 i386 `update.info.xml` file:

```
fedora-linux-core-updates-5-i386-updateinfo.xml
```

Notes
-----

Fedora Core 1 through 4 do not have any updateinfo (at least that I can find).

The main differences between the architectures is going to be the NVRs for the
updates.

Fedora tends to separate out `main` frome `updates`, with `main` being the initial
release, and any further changes added to `updates`. Thus, the `main` repository
does not have `updateinfo.xml` as there are no updates to it.

Fedora Core 5
-------------

Retrieved 2024-10-16.

Laste updated in mid-2007, Fedora Core 5 is the oldest Fedora with `updateinfo.xml`
in the repository metadata.

There is no `updateinfo.xml` in the SRPMs repodata.

There are `testing` repositories for Fedora Core 5 `updates`, which also have (smaller) `updateinfo.xml`.

URLs:

 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/5/x86_64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/5/i386/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/5/ppc/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/testing/5/x86_64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/testing/5/i386/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/testing/5/ppc/repodata/updateinfo.xml.gz

Fedora Core 6
-------------

Retreived 2024-10-16.

Last updated 2007-12-07.

There is no `updateinfo.xml` in the SRPMs repodata.

There are `testing` repositories for Fedora Core 5 `updates`, which also have (smaller) `updateinfo.xml`.

URLs:

 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/6/i386/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/6/x86_64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/6/ppc/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/testing/6/x86_64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/testing/6/i386/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/core/updates/testing/6/ppc/repodata/updateinfo.xml.gz

Fedora 7
--------

Retreived 2024-10-16.

Last updated 2008-06-14.

The SRPMS repository now has `updateinfo.xml`.

Architectures are now: `SRPMS`, `i386`, `ppc`, `ppc64`, `x86_64`.

The `main` / `updates` repository style continues.

URLs:
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/7/SRPMS/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/7/i386/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/7/ppc/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/7/ppc64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/7/x86_64/repodata/updateinfo.xml.gz