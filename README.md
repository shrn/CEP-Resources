Getting Started with the Creative Cloud Extension SDK
==============

This page provides resources you need to get started creating extensions for Adobe Creative Cloud applications, using the new HTML5/JavaScript interface model. The Flash/ActionScript interface model for extensions is deprecated in the Creative Cloud release; support has already been removed from CC2014 and later releases.

* Creative Cloud 2018 products include CEP 8 for developing extensions and add-ons. 

* Refer to https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_8.x/Documentation/CEP%208.0%20HTML%20Extension%20Cookbook.md#applications-integrated-with-cep for 2017 product integration with CEP 8.

* In the Creative Cloud 2015.x release in June 2016, Photoshop and Illustrator use CEP 7 while other applications still use CEP 6.1. Extensions and add-ins must be built on at least CEP 6 infrastructure.

* In the Creative Cloud 2015 release extensions and add-ins must be built on the CEP 6 infrastructure.

* In the Creative Cloud 2014 release, extensions and add-ins must be built on the CEP 5 infrastructure and loaded with Extension Manager. The current releases either do not now or soon will not support CEP 4 and Flash/ActionScript extensions.

* The Creative Suite 6 and the Creative Cloud 2013 releases of Adobe desktop applications support CEP 4, which allows you to build extensions using the older Flash/ActionScript interface model. However, the new HTML5/JavaScript model is preferred. It is recommended that you port existing Flash/ActionScript extensions to the new model.

This SDK provides the low-level tools that you need to build extensions. Extensions that you build using these tools must be packaged as ZXP files in order to be seen and loaded by Extension Manager. You can offer extensions as free or paid products through our marketing portals (Adobe Exchange, the Add-ins website, the Creative Cloud desktop app). When you do this, you upload the extension to Adobe as a single ZXP file.

Resources you will need include:
* CEP JavaScript libraries for communicating with the operating system and Extension Manager and for communicating with the host application and other extensions.
* Sample code for how to use these libraries
* The ZXP packager, a command-line utility

---


For developing CEP 5.x HTML/JavaScript extensions for CC2014 host applications

**Documentation**
* [Offical Adobe Extension SDK Documentation for CC 2014](http://adobe.ly/1rin38t)
* [CEP 5 HTML Extension Cookbook for CC 2014](https://github.com/Adobe-CEP/CEP-Resources/wiki/CEP-5-HTML-Extension-Cookbook-for-CC-2014)
* [CEP 5 Flash Extension Cookbook for CC 2014](https://github.com/Adobe-CEP/CEP-Resources/wiki/CEP-5-Flash-Extension-Cookbook-for-CC-2014)

**APIs** (https://github.com/Adobe-CEP/CEP-Resources/tree/master/CEP_5.x)
* Include these files in your extension project if you need to use the APIs.
  * AgoraLib.js
  * CSInterface.js
  * Vulcan.js
* Do NOT include this file in your extension project. It is already integrated into CEP.
  * CEPEngine_extensions.js
* Extension Manifest
  * ExtensionManifest_v_5_0.xsd
* PlugPlugExternalObject
  * [PlugPlugExternalObject for InDesign CC 2014](http://bit.ly/1qlnKOb)

**Samples**
* [Sample extensions](https://github.com/Adobe-CEP/Samples)

**Other Documents**
* [CEP for the InDesign Developer](http://adobe.ly/1xXkviH)
* [Extending Adobe CC 2014 apps using Node.js](http://bit.ly/1yAR0T9)
* [A short guide to HTML5 extensions](http://adobe.ly/Nk1EK7)
   (NOTE:  For CEP 4.0 but still mostly relevant)
* [Guide to signing extensions](http://adobe.ly/1oiS4FE)
   (NOTE:  For CEP 4.0 but valid for CEP 5)


----

Miscellaneous help
* [CS SDK Blog](https://blogs.adobe.com/cssdk/)
* [Andy Hall's Super Mega Guide (English)] (http://bit.ly/XQn9IV) [ (Japanese)] (http://bit.ly/XQnB9P)
* [Davide Barranca’s blog](http://www.davidebarranca.com/) and [HTML Panels Development Course](http://htmlpanelsbook.com/)
* [David Deraedt’s plugin for Adobe Brackets](http://bit.ly/QKWWYL)
* [Olav Martin Kvern's article on extensibility and InDesign](http://bit.ly/1zEa9Ef)
* [The other API (Article on Medium)](http://bit.ly/1hIFZay)
* [Adobe Exchange](http://bit.ly/1mHVksI)
* [Photoshop CC 2014 CEP samples by John Peterson](http://bit.ly/1nGAWYN)

----



