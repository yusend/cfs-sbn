# cFS: Software Bus Network

[![GitHub release](https://img.shields.io/github/release/lassondesat/cfs-sbn.svg)](https://github.com/lassondesat/cfs-sbn/releases)

* [Original README](cfs-sbn-app-OSS-readme.txt)

## Description

The Software Bus Network application (SBN) is a core Flight System (cFS)
application that is a plug in to the Core Flight Executive (cFE) component of
the cFS.

The cFS is a platform and project independent reusable software framework and
set of reusable applications developed by NASA Goddard Space Flight Center. This
framework is used as the basis for the flight software for satellite data
systems and instruments, but can be used on other embedded systems. More
information on the cFS can be found at http://cfs.gsfc.nasa.gov

The SBN application extends the cFE Software Bus (SB) publish/subscribe
messaging service across partitions, processes, processors, and networks.

The SBN is prototype code and requires a patch to the cFE Software Bus code. The
patch is scheduled to be uploaded to this project COB 4/3/15.

## Requirements

* [Operating System Abstraction Layer][osal] 4.1.1 or higher
* [core Flight Executive][cfe] 6.4.1 or higher

## Sources

* https://sourceforge.net/projects/cfs-sbn/

[osal]: https://github.com/lassondesat/osal
[cfe]: https://github.com/lassondesat/coreflightexec
