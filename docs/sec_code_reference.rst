==============
Code reference
==============

.. toctree::
  :maxdepth: 2


bg_estimate (background-estimation)
===================================

Constants
---------
.. autodata:: qpimage.bg_estimate.VALID_FIT_OFFSETS 
.. autodata:: qpimage.bg_estimate.VALID_FIT_PROFILES

Methods
-------
.. automodule:: qpimage.bg_estimate
   :exclude-members: VALID_FIT_OFFSETS, VALID_FIT_PROFILES
   :members:
   :undoc-members:


core (QPImage)
==============

Constants
---------
.. autodata:: qpimage.core.VALID_INPUT_DATA


Classes
-------
.. autoclass:: qpimage.core.QPImage
   :members:
   :undoc-members:


Methods
-------
.. autofunction:: qpimage.core.copyh5


holo (hologram analysis)
========================

Methods
-------
.. automodule:: qpimage.holo
   :members:
   :undoc-members:


image_data (basic image management)
===================================

Constants
---------
.. autodata:: qpimage.image_data.COMPRESSION
.. autodata:: qpimage.image_data.VALID_BG_KEYS


Classes
-------
.. automodule:: qpimage.image_data
   :members: Amplitude, Phase
   :undoc-members:
   :show-inheritance:
.. autoclass:: qpimage.image_data.ImageData
   :members:
   :undoc-members:


integrity_check (check QPImage data)
====================================

Exceptions
----------
.. autoexception:: qpimage.integrity_check.IntegrityCheckError

Methods
-------
.. automodule:: qpimage.integrity_check
   :exclude-members: IntegrityCheckError
   :members:
   :undoc-members:


meta (definitions for QPImage meta data)
========================================

Constants
---------
.. autodata:: qpimage.meta.META_KEYS

Exceptions
----------
.. autoexception:: qpimage.meta.MetaDataMissingError

Classes
-------
.. autoclass:: qpimage.meta.MetaDict
   :members:
   :undoc-members:
   :show-inheritance:


series (QPSeries)
=================

Classes
-------
.. autoclass:: qpimage.series.QPSeries
   :members:
   :undoc-members:
