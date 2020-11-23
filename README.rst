.. This README is meant for consumption by humans and pypi. Pypi can render rst files so please do not use Sphinx features.
   If you want to learn more about writing documentation, please check out: http://docs.plone.org/about/documentation_styleguide.html
   This text does not appear on pypi or github. It is a comment.

.. image:: https://travis-ci.org/collective/collective.debug.svg?branch=master
    :target: https://travis-ci.org/collective/collective.debug

.. image:: https://coveralls.io/repos/github/collective/collective.debug/badge.svg?branch=master
    :target: https://coveralls.io/github/collective/collective.debug?branch=master
    :alt: Coveralls

.. image:: https://img.shields.io/pypi/v/collective.debug.svg
    :target: https://pypi.python.org/pypi/collective.debug/
    :alt: Latest Version

.. image:: https://img.shields.io/pypi/status/collective.debug.svg
    :target: https://pypi.python.org/pypi/collective.debug
    :alt: Egg Status

.. image:: https://img.shields.io/pypi/pyversions/collective.debug.svg?style=plastic   :alt: Supported - Python Versions

.. image:: https://img.shields.io/pypi/l/collective.debug.svg
    :target: https://pypi.python.org/pypi/collective.debug/
    :alt: License


================
collective.debug
================

collective.debug provide a ``@debug`` view for analyzing and debugging purposes.

Warning
--------

Use this add-on with care because it may expose unwanted information. Use it
for debugging and analyzing purposes only. Do not use it production.


Installation
------------

Install collective.debug by adding it to your buildout::

    [buildout]

    ...

    eggs =
        collective.debug


and then running ``bin/buildout``

Usage
-----

This add-on provides a ``@@debug`` browser view that returns some debugging information
on the current context object, the current user and its roles, the instance dict of the
current context object and request information.


Contribute
----------

- Issue Tracker: https://github.com/collective/collective.debug/issues
- Source Code: https://github.com/collective/collective.debug
- Documentation: https://docs.plone.org/foo/bar


License
-------

The project is licensed under the GPLv2.

Author
------

Andreas Jung (info@zopyx.com)
