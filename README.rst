OPETH
=====

More detailed documentation: https://opeth.readthedocs.io/

.. rtd-inclusion-marker-do-not-remove

Online Peri-Event Time Histogram for `Open Ephys <http://www.open-ephys.org/gui>`_.

OPETH visualizes Peri-Event Time Histograms (PETH) of spikes detected in raw Open Ephys data, 
broadcasted via `ZeroMQ <https://zeromq.org>`_. PETH is aligned to triggers from Open Ephys.

Quickstart
----------

- OPETH requires `ZMQInterface plugin <https://github.com/open-ephys-plugins/zmq-interface>`_. 
  It is part of Open Ephys from version 0.6.7 up.
- Set up Open Ephys with ZMQInterface plugin. The ZMQ plugin is recommended to be put after bandpass 
  filter and/or common average reference filter in the Open Ephys signal chain, while spike detector filter is not required.
- Start with the ``opeth`` command when using the pip package or start with ``python opeth/gui.py`` when running from sources (see below).

Installation
------------

... under construction ...

Dependencies
^^^^^^^^^^^^

Required non-default packages: ``pyzmq``, ``pyqtgraph`` plus one of the qt versions for pyqtgraph, preferably ``PyQt5``,
and also their dependencies (e.g. ``numpy``), see ``requirements.txt``.

Running from sources
--------------------

After cloning the git repository or extracting a source zip file, multiple methods could work.

Setting up python environment with conda
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

... under construction ...

Setting up python environment with pip
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Python dependencies can be installed with the command

::

    pip install -r requirements.txt


