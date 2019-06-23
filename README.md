FIB-SEM semi-automated ion beam milling

|build-status| |docs|

Installation
============

Install or upgrade to the latest version directly from GitHub with:

.. code-block::

   pip install git+https://github.com/DeMarcoLab/fibsem.git

You can check what version you're currently using in python:

.. code-block:: python

   import fibsem
   fibsem.__version__

Runing the program
==================

From ipython

.. code-block:: python

   import fibsem
   fibsem.run_milling(config='path/to/my/settings.yml')

Your settings.yml file should be based on the `default config settings file`_.

.. _default config settings file: (https://github.com/DeMarcoLab/fibsem/blob/develop/config_default.yml

Alternatively, your can launch the program directly From the command line:

.. code-block::

   python -m fibsem.main --config path/to/my/settings.yml

See all the command line options available with:

.. code-block::

   python -m fibsem --help


.. |build-status| image:: https://travis-ci.com/DeMarcoLab/fibsem.svg?branch=develop
    :alt: build status
    :target: https://travis-ci.com/DeMarcoLab/fibsem

.. |docs| image:: https://readthedocs.org/projects/fibsem/badge/?version=develop
    :alt: Documentation Status
    :target: https://fibsem.readthedocs.io/en/develop/?badge=develop
