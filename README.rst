==============================
Local GAE development skeleton
==============================

Disclaimer
==========

This is a basic skeleton for GAE projects I've made.
Feel free to use, adopt and contribute if you have ideas on how to
improve my experience. Any help is welcome.

Quick usage reference
=====================

1. Clone the contents of this repository somewhere you keep your project's
   sources:

   ``git clone git://github.com/nimnull/gae-skeleton.git <project name>``

   Dont forget to replace *<project name>* with the appropriate project's
   title.

#. Change the current dir to the one you've cloned this repo.

#. Adjust ``eggs =`` section with the packages you suppose to use with
   your project.

#. Place your project's source file under the ``app`` directory. Create it 
   manually or just clone your existing repo somehow like this:
   ``git clone <your repository URL> app``
   Then run ``mkdir -p app/lib/dist``.

#. Ensure that you have zc.buildout_ installed system-wide or in your
   virtual environment in case you are using sort of it.

#. Run buildout tool under the directory you've clone gae-skeleton in.

#. ...

#. **PROFIT!!!**

:Authors:
        Yegor Nazarkin

:Contacts:
        http://twitter.com/nimnull

.. _zc.buildout: http://www.buildout.org/
