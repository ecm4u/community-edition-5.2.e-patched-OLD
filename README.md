Alfresco 5.2.e-patched
======================

This is a patched version of Alfresco 5.2.e, based on [the subversion tag](https://svn.alfresco.com/repos/alfresco-open-mirror/alfresco/COMMUNITYTAGS/5.2.e/). The following changes have been made.

* Don't build the module `legacy-lucene`.
* ~~Patched `QuickShareServiceImpl.java` to work correctly in a multi-tenant setup.~~
* ALF-21521: Disable the Global Authentication Filter.
* ALF-21749: Catch missing name parts of site manager in admin FTL.

You can create a diff to the tag `5.2.e` by executing 

    $ ./diff-to-tag.sh

This will create a file `../community-edition-5.2.e.diff`.
