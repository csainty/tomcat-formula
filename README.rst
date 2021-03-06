======
tomcat
======

Formula to set up and configure tomcat webserver

.. note::

    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html>`_.

Available states
================

.. contents::
    :local:

``tomcat``
----------

Includes tomcat.package for the Tomcat install.

``tomcat.native``
-----------------

Installs Apache Portable Runtime for Tomcat.

``tomcat.manager``
-----------------

Installs the host-manager and manager web applications for Apache Tomcat.

``tomcat.package``
------------------

Installs the Tomcat package, and configures the configuration file.

``tomcat.vhosts``
------------------

Configures Tomcat name-based virtual hosts using data from Pillar.

``tomcat.ssl``
------------------

Enables SSL in tomcat.

Formula Dependencies
====================

* java
