OMERO.webpublic
===============
Open Microscopy Environment webpublic OMERO.web extension application.

Requirements
============

* OMERO 4.4.0 or later

Development Installation
========================

Clone the repository in to your OMERO.web installation:

    cd components/tools/OmeroWeb/omeroweb/
    git clone git://github.com/openmicroscopy/webpublic.git
    path/to/bin/omero config set omero.web.apps '["webpublic"]'

Now start up OMERO.web as normal in your development environment.

Production Installation
=======================

Install the latest version of OMERO.server and OMERO.web and then:

    cd $OMERO_HOME/lib/python/omeroweb
    wget -O master.zip https://github.com/openmicroscopy/webpublic/zipball/master
    unzip master.zip
    mv openmicroscopy-webpublic-* webpublic
    path/to/bin/omero config set omero.web.apps '["webpublic"]'

You can then configure OMERO.webpublic as per normal:

* http://trac.openmicroscopy.org/ome/wiki/OmeroWebPublic

