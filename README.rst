
Introduction
============

.. image:: https://readthedocs.org/projects/adafruit-circuitpython-vc0706/badge/?version=latest
    :target: https://docs.circuitpython.org/projects/vc0706/en/latest/
    :alt: Documentation Status

.. image :: https://img.shields.io/discord/327254708534116352.svg
    :target: https://adafru.it/discord
    :alt: Discord

.. image:: https://github.com/adafruit/Adafruit_CircuitPython_VC0706/workflows/Build%20CI/badge.svg
    :target: https://github.com/adafruit/Adafruit_CircuitPython_VC0706/actions/
    :alt: Build Status

CircuitPython module for use with the `VC0706 serial TTL camera <https://www.adafruit.com/product/397>`_.  Allows basic image capture and download of image data from the camera over a serial connection.  See examples for demo
of saving image to a SD card (must be wired up separately) or internally.

Dependencies
=============
This driver depends on:

* `Adafruit CircuitPython <https://github.com/adafruit/circuitpython>`_

Please ensure all dependencies are available on the CircuitPython filesystem.
This is easily achieved by downloading
`the Adafruit library and driver bundle <https://github.com/adafruit/Adafruit_CircuitPython_Bundle>`_.

Installing from PyPI
====================

On supported GNU/Linux systems like the Raspberry Pi, you can install the driver locally `from
PyPI <https://pypi.org/project/adafruit-circuitpython-vc0706/>`_. To install for current user:

.. code-block:: shell

    pip3 install adafruit-circuitpython-vc0706

To install system-wide (this may be required in some cases):

.. code-block:: shell

    sudo pip3 install adafruit-circuitpython-vc0706

To install in a virtual environment in your current project:

.. code-block:: shell

    mkdir project-name && cd project-name
    python3 -m venv .env
    source .env/bin/activate
    pip3 install adafruit-circuitpython-vc0706

Usage Example
=============

See examples/snapshot.py.

Documentation
=============

API documentation for this library can be found on `Read the Docs <https://docs.circuitpython.org/projects/vc0706/en/latest/>`_.

For information on building library documentation, please check out `this guide <https://learn.adafruit.com/creating-and-sharing-a-circuitpython-library/sharing-our-docs-on-readthedocs#sphinx-5-1>`_.

Contributing
============

Contributions are welcome! Please read our `Code of Conduct
<https://github.com/adafruit/Adafruit_CircuitPython_vc0706/blob/main/CODE_OF_CONDUCT.md>`_
before contributing to help this project stay welcoming.
