**************************
cosmoplotian Documentation
**************************

This is the documentation for ``cosmoplotian``.

``cosmoplotian`` is a small package that defines some useful options within
the ``matplotlib`` API. It does this in two main way:

* Provides a set of WCS projections using the :class:`astropy.visualization.wcsaxes.WCSAxes` 
  interface. These are designed to help plot ``HEALPix`` maps in both Galactic and ICRS frames.
* Provides a set of nice colormaps, integrated into the ``cmap`` API.

There are a few additional utility functions that can be imported and used, 
but mostly the package works behind the scenes in ``matplotlib``.


.. toctree::
  :maxdepth: 1
  
  /cosmoplotian/projections
  /cosmoplotian/colormaps

Reference/API
=============

.. automodapi:: cosmoplotian