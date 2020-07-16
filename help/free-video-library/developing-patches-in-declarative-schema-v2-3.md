
---
title: Developing patches in Declarative Schema v2.3
description: Creating a product attribute with a data patch
feature: Video Pages
topics: development, authoring
kt: 5559
doc-type: feature-video
activity: use
team: MagentoU
---
# Developing patches in Declarative Schema v2.3

To create a product attribute with a data patch we first need to create the class AddSimpleAttribute and implement DataPatchInterface. Next we need to instantiate the EavSetupFactory class within the constructor.

#### Who is this video for?
* Developers

**Declarative Schema was designed to simplify the Magento installation and upgrade processes. Previously, developers had to write database scripts in PHP for each new version of Magento. Various scripts were required for:**
* Installing and upgrading the database schema
* Installing and upgrading data
* Invoking other operations that are required each time Magento was installed or upgraded

>[!VIDEO](https://video.tv.adobe.com/v/35455)

**Useful links:**
<br/>
[Declarative Schema](https://devdocs.magento.com/guides/v2.4/extension-dev-guide/declarative-schema/)
<br/>
[Data Patches](https://devdocs.magento.com/guides/v2.4/extension-dev-guide/declarative-schema/data-patches.html)
