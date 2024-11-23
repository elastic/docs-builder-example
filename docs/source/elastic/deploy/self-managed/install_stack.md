---
title: Install a self-managed Elastic Stack
---

```{note}
This page applies to the latest version of the Elastic Stack in an on-premise self-managed environment.
```

Install the Elastic Stack products you want to use in the following order:

. Elasticsearch 
. Kibana 
. Logstash 
. Elastic Agent or Beats 
. APM
. Elasticsearch Hadoop

Installing in this order ensures that the components each product depends on are in place.