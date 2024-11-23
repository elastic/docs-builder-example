---
title: Create an Elastic Cloud hosted deployment
---

```{note}
This page applies to the current Elastic Cloud Hosted environment.
```

An Elastic Cloud deployment includes Elastic Stack components such as Elasticsearch, Kibana, and other features, allowing you to store, search, and analyze your data.
You can spin up a proof-of-concept deployment to learn more about what Elastic can do for you.

To explore Elasticsearch Service and its solutions, create your first deployment by following one of these getting started guides.
If you are instead interested in serverless Elastic Cloud, check the serverless documentation.

You can also create a deployment using the Elastic Cloud API.
This can be an interesting alternative for more advanced needs, such as for creating a deployment encrypted with your own key.

. Log in to your cloud.elastic.co account and select Create deployment from the Elasticsearch Service main page. Once you are on the Create deployment page, you can create the deployment with the defaults assigned, where you can edit the basic settings, or configure more advanced settings.
. From the main Settings, you can change the cloud provider and region that host your deployment, the stack version, and the hardware profile, or restore data from another deployment (Restore snapshot data).
. Expand Advanced settings to configure your deployment for encryption using a customer-managed key, autoscaling, storage, memory, and vCPU. Check Customize your deployment for more details.
  Trial users won’t find the Advanced settings when they create their first deployment. This option is available on the deployment’s edit page once the deployment is created.

. Select Create deployment. It takes a few minutes before your deployment gets created. While waiting, you are prompted to save the admin credentials for your deployment which provides you with superuser access to Elasticsearch. Keep these credentials safe as they are shown only once. These credentials also help you add data using Kibana. If you need to refresh these credentials, you can reset the password.
. Once the deployment is ready, select Continue to open the deployment’s main page. From here, you can start ingesting data or simply try a sample data set to get started.

At any time, you can manage and adjust the configuration of your deployment to your needs, add extra layers of security, or (highly recommended) set up health monitoring.