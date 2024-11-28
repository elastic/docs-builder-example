---
title: Ubuntu 20.04 LTS (Focal Fossa)
---

```{versionadded} 3.3
Elastic Cloud Enterprise 3.3 and later support Ubuntu 20.04 LTS (Focal Fossa).
```

The following instructions show you how to prepare your hosts on 20.04 LTS (Focal Fossa) and Ubuntu 22.04 LTS (Jammy Jellyfish).

. Install Docker 24.0
. Set up XFS quotas
. Update the configurations settings
. Configure the Docker daemon options

## Install Docker

Install Docker LTS version 24.0 for Ubuntu 20.04 or 22.04.

Make sure to use a combination of Linux distribution and Docker version that is supported, following our official Support matrix. Using unsupported combinations can cause multiple issues with you ECE environment, such as failures to create system deployments, to upgrade workload deployments, proxy timeouts, and more.

Docker 25 and higher are not compatible with ECE 3.7.

. Install the Docker repository dependencies