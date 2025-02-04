---
title: "SQL Server and Azure VM"
theme: default
---

## Table of Contents
1. [SQL Server and Azure Virtual Machines](#sql-server-and-azure-virtual-machines)
2. [When to run a SQL Server on a VM](#when-to-run-a-sql-server-on-a-vm)
3. [Backups](#backups)
4. [Azure Resource Management](#azure-resource-management)
5. [Azure Storage](#azure-storage)

# SQL Server and Azure Virtual Machines

>NOTE
>*laas* are SQL servers running on Azure virtual machines.

### When to run a SQL Server on a VM:

- When there is incompatibility with your projects.  For example, if you are working with a third party that is using an older version of a SQL Server.
- Using other SQL Server Services.  Such as:
  | Name | Service |   
  | --- | ----- |
  | SSAS | SQL Server Analysis Services |
  | SSIS | SQL Server Integration Services |
  | SSRS | SQL Server Reporting Services |

### Backups

Sometimes you need to back up your data!  There are two services Azure offers:

- **Back up to URL**: standard backup syntax
- **Azure Backup**: more complete services; offers automated backups

### Azure Resource Management

This is a service that allows deployment for cloud services and manages databases.  All Azure resources will end up as JSON documents known as _Azure Resource Manager_ templates.  It gives all information needed for deployment.

### Azure Storage

Four types:
- Standard
- Standard SSD
- Premium SSD
- Ultra Disk

