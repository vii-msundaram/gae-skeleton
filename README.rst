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

2. Change the current dir to the one you've cloned this repo.

3. Place your project's source file under the ``app`` directory. Create it 
   manually or just clone your existing repo somehow like this:
   ``git clone <your repository URL> app``
   Then run ``mkdir -p app/lib/dist``.

4. Ensure that you have zc.buildout_ installed system-wide or in your
   virtual environment in case you are using sort of it.

5. Run buildout tool under the directory you've clone gae-skeleton in.

6. ...

7. **PROFIT!!!**

:Authors:
        Yegor Nazarkin

:Contacts:
        http://twitter.com/nimnull

.. _zc.buildout: http://www.buildout.org/
