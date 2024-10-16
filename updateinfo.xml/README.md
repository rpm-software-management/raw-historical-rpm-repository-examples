updateinfo.xml samples
======================

These are examples of `updateinfo.xml` files from as many `RPM`/`yum`/`dnf`
based Linux distributions and versions that I could find. The purpose of
collating them all here is to be able to look at real world examples of
this format, and where quirks are.

Collating these files together will be useful for writing documentation
and tests.

Notes
-----

OpenSUSE starts having updateinfo at 11.0, with a prior patch format in 10.x.
Currenttly, pre-10.x metadata is not here. I believe this was the precursor
to the `updateinfo.xml` style metadata, and may not be relevant for any
tooling going forward. Since it's a different format, it should go in its
own section rather than sharing with `updateinfo.xml`.

I know of another one!
----------------------
Awesome! Send a pull request!

Where is the spec?
------------------
See https://github.com/rpm-software-management/rpm-metadata for a (slowly) growing set of documentation on all parts of the repository metadata.

There is an XML schema with documentation about all the various quirks that have been seen in this data set.

Where are these from?
---------------------
See the `README.md` in each directory.
