CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Dependencies
 * Installation
 * Author

INTRODUCTION
------------

The FileField Role Limit module is an extension of CCK FileField module and 
adds the capability to limit the max upload file size for each different role.

The Filefield Role Limit module create new settings for each FileField field 
to define single file upload max size or the whole uploaded files size in a 
single node.
Different limit values can be provided for each role and the module will 
automatically switch to default FileField max upload size behavior if no 
settings per role are provided.

The Filefield Role Limit module works also with ImageField module.

DEPENDENCIES
------------
 * Content (http://drupal.org/project/cck)
 * Filefield (http://drupal.org/project/filefield)

FileField Role Limit module can also work with the following:

 * ImageField (http://drupal.org/project/imagefield)
 * FileField Sources (http://drupal.org/project/filefield_sources)

INSTALLATION
------------

1) Copy the Filefield folder to the modules folder in your installation.

2) Copy the FileField Role Limit folder to the modules folder in your 
   installation.

3) Enable Filefield and FileField Role Limit modules using 
   Administer -> Site building -> Modules(/admin/build/modules).

4) Create a new file field in through CCK's interface. 
   Visit Administer -> Content management -> Content types 
   (admin/content/types), then click "Manage fields" on the type you want to 
   add a file upload field. Select "File" as the field type and "File" as the 
   widget type to create a new field.

5) In new file field settings, open "File size restrictions" fieldset.
   Inside this fieldset you'll be able to set a default upload limit size per
   file and per node. If you need to set a different limit for a particular 
   role, open the inner fieldsets "Maximum upload size per file per role" and
   Maximum upload size per node per role. Set the value for the roles you 
   need to.

6) Upload files on the node form for the type that you set up.

AUTHOR
------

Alberto Colella
http://drupal.org/user/460740

Contacs:
http://drupal.org/user/460740/contact
kongoji@gmail.com
