---
title: Install Elasticsearch from an archive on Linux or MacOS
sub:
  'es': "Elasticsearch"
  'version': "8.16.1"
---

```{note}
This page applies to the latest version of the Elastic Stack in an on-premise self-managed environment.
```

{{es}} is available as a `.tar.gz` archive for Linux and MacOS.

The latest stable version of {{es}} can be found on the
[Download {{es}}](https://www.elastic.co/downloads/elasticsearch) page. Other
versions can be found on the [Past Releases page](https://www.elastic.co/downloads/past-releases).

## Download and install archive for Linux

The Linux archive for {{es}} v{{version}} can be downloaded and installed as follows:

```{code} sh
wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-{{version}}-linux-x86_64.tar.gz
wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-{{version}}-linux-x86_64.tar.gz.sha512
shasum -a 512 -c elasticsearch-{{version}}-linux-x86_64.tar.gz.sha512 <1>
tar -xzf elasticsearch-{{version}}-linux-x86_64.tar.gz
cd elasticsearch-{{version}}/ <2>
```
<1> Compares the SHA of the downloaded `.tar.gz` archive and the published checksum, which should output
    `elasticsearch-{{version}}-linux-x86_64.tar.gz: OK`.
<2> This directory is known as `$ES_HOME`.

## Download and install archive for MacOS

The MacOS archive for {{es}} v{{version}} can be downloaded and installed as follows:

```{code} sh
curl -O https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-{{version}}-darwin-x86_64.tar.gz
curl https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-{{version}}-darwin-x86_64.tar.gz.sha512 | shasum -a 512 -c - <1>
tar -xzf elasticsearch-{{version}}-darwin-x86_64.tar.gz
cd elasticsearch-{{version}}/ <2>
```

<1> Compares the SHA of the downloaded `.tar.gz` archive and the published checksum, which should output
    `elasticsearch-{{version}}-darwin-x86_64.tar.gz: OK`.
<2> This directory is known as `$ES_HOME`.


