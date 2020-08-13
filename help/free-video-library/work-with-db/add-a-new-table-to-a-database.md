
---
title: Add A New Table To A Database
description: Magento 2 has a special mechanism that enables you to create database tables, modify existing ones, and even add some data into them.
feature: Video Pages
topics: development, authoring
kt: 5613
doc-type: feature-video
activity: use
team: MagentoU
---
# Add A New Table To A Database

Magento 2 has a special mechanism that enables you to create database tables, modify existing ones, and even add some data into them - like setup data, which has to be added when a module is installed. This mechanism allows those changes to be transferable between different installations.

Rather than doing manual SQL operations repeatedly when reinstalling the system, developers create an install (or upgrade) script that contains the data. The script runs every time a module is installed.

#### Who is this video for?
* Developers

#### Video Content
* Create a new module
* Create InstallSchema Script
* Create InstallData Script
* Add new module and verify a table with data was created
* Create an UpgradeSchema script
* Create an UpgradeData script
* Run upgrade scripts and verify the table has changed

>[!VIDEO](https://video.tv.adobe.com/v/35791)

**Useful links:**
<br/>
[Add a New table to DataBase](https://devdocs.magento.com/videos/fundamentals/add-a-new-table-to-database/)
<br/>
[Migration Commands](https://devdocs.magento.com/guides/v2.4/extension-dev-guide/declarative-schema/migration-commands.html)