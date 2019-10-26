========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - tests
      - | |travis|
        |
        | |codeclimate|
    * - package
      - | |commits-since|

.. |travis| image:: https://api.travis-ci.org/GabrielBG010/2019fa-csci-utils-GabrielBG010-2.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/GabrielBG010/2019fa-csci-utils-GabrielBG010-2

.. |codeclimate| image:: https://codeclimate.com/github/GabrielBG010/2019fa-csci-utils-GabrielBG010-2/badges/gpa.svg
   :target: https://codeclimate.com/github/GabrielBG010/2019fa-csci-utils-GabrielBG010-2
   :alt: CodeClimate Quality Status

.. |commits-since| image:: https://img.shields.io/github/commits-since/GabrielBG010/2019fa-csci-utils-GabrielBG010-2/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/GabrielBG010/2019fa-csci-utils-GabrielBG010-2/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

Installation
============

::

    pip install csci-utils2

You can also install the in-development version with::

    pip install https://github.com/GabrielBG010/2019fa-csci-utils-GabrielBG010-2/archive/master.zip


Documentation
=============


To use the project:

.. code-block:: python

    import csci_utils2
    csci_utils2.1()


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
