.. index:: Release notes


==============================
Release Notes of SlimerJS 0.10
==============================

version 0.10.0
==============

Still in development

New API
-------


Fixed bugs
----------

- Fixed configuration reading for script handlers (internal stuff)
- Callback given to ``webpage.open()`` is now really called after the page loading:
  it allows to call ``render()`` without a delay (``setTimeout``...)

Fixed PhantomJS conformance issues
----------------------------------

- a module should be able to call the ``return`` keyword

Other informations about this release
-------------------------------------



Missing APIS in SlimerJS 0.10
-----------------------------

Here are the PhantomJS 1.9 APIs that are missing in SlimerJS 0.10 but planed in future releases.

- some few options for the command line  and settings on the webpage object
  are not supported yet. Some of them are the possibility to deactivate
  SSL verification and Web security (CORS etc)
- no support of Ghost Driver (Selenium web driver)
- page rendering into PDF

You can read the `compatibility table <https://github.com/laurentj/slimerjs/blob/master/API_COMPAT.md>`_
to know details.

See also :doc:`the differences in APIs and behaviors <differences-with-phantomjs>` between
SlimerJS and PhantomJS.

Known issues
------------

- See `the github page <https://github.com/laurentj/slimerjs/issues>`_ ...

Contributors
------------


Previous release notes
======================

.. toctree::
   :maxdepth: 1

   release-notes-0.9
   release-notes-0.8
   release-notes-0.7
   release-notes-0.6

