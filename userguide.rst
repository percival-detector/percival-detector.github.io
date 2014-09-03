User Guide
==========

Cover topics:

* Startup.
* Acquire.
* Parameters.
* Scan.
* Process.
* View.
* Using with DAWN

Getting started: simple scan
----------------------------

A scan of a DAC parameter is a relatively simple task. The following demonstrate how
to achieve this with a single loop. The basic steps include:

* Instansiate a :class:`percivalui.percival.PercivalUI` object.
* Configure the :obj:`percivalui.percival.PercivalUI.data` instance to capture data into a file.
* Scan through a list of DAC values, and for each value command an acquisition of N frames.
* Wait for file saving to complete.
* Request the details of where the dataset was stored.
* Open dataset and start processing.

.. literalinclude:: percivalui/docs/simplescan_example.py

PercivalUI in DAWN
------------------

* Configuring dawn to pick up the python packages.
* Acquire data
* Plot results
* Example scan

