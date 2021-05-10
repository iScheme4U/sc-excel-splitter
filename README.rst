.. image:: https://badge.fury.io/py/sc-excel-splitter.svg
    :target: https://badge.fury.io/py/sc-excel-splitter
.. image:: https://img.shields.io/pypi/pyversions/sc-excel-splitter
    :alt: PyPI - Python Version

A simple Python project sample structure
========================================

This project provides a sample structure for creating python project.


Installation
------------

It is possible to install the tool with `pip`::

    pip install sc-excel-splitter

Configuration
-------------

First, make sure /var/opt/sc directory exists, if not create this directory and make sure current user has the right
to create files in this directory.

You can copy `default.yml <https://github.com/Scott-Lau/sc-excel-splitter/blob/master/excel/tests/sample_config/default.yml>`_
to /var/opt/sc/.sc-excel-splitter/production.yml to initialize the production configuration.

The default configuration file looks like this::

    dev:
      # whether this program is running is development mode
      dev_mode: False

License
-------

The script is released under the MIT License.  The MIT License is registered
with and approved by the Open Source Initiative [1]_.

.. [1] https://opensource.org/licenses/MIT