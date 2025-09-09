============================================================
surface_filling_curves_in_rhino: Surface_filling_curves_in_Rhino
============================================================

.. start-badges

.. image:: https://img.shields.io/badge/License-MIT-blue.svg
    :target: https://github.com/augmentedfabricationlab/surface_filling_curves_in_rhino/blob/master/LICENSE
    :alt: License MIT

.. image:: https://travis-ci.org/augmentedfabricationlab/surface_filling_curves_in_rhino.svg?branch=master
    :target: https://travis-ci.org/augmentedfabricationlab/surface_filling_curves_in_rhino
    :alt: Travis CI

.. end-badges

.. Write project description

**This project contains a reimplementation of Yuta Nomas surface-filling-curve-algorithm via medial axis energy. It uses the original codebase to enerate a .dll that can be called from Grasshoppe's scripting components. The example .ghx file uses the .dll in the C# scripting component of grasshopper.** ...


Main features
-------------

* feature
* feature
* more features

**surface_filling_curves_in_rhino** runs on Python x.x and x.x.


Documentation
-------------

.. Explain how to access documentation: API, examples, etc.

..
.. optional sections:

Requirements
------------

.. Write requirements instructions here


Installation
------------

.. Write installation instructions here


Contributing
------------

Make sure you setup your local development environment correctly:

* Clone the `surface_filling_curves_in_rhino <https://github.com/augmentedfabricationlab/surface_filling_curves_in_rhino>`_ repository.
* Install development dependencies and make the project accessible from Rhino:

::

    pip install -r requirements-dev.txt
    invoke add-to-rhino

**You're ready to start working!**

During development, use tasks on the
command line to ease recurring operations:

* ``invoke clean``: Clean all generated artifacts.
* ``invoke check``: Run various code and documentation style checks.
* ``invoke docs``: Generate documentation.
* ``invoke test``: Run all tests and checks in one swift command.
* ``invoke add-to-rhino``: Make the project accessible from Rhino.
* ``invoke``: Show available tasks.

For more details, check the `Contributor's Guide <CONTRIBUTING.rst>`_.


Releasing this project
----------------------

.. Write releasing instructions here


.. end of optional sections
..

Credits
-------------

This package was created by Merlin Bieling <merlin.bieling@tum.de> `@merlinbb <https://github.com/merlinbb>`_ at `@augmentedfabricationlab <https://github.com/augmentedfabricationlab>`_
