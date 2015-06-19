Tableau Plugin
==============
*Contributors:* Julie Repass (maid0marion), Ian Parker
* *Tags:* shortcode, embed, tableau
* *Tested versions:* 4.4.2

Description
===========
Php Shortcode to embed a Tableau Server View in a Wordpress page via Javascript API. Plus a shortcode button added to both the HTML and Visual editor.

Installation
============
1. Upload the 'tableau-plugin' folder to the directory used to store plugins (default is `/wp-content/plugins/`)
2. Activate the plugin through the 'Plugins' menu in WordPress

Uninstallation
==============
1. Remove the 'tableau-plugin' folder from the plugins directory in your Wordpress installation (default is `/wp-content/plugins/`).

Using the Plugin
================
The plugin adds a button to both the Visual and HTML editors to insert short code for embedding an interactive Tableau Server view.  For more information on using the Tableau plugin for Wordpress, please visit the [How to Use the Tableau Wordpress Plugin]( 
https://github.com/maid0marion/Tableau-Wordpress-Plugin/wiki/How-to-Use-the-Tableau-Wordpress-Plugin) wiki page.

Changelog
=========

19/06/2015 (IP)
---------------
* Support Trusted Authentication
* Use Javascript API
* Remove options that don't appear to be supported by JS API (Revert, Refresh and linktarget)

V1.01 - 23.03.2012
------------------
* Fixed bug for 'revert' parameter and added support for target URL parameter
* Tested code in 3.4.1 and fixed issue with closing tag in HTML editor

Upgrade Notice
==============
V1.01
-----
Updated parameter options and fixed issue with closing tag in HTML editor.

