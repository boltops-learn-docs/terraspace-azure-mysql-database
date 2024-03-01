<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-azure-mysql-database/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraspace Azure MySQL Database

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

This contains example code that creates:

* Azure MySQL Database

It uses:

* [azurerm_mysql_server](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/mysql_server)

## Env Vars

You should configure these env vars:

* ARM_CLIENT_ID
* ARM_CLIENT_SECRET
* ARM_SUBSCRIPTION_ID
* ARM_TENANT_ID

As covered in: [Terraspace Azure Getting Started Docs: Configure Azure](https://terraspace.cloud/docs/learn/azure/configure/)

## Deploy

To deploy:

    terraspace up mysql

## Video

[![Watch the video](https://uploads-learn.boltops.com/lxo869pq3h0gqc31yo0pn8a5eww3)](https://learn.boltops.com/courses/terraspace-azure/lessons/terraspace-azure-mysql-database)

Note: Premium video content requires a subscription.
