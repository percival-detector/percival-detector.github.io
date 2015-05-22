.. Percival documentation master file, created by
   sphinx-quickstart on Thu Aug 26 14:31:32 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Percival Software documentation
===============================

The Percival detector project software documentation is maintained on these pages.

Introduction...

Guides and manuals
------------------

.. toctree::
   :maxdepth: 2

   architecture
   installation
   userguide
   frame-receiver
   reference-percivalui
   
Developers Documentation
------------------------

The Percival software project comprise a number of software packages, designed to
support the different aspects of running the Percival detector system. The packages
are carefully designed to be as de-coupled as possible due to the nature of developing
across multiple teams.

The following sections collect the developers documentation into one central area.

PercivalUI Python documentation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The PercivalUI module contains python packages which are used to provide a
user interface to the Percival detector in the form of a python class/object.

Frame Grabber documentation
^^^^^^^^^^^^^^^^^^^^^^^^^^^

The frame grabber application operate as a service on each of the compute nodes,
capturing incoming image frames from the hardware boards and distribute them into
FIFO buffers, which are then read by the processing applications.

Frame Processing applications
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The live processing applications run on each of the compute nodes, processing data
from FIFO buffers (filled by the Frame Grabber) and eventually write the resulting
frames out to HDF5 files.
 

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

