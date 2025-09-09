============================================================
surface_filling_curves: Surface-filling-curves
============================================================

.. start-badges

.. image:: https://img.shields.io/badge/License-MIT-blue.svg
    :target: https://github.com/augmentedfabricationlab/surface_filling_curves/blob/master/LICENSE
    :alt: License MIT

.. image:: https://travis-ci.org/augmentedfabricationlab/surface_filling_curves.svg?branch=master
    :target: https://travis-ci.org/augmentedfabricationlab/surface_filling_curves
    :alt: Travis CI

.. end-badges

.. Write project description

**This project contains a reimplementation of Yuta Nomas surface-filling-curve-algorithm via medial axis energy. It uses the original codebase to enerate a .dll that can be called from Grasshoppe's scripting components. The example .ghx file uses the .dll in the C# scripting component of grasshopper.** ...


Main features
-------------

* Generate Surface-filling-curves on manifold triangle meshes. 
* Adjust density, smoothness of the curves, 
* Additionally to the original implementation, includes fixed curves, that influence curve evolution, but themselves do not evolve.


Requirements
------------

Once you download this repository you can run the code inside the example .ghx file in the Rhino folder.

Installation
------------


Go into surface_filling_curves_in_rhino\build\bin\Debug and copy the sfc.dll into the libraries folder C:\Users\<YourUsername>\AppData\Roaming\Grasshopper\Libraries. 
Now you can use the example_file.ghx in the Rhino folder.


Credits
-------------

This package was created by Merlin Bieling <merlin.bieling@tum.de> `@MerlinBieling <https://github.com/MerlinBieling>`_ at `@augmentedfabricationlab <https://github.com/augmentedfabricationlab>`_
