---
title: "Synchronizing Project for the web tasks with Planner and To Do"
ms.author: sourabhsharma
author: SourabhSharma
manager: sandes
ms.date: 04/17/2024
audience: admin
ms.topic: article
ms.service: project-web
ms.localizationpriority: medium
description: "Learn how to enable/disable Project for the web task syncing with Planner and To Do."
---

# Synchronize Project for the web tasks with Planner and To Do 

By default, Project for the web tasks with Planner and To Do is enabled for all tenants. This means that the Assigned to me view in Planner and To Do will display all Microsoft 365 tasks assigned to a user. 

However, there may be instances when disabling this synchronization at the tenant level would be helpful, such as if you require your data for Project for web and Planner to exist in two different data boundaries. 

## Admin controls to enable or disable synchronization

An admin can enable or disable Project for the web task synchronization with Planner and To Do for all users in their organization through the Project settings page in the Microsoft 365 admin center. 

Use the following steps to Enable or Disable Project for the web Task Syncing: 

1. In the Microsoft 365 admin center, expand the navigation menu, select **Settings**, and then select **Org Settings**. 
2. Select **Project**. 
3. On the Project settings page, select or clear the checkbox **Turn on Assigned to me view syncing for your organization**, and then select **Save**. 

> In order for Project for the web task to synchronize with Planner and To Do tasks, Project for the web must be enabled for the tenant. If the administrator decides to disable it, tasks won't be synchronized and no new data will be copied to Planner and To Do. Note that previously stored data won't be deleted until the Assigned to me view syncing is explicitly disabled for the tenant. 