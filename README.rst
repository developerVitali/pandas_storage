========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/pandas_storage/badge/?style=flat
    :target: https://pandas_storage.readthedocs.io/
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/developerVitali/pandas_storage.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/developerVitali/pandas_storage

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/developerVitali/pandas_storage?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/developerVitali/pandas_storage

.. |requires| image:: https://requires.io/github/developerVitali/pandas_storage/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/developerVitali/pandas_storage/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/developerVitali/pandas_storage/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/developerVitali/pandas_storage

.. |version| image:: https://img.shields.io/pypi/v/pdstorage.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/pdstorage

.. |wheel| image:: https://img.shields.io/pypi/wheel/pdstorage.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/pdstorage

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pdstorage.svg
    :alt: Supported versions
    :target: https://pypi.org/project/pdstorage

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pdstorage.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/pdstorage

.. |commits-since| image:: https://img.shields.io/github/commits-since/developerVitali/pandas_storage/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/developerVitali/pandas_storage/compare/v0.0.0...master



.. end-badges

Read and Write pandas Dataframes to storage (Azure Blob, etc.)

* Free software: BSD 2-Clause License

Installation
============

::

    pip install pdstorage

You can also install the in-development version with::

    pip install https://github.com/developerVitali/pandas_storage/archive/master.zip


Documentation
=============


https://pandas_storage.readthedocs.io/


Development
===========

To run all the tests run::

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
