============
tabletop_pta
============


.. image:: https://img.shields.io/pypi/v/tabletop_pta.svg
        :target: https://pypi.python.org/pypi/tabletop_pta

.. image:: https://img.shields.io/travis/Hazboun6/tabletop_pta.svg
        :target: https://travis-ci.org/Hazboun6/tabletop_pta

.. image:: https://readthedocs.org/projects/tabletop-pta/badge/?version=latest
        :target: https://tabletop-pta.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status




Python Package to do Time of Arrival calculations for a Pulsar Timing Array demonstration with metronomes.


* Free software: MIT license
* Documentation: https://tabletop-pta.readthedocs.io.

Installation
------------

Before installing the tabletop_pta demonstration software one should install the
audio software needed by tabletop_pta to record and playback the metronome
pulses. This includes PyAudio and the PortAudio c-libraries it is based on.

PyAudio: https://people.csail.mit.edu/hubert/pyaudio/ (And PortAudio Libraries)

After installing those requirements got to the directory where `~/tabletop_pta/`
can be found and run

`python setup.py install`

Features
--------

This software runs a set of Python scripts for finding the arrival time of metronome ticks.

One may use the various functions while running Python or use one of two
graphical user interfaces called with the commands:

`PTAdemo_single_metronome`

`PTAdemo_double_metronome`

Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
