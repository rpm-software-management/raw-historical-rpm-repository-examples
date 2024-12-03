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

With Fedora 7 dropping 'Core' from the name, we now have:
```
fedora-linux-updates-7-x86_64-updateinfo.xml
```

Notes
-----

Fedora Core 1 through 4 do not have any updateinfo (at least that I can find).

The main differences between the architectures is going to be the NVRs for the
updates.

Fedora tends to separate out `main` frome `updates`, with `main` being the initial
release, and any further changes added to `updates`. Thus, the `main` repository
does not have `updateinfo.xml` as there are no updates to it.

Fedora 8 and 9 have `.newkey` "architectures" as well. See https://fedoraproject.org/wiki/Enabling_new_signing_key for details.

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

The `main` / `updates` repository style continues, where `main` does not have `updateinfo.xml`.

URLs:
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/7/SRPMS/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/7/i386/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/7/ppc/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/7/ppc64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/7/x86_64/repodata/updateinfo.xml.gz

Fedora 8
--------

Retreived 2024-12-02.

Last updated 2009-01-08 (newkey), 2008-09-10 (original).

Architectures: `SRPMS`, `i386`, `ppc`, `ppc64`, `x86_64`. Each has a regular repo and a `.newkey` repo.

The `main` / `updates` repository style continues, where `main` does not have `updateinfo.xml`.

URLs:
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/8/SRPMS/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/8/i386/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/8/ppc/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/8/ppc64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/8/x86_64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/8/SRPMS.newkey/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/8/i386.newkey/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/8/ppc.newkey/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/8/ppc64.newkey/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/8/x86_64.newkey/repodata/updateinfo.xml.gz

Fedora 9
--------

Retreived 2024-12-02.

Last updated 2009-07-11 (newkey), 2008-09-10 (original).

Architectures: `SRPMS`, `i386`, `ppc`, `ppc64`, `x86_64`. Each has a regular repo and a `.newkey` repo.

The `main` / `updates` repository style continues, where `main` does not have `updateinfo.xml`.

URLs:
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/9/SRPMS/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/9/i386/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/9/ppc/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/9/ppc64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/9/x86_64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/9/SRPMS.newkey/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/9/i386.newkey/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/9/ppc.newkey/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/9/ppc64.newkey/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/9/x86_64.newkey/repodata/updateinfo.xml.gz

Fedora 10, 11, 12
--------

Retreived 2024-12-02.

Last updated:
- Fedora 10: 2009-12-11
- Fedora 11: 2010-06-25
- Fedora 12: 2010-12-02

Architectures: `SRPMS`, `i386`, `ppc`, `ppc64`, `x86_64`.

The `main` / `updates` repository style continues, where `main` does not have `updateinfo.xml`.

URLs:
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/{10,11,12}/SRPMS/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/{10,11,12}/i386/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/{10,11,12}/ppc/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/{10,11,12}/ppc64/repodata/updateinfo.xml.gz
 - https://archive.fedoraproject.org/pub/archive/fedora/linux/updates/{10,11,12}/x86_64/repodata/updateinfo.xml.gz
