---
title: "Week of July 30, 2025"
date: 2020-07-30
taxonomy:
    products:
        - patch-my-pc-cloud
    release-notes-type:
      - product-release
    release-notes-update-type:
      - new-feature
      - bug-fix
---

#### New Features

**Custom Apps**

* **Uninstall Arguments –** We’ve now added the ability for you to specify uninstall parameters for a Custom App.

**Intune Apps**

* **PMPC Scripts –** You can now see and disable any scripts we recommend for an app when you create a deployment.

**Managed Service Provider**

* **App Set Details –** You can now expand an App Set to see a list of the apps it contains and summary information for each app within the App Set.

#### Fixes

**Portal**

* Resolved an issue with Microsoft SQL Server Management Studio 21, where assignments could only be created to either install or update this app. Now we support both.

**Custom Apps**

* Resolved an issue when creating a Custom App containing files with duplicate names but different extensions (e.g. **setup.exe** and **setup.zip**), generating a duplicate filename error.

**Intune Apps**

* Resolved an issue where attempting to add an assignment to an existing deployment failed with a **400 Bad Request** error.

**Managed Service Provider**

* Resolved an issue where adding a Child MSP company to an App Set containing a Custom App resulted in the app being stuck with a status of **In Progress** on the Child Company.
* Resolved an issue where adding a Child MSP company generated a **Bad request** error.