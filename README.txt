Soar
====

Soar is a Drupal distribution that takes all of the cutting-edge Drupal 7 features and packages them together so they work out of the box. 
It integrates Twitter Bootstrap, Panels, Quickedit, and custom CKEditor configuration for a steamlined user-interface. It is the next-generation
of [Flight](http://drupal.org/project/flight).

Key Features
------------
+ Standardize your responsive design and theming workflow with Twitter Bootstrap and SASS mixins
+ Setup grunt to watch for SASS changes, auto-reload your browser, and check theme optimization
+ Panels in place editor for a nice page builder experience
+ Integrated media, CKEditor and Quickedit modules
+ Advanced CKEditor widgets for nice custom layouts


Installation
------------
Soar is fully packaged by Drupal.org and can be downloaded and installed on your own server similar to Drupal core.


Other Features
--------------
+ Beans for exportable blocks
+ Quickly create your sub-theme with Grunt (and no search and replace)
+ Bash scripts to install LiveReload so you don't need to hit F5 everytime you edit your SASS file
+ Administration Menu is used for superuser, while Toolbar is used for all other administration users
+ Easily add support for slideshows, event calendars, webforms (with form builder) and advanced workflows (with Workbench), by enabling optional features

Drupal Structure Document
-------------------------
Site planning is an essential part to any successful Drupal Build. ___ came up with an excellent
Google Docs spreadsheet template for planning content types, view, display modes and more.  We have
created a version of this structure document for all of the Soar features.  Use it to start your
planning for your next project:
https://docs.google.com/spreadsheet/ccc?key=0Alw0s_pQVmyXdFRwWmxLWnFfNHFSM1BSQkhsdG4wcmc&usp=sharing

Who
---
Soar was developed and is maintained by Albatross Digital. We use it as the starting-point for our projects.

Manually Building
-----------------
  drush verify-makefile drupal-org.make
  drush make --no-cache --drupal-org drupal-org.make tmp
  rsync -a tmp/* .
  rm -r tmp


