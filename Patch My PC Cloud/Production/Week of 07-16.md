---
title: "Week of July 16, 2025"
date: 2020-07-16
taxonomy:
    products:
        - patch-my-pc-cloud
---

#### Fixes

**Portal**

* Resolved an issue where if the macOS trial banner was closed for one PMPC Cloud Company, if you logged into another company, the banner was also disabled.
* Resolved an issue with overlapping elements in the portal if a resolution lower than 1324 x 724px was used.
* Resolved an issue where if you had the **Remember my Selection** checkbox checked on the sign in page, then signed out, and selected a different company to sign into, you were signed into the company that was remembered, not the new one you selected to sign into.

**Custom Apps**

* Resolved an issue with an app’s icon not being displayed in a webhook when the deployment of a Custom App is updated via the Sync Schedule.

**Intune Apps**

* Resolved an issue when running Discovery for a new PMPC Cloud Company generating an error, which was resolved by clicking **Refresh**.
* Resolved an issue with the sorting of apps in Discovery not working correctly.
* Resolved an issue with excluding an Entra ID group from Branding now working.

**Managed Service Provider**

* Resolved an issue with adding a scripts and arguments to an MSP App Sets not being saved, as when you edited the App Set, the script and it’s arguments were missing.