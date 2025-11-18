---
title: "Week of July 2, 2025"
date: 2020-07-02
taxonomy:
    products:
        - patch-my-pc-cloud
---

#### New Features

**Portal**

* **New “Items per page” options –** We’ve added new values to the **Items per page** dropdown in the portal to allow you to choose to display more items per page in the portal.
* **Increased character limits –** We now support 2,048 characters in the following fields:
  * Install Parameters Additional Argument
  * Silent Install Parameters
  * Additional Silent Uninstall Parameters

**Custom Apps**

* **Version number replaced with “%” –** Now, when you add a Primary Install File that is an MSI, when populating the various properties, if we detect a version number in the **Apps & Features Name** field, we replace it with a "**%**".

#### Fixes

**Discovery**

* Resolved an issue where if a single Intune discovered app was mapped to two different products from our App Catalog, and one of them was managed and the other was unmanaged, one of them would appear under the **Managed** tab and the other would appear in the **Unmanaged** tab.\
  \
  Now, if one of them is managed and the other is unmanaged, the managed app is displayed in the **Managed** tab and the unmanaged app is hidden in the **Unmanaged** tab.\\

**Custom Apps**

* Resolved an issue with a Custom Apps icon not being shown in a webhook when its deployment is updated via Sync Schedule.

**Managed Service Provider**

* Resolved an issue with an MSP not being able to unlink a child customer if their license had expired.
