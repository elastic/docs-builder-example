---
title: Ubuntu 18.04 LTS (Bionic Beaver)
---

```{deprecated} 3.6
Support for Ubuntu 18.04 LTS (Bionic Beaver) was removed in Elastic Cloud Enterprise 3.7.
```

The following instructions show you how to prepare your hosts on 18.04 LTS (Bionic Beaver).

. Check the supported Linux kernel
. Install Docker 18.09.9
. Set up XFS quotas
. Update the configurations settings
. Configure the Docker daemon options
. Check the supported Linux kernel
. Elastic Cloud Enterprise requires 3.10 or higher, except between 4.4.156 and 4.9. To check your kernel version, run uname -r.

## Install Docker

Install Docker LTS version 19.03 for Ubuntu 18.04