========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor|
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/2019sp-pset-utils-elsalmi/badge/?style=flat
    :target: https://readthedocs.org/projects/2019sp-pset-utils-elsalmi
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/elsalmi/2019sp-pset-utils-elsalmi.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/elsalmi/2019sp-pset-utils-elsalmi

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/elsalmi/2019sp-pset-utils-elsalmi?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/elsalmi/2019sp-pset-utils-elsalmi

.. |version| image:: https://img.shields.io/pypi/v/pset-utils.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/pset-utils

.. |commits-since| image:: https://img.shields.io/github/commits-since/elsalmi/2019sp-pset-utils-elsalmi/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/elsalmi/2019sp-pset-utils-elsalmi/compare/v0.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/pset-utils.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/pset-utils

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pset-utils.svg
    :alt: Supported versions
    :target: https://pypi.org/project/pset-utils

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pset-utils.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/pset-utils


.. end-badges

"Utilties Library"

* Free software: BSD 2-Clause License

Installation
============

::

    pip install pset-utils

Documentation
=============


https://2019sp-pset-utils-elsalmi.readthedocs.io/


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
