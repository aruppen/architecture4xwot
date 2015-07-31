# Meta-Model For the eXtended Web of Things

This project contains the meta-modle for the eXtended Web of
Things. In order to work with it is important to get the right eclipse
distribution. To do so, download the _Eclipse Epsilon Distribution_.

On the a4xWoT.emf file -> right click -> Generate Ecore Model. This
will create a new file called a4xWoT.ecore which contais the
meta-model in eclipse's ecore language.

File -> New -> Other -> EMF Generator Model. Then select a file name
(a4xWoT.genmodel) and select _Ecore model_ as model importer. On the
next page, select the a4xWoT.ecore file and finish the process. This
creates a new file called a4xWoT.genmodel. Open it and expand the
first element until you see the Xwot element.

Right click on the Xwot element -> generate all. This generate the
eclipse plugins.

Right click on the src folder and choose Export... -> Deployable plug-ins und fragments -> select all the projects and export. This creates the jar files which can then be added to another Eclipse intstalltion to provide the xWoT editor.