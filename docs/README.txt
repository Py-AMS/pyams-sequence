======================
PyAMS sequence package
======================

.. contents::


What is PyAMS?
==============

PyAMS (Pyramid Application Management Suite) is a small suite of packages written for applications
and content management with the Pyramid framework.

**PyAMS** is actually mainly used to manage web sites through content management applications (CMS,
see PyAMS_content package), but many features are generic and can be used inside any kind of web
application.

All PyAMS documentation is available on `ReadTheDocs <https://pyams.readthedocs.io>`_; source code
is available on `Gitlab <https://gitlab.com/pyams>`_ and pushed to `Github
<https://github.com/py-ams>`_. Doctests are available in the *doctests* source folder.


What is PyAMS sequence?
=======================

PyAMS_sequence is a package based on classical Zope IntIds utility, but used to handle generation
of continuous sequences; in PyAMS, these sequences are used to identify, for example, contents
handled by workflows, all versions of a given content sharing the same identifier.

These identifiers are then used to create references to internal contents; workflow management
system then allows you to automatically reference the currently published version of a given
content.

Custom schemas fields and forms widgets are available to select internal references into
content management interface.
