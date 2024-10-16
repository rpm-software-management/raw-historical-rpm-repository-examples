# Raw Historical RPM Repository Examples

In contrast to the effort to document the RPM repository metadata formats
in [rpm-metadata](https://github.com/rpm-software-management/rpm-metadata), this repository
houses raw examples.

Since real-world data for some repository metadata (and data) gets large,
those files can live here, reserving [rpm-metadata](https://github.com/rpm-software-management/rpm-metadata)
for smaller examples (either edited versions of what's here, or examples
that illustrate the real-world quirks that have been observed).

This repository is *just the raw data* with some READMEs about it.

Initially, this is just `updateinfo.xml`, but expanding over time is encouraged.

Why?
----

To save the next person time when looking for a large collection of real-world
examples (for whatever reason).

When authoring tooling to interact with RPM repositories (e.g. `dnf`, third
party tools, or something as simple as an updateinfo to HTML tool), being
able to ensure your software is correct is important. As the repository format
has evolved over decades, real world examples are important for testing, and
helping determine specific test cases.

Repository Layout
-----------------

- `data-or-metadata-type/`
  - A `README.md` describing directory layout, where data came from, where to
    look in [rpm-metadata](https://github.com/rpm-software-management/rpm-metadata)
    for more concise information
  - The data/metadata, in whatever structure is most useful

What are we looking to add?
---------------------------

As much real-world data as possible (within reason of duplication)!

What we are looking for:
1. Examples of good practice
2. Examples of less than ideal practice
3. Outright errors/mistakes that can be useful for constructing tests/documentation as to expected behavior

Why?
----

Hunting down historical examples can take a long time. Let's avoid doing that.


What about RPMs themselves?
---------------------------

We prefer not to store the entire RPM repostories here, so when bringing
in any binary and source RPMs, there should be an explicit purpose for it,
and an attempt made to find the smallest files that illustrate something.

