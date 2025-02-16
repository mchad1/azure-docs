---
title: Terraform samples for Azure Cosmos DB Core (SQL API)
description: Use Terraform to create and configure Azure Cosmos DB. 
author: ginsiucheng
ms.service: cosmos-db
ms.subservice: cosmosdb-sql
ms.topic: conceptual
ms.date: 09/16/2022
ms.author: gicheng
ms.reviewer: mjbrown
---

# Terraform for Azure Cosmos DB

[!INCLUDE[appliesto-sql-api](../includes/appliesto-sql-api.md)]

This article shows Terraform samples for Core (SQL) API accounts. 

## Core (SQL) API

|**Sample**|**Description**|
|---|---|
|[Create an Azure Cosmos account, database, container with autoscale throughput](manage-with-terraform.md#create-autoscale) | Create a Core (SQL) API account in two regions, a database and container with autoscale throughput. |
|[Create an Azure Cosmos account, database, container with analytical store](manage-with-terraform.md#create-analytical-store) | Create a Core (SQL) API account in one region with a container configured with Analytical TTL enabled and option to use manual or autoscale throughput. |
|[Create an Azure Cosmos account, database, container with standard (manual) throughput](manage-with-terraform.md#create-manual) | Create a Core (SQL) API account in two regions, a database and container with standard throughput. |
|[Create an Azure Cosmos account, database and container with a stored procedure, trigger and UDF](manage-with-terraform.md#create-sproc) | Create a Core (SQL) API account in two regions with a stored procedure, trigger and UDF for a container. |
|[Create an Azure Cosmos account with Azure AD identity, Role Definitions and Role Assignment](manage-with-terraform.md#create-rbac) | Create a Core (SQL) API account with Azure AD identity, Role Definitions and Role Assignment on a Service Principal. |
|[Create a free-tier Azure Cosmos account](manage-with-terraform.md#free-tier) |  Create an Azure Cosmos DB Core (SQL) API account on free-tier. |

## Next steps

Trying to do capacity planning for a migration to Azure Cosmos DB? You can use information about your existing database cluster for capacity planning.

* If all you know is the number of vcores and servers in your existing database cluster, read about [estimating request units using vCores or vCPUs](../convert-vcore-to-request-unit.md)
* If you know typical request rates for your current database workload, read about [estimating request units using Azure Cosmos DB capacity planner](estimate-ru-with-capacity-planner.md)
