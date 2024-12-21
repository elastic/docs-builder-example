---
title: Ubuntu 22.04 LTS (Jammy Jellyfish)
---

```{versionadded} 3.7
Support for Ubuntu 20.04 LTS (Focal Fossa) was added in Elastic Cloud Enterprise 3.7.
```

The following instructions show you how to prepare your hosts on Ubuntu 22.04 LTS (Jammy Jellyfish).

1. Install Docker 24.0
1. Set up XFS quotas
1. Update the configurations settings
1. Configure the Docker daemon options

## Install Docker

Install Docker LTS version 24.0 for Ubuntu 20.04 or 22.04.

Make sure to use a combination of Linux distribution and Docker version that is supported, following our official Support matrix. Using unsupported combinations can cause multiple issues with you ECE environment, such as failures to create system deployments, to upgrade workload deployments, proxy timeouts, and more.

Docker 25 and higher are not compatible with ECE 3.7.

1. Install the Docker repository dependencies