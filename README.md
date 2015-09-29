ThreeSpace
==========

`threespace` is a Python library for interfacing with the [YEI 3-Space Sensor](http://www.yeitechnology.com/yei-3-space-sensor).

The code in `/threespace` (with the exception of `__init__.py`), `examples/`, and `try_port/` is taken directly from [3-Space Python API 2.0.2.3](http://www.yeitechnology.com/yei-3-space-application-programming-interface#down_and_doc) and has been packaged as a Python/PyPi library and hosted on GitHub in the hopes that this code be easier to install/use and encourage development by the community to improve the API.

The `threespace` package homepage is located at (https://github.com/Knio/threespace)


Installation
============

`threespace` can be installed via [pip](http://pypi.python.org/pypi/pip/):

    pip install threespace

It can also be installed manually by downloading/cloning this repository and running `setup.py`

    python setup.py install


Usage
=====

The `threespace` module exports `*` from YEI's `threespace_api.py` file.

    import threespace
    device = threespace.TSUSBSensor(com_port="COM12")


*NOTE*: The official module is called `threespace_api`, while this module is called `threespace`, so you may have to change import statements if you're using both.
