---
layout: default
---

# [Overview](#overview) #

The Grid Community Forum (GridCF) is a global community that provides support for core grid software.

Specifically, the GridCF is attempting to support a software stack christened the [Grid Community Toolkit](http://gridcf.org/gct-docs/) (GCT).  The GCT is an open-source fork of the venerable [Globus Toolkit](http://toolkit.globus.org/toolkit/) created by the [Globus Alliance](http://toolkit.globus.org/alliance/).  The GCT is _derived_ from the Globus Toolkit, but is not the Globus Toolkit.  Further, the GridCF is not a part of the Globus Alliance.

The GridCF is a nascent organization: we are looking for energetic contributors across a broad range of technical skills.  Check out our [governance doc](governance.md) and [join us on GitHub](https://github.com/gridcf)!

## [Objectives](#objectives) ##

The creation of the GridCF and the GCT fork of the Globus Toolkit was motivated by the announcement of the upcoming [end-of-support](https://github.com/globus/globus-toolkit/blob/globus_6_branch/support-changes.md) of the Globus Toolkit in January 2018.

With this effort, we aim to:

- Maintain the quality and security of critical functionality such as the Grid Security Infrastructure (GSI) and an open-source GridFTP implementation.
- Partner across several grid organizations to share the burden of supporting this core functionality.
- Provide an open and welcoming forum for external contributors to improve the software.

## [Contact](#contact) ##

To get in touch with us - or even better - to get involved, participate in the discussions or start a new discussion on our general mailing list [discuss@gridcf.org](https://mailman.egi.eu/mailman/listinfo/discuss) hosted by [EGI](https://www.egi.eu/).

For patches or to report non-confidential problems, please make a pull request or use the respective issue trackers in our projects [gct](https://github.com/gridcf/gct/issues) and [gct-docs](https://github.com/gridcf/gct-docs/issues) on GitHub.

If you would like to make the GridCF aware of a security problem in a discreet manner, send an email to [security@gridcf.org](mailto:security@gridcf.org).

## [News](#news) ##
----

For release and general announcements please subscribe to our announcement list [announcement@gridcf.org](https://mailman.egi.eu/mailman/listinfo/announcement) hosted by [EGI](https://www.egi.eu/).

****

### [2019-09-19](#2019-09-19) ###

#### GCT version 6.2.20190906 (maintenance release) ####

The GridCF is pleased to announce a new release of the GCT: GCT version 6.2.20190906 is a maintenance release and includes all changes since the last maintenance release in February 2019.

**Packages are available from:**

* [Debian](https://www.debian.org/) (for Debian unstable (sid), excluding gsi-openssh)

* [EPEL](https://fedoraproject.org/wiki/EPEL) (for Red Hat Enterprise Linux, CentOS and Scientific Linux 6 and 7 (currently in EPEL updates-testing!))

* [Fedora](https://fedoraproject.org/) (for Fedora 29 and 30)

> **NOTICE:** As a preview, packages (excluding gsi-openssh) are also available from the [OpenSUSE Build Service ](https://build.opensuse.org/project/show/home:frank_scheiner:gct) (or SLES 12 (SP2), 12 (SP3), 12 (SP4), 15, 15 (SP1) and OpenSUSE Leap 15.0, 15.1 and OpenSUSE Tumbleweed). To install follow [these exemplary instructions](https://software.opensuse.org//download.html?project=home%3Afrank_scheiner%3Agct&package=globus-common) for the `globus-common` package (which are also valid for the other packages).

****

All details about this release can also be found on the [corresponding GitHub releases page](https://github.com/gridcf/gct/releases/tag/v6.2.20190906)

### [2019-02-26](#2019-02-26) ###

#### GCT version 6.2.20190226 (maintenance release) ####

The GridCF is pleased to announce a new release of the GCT: GCT version 6.2.20190226 is a maintenance release and includes all changes since the first GCT 6.2 release in November 2018.

**Packages are available from:**

* [Debian](https://www.debian.org/) (for Debian testing (buster) and unstable (sid), excluding gsi-openssh)

* [EPEL](https://fedoraproject.org/wiki/EPEL) (for Red Hat Enterprise Linux, CentOS and Scientific Linux 6 and 7)

* [Fedora](https://fedoraproject.org/) (for Fedora 28, 29 and 30)

> **NOTICE:** As a preview, packages (excluding gsi-openssh) are also available from the [OpenSUSE Build Service ](https://build.opensuse.org/project/show/home:frank_scheiner:gct) (for SLES 12 (SP3), 12 (SP4), 15 and OpenSUSE Leap 15.0, 15.1 and OpenSUSE Tumbleweed). To install follow [these exemplary instructions](https://software.opensuse.org//download.html?project=home%3Afrank_scheiner%3Agct&package=globus-common) for the `globus-common` package (which are also valid for the other packages).

****

All details about this release can also be found on the [corresponding GitHub releases page](https://github.com/gridcf/gct/releases/tag/v6.2.20190226)

### [2018-11-15](#2018-11-15) ###

#### GCT version 6.2.20181115 (first 6.2 release) ####

The GridCF is pleased to announce the release of the GCT version 6.2.20181115, the first GCT 6.2 release.

**Packages are available from:**

* [Debian](https://www.debian.org/) (for Debian unstable (Sid), excluding gsi-openssh)

* [EPEL](https://fedoraproject.org/wiki/EPEL) (for Red Hat Enterprise Linux, CentOS and Scientific Linux 6 and 7)

* [Fedora](https://fedoraproject.org/) (for Fedora 28 and 29)

> **NOTICE:** As a preview, packages (excluding gsi-openssh) are now also available from the [OpenSUSE Build Service ](https://build.opensuse.org/project/show/home:frank_scheiner:gct) (for SLES 12 (SP3), 12 (SP4), 15 and OpenSUSE Leap 15.0, 15.1 and OpenSUSE Tumbleweed). To install follow [these exemplary instructions](https://software.opensuse.org//download.html?project=home%3Afrank_scheiner%3Agct&package=globus-common) for the `globus-common` package (which are also valid for the other packages).

****

All details about this release can also be found on the [corresponding GitHub releases page](https://github.com/gridcf/gct/releases/tag/v6.2.20181115)

### [2018-10-30](#2018-10-30) ###

Grid Community Toolkit packages are now available in Fedora 29 stable, too.

- Fedora 29:
<https://bodhi.fedoraproject.org/updates/FEDORA-2018-f9acba9316>

### [2018-10-16](#2018-10-16) ###

Grid Community Toolkit packages are now available in EPEL stable and Fedora 28 stable.

- EPEL 6:  
<https://bodhi.fedoraproject.org/updates/FEDORA-EPEL-2018-d19f4f231e>

- EPEL 7:  
<https://bodhi.fedoraproject.org/updates/FEDORA-EPEL-2018-8aebaba2a9>

- Fedora 28:
<https://bodhi.fedoraproject.org/updates/FEDORA-2018-b36a6d2d0d>

### [2018-09-24](#2018-09-24) ###

Package updates based on the Grid Community Toolkit are now available in EPEL testing, Fedora updates testing and Debian unstable and testing.

- EPEL 6:  
<https://bodhi.fedoraproject.org/updates/FEDORA-EPEL-2018-d19f4f231e>

- EPEL 7:  
<https://bodhi.fedoraproject.org/updates/FEDORA-EPEL-2018-8aebaba2a9>

- Fedora 28:  
<https://bodhi.fedoraproject.org/updates/FEDORA-2018-b36a6d2d0d>

- Fedora 29:  
<https://bodhi.fedoraproject.org/updates/FEDORA-2018-f9acba9316>

- Debian:  
<https://qa.debian.org/developer.php?login=mattias.ellert@physics.uu.se>
