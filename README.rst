============
tabletop_pta
============


.. image:: https://img.shields.io/pypi/v/tabletop_pta.svg
        :target: https://pypi.python.org/pypi/tabletop_pta

.. image:: https://img.shields.io/travis/nanograv/tabletop_pta.svg
        :target: https://travis-ci.org/nanograv/tabletop_pta

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

Note: That the PortAudio libraries are not installed when PyAudio (which depends
on PortAUdio) is installed. You must follow the instructions found in the link
above to install `PortAudio`.

Once `PortAudio` and `PyAudio` are installed you can install the `tabletop_pta`
package with a simple call to `pip`:

``pip install tabletop_pta``

Alternatively, one can install directly from the downloaded GitHub files. First
clone the repository.


``git clone https://github.com/nanograv/tabletop_pta.git``

Then go into the `tabletop_pta` directory and run


``python setup.py install``

Publication
-----------
This work is featured in a publication_, currently released on the ArXiv. If you
would like to reference this work please use the following attribution:

.. _publication: https://arxiv.org/abs/1803.05285

.. code-block:: tex

  @article{Lam:2018wbx,
        author         = "Lam, Michael T. and Romano, Joseph D. and Key, Joey S.
                          and Normandin, Marc and Hazboun, Jeffrey S.",
        title          = "{An Acoustical Analogue of a Galactic-scale
                          Gravitational-Wave Detector}",
        year           = "2018",
        eprint         = "1803.05285",
        archivePrefix  = "arXiv",
        primaryClass   = "physics.ed-ph",
        SLACcitation   = "%%CITATION = ARXIV:1803.05285;%%"
  }


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
