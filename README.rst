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
        | |landscape| |scrutinizer|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/powerline-rbenv/badge/?style=flat
    :target: https://readthedocs.org/projects/powerline-rbenv
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/seanfisk/powerline-rbenv.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/seanfisk/powerline-rbenv

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/seanfisk/powerline-rbenv?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/seanfisk/powerline-rbenv

.. |requires| image:: https://requires.io/github/seanfisk/powerline-rbenv/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/seanfisk/powerline-rbenv/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/seanfisk/powerline-rbenv/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/seanfisk/powerline-rbenv

.. |landscape| image:: https://landscape.io/github/seanfisk/powerline-rbenv/master/landscape.svg?style=flat
    :target: https://landscape.io/github/seanfisk/powerline-rbenv/master
    :alt: Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/powerline-rbenv.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/powerline-rbenv

.. |downloads| image:: https://img.shields.io/pypi/dm/powerline-rbenv.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/powerline-rbenv

.. |wheel| image:: https://img.shields.io/pypi/wheel/powerline-rbenv.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/powerline-rbenv

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/powerline-rbenv.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/powerline-rbenv

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/powerline-rbenv.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/powerline-rbenv

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/seanfisk/powerline-rbenv/master.svg?style=flat
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/seanfisk/powerline-rbenv/


.. end-badges

Powerline segments for rbenv/pyenv/plenv

* Free software: BSD license

Installation
============

::

    pip install powerline-rbenv

Documentation
=============

https://powerline-rbenv.readthedocs.org/

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
