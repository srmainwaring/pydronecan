UAVCAN stack in Python
======================

Python implementation of the [UAVCAN protocol stack](http://uavcan.org/).

UAVCAN is a lightweight protocol designed for reliable communication in aerospace and robotic applications via CAN bus.

## Documentation

* [UAVCAN website](http://uavcan.org)
* [UAVCAN discussion group](https://groups.google.com/forum/#!forum/uavcan)
* [Pyuavcan overview](http://uavcan.org/Implementations/Pyuavcan/)
* [Pyuavcan tutorials](http://uavcan.org/Implementations/Pyuavcan/Tutorials/)

## Installation

Compatible Python versions are 2.7 and 3.3 and newer.
If the library is used with Python 3, which is recommended, it does not require any additional dependencies.
If Python 2.7 is used, additional dependencies are needed - refer to `setup.py` for more info.

```bash
pip install uavcan
```

## Development

The code should be formatted in compliance with [PEP8](https://www.python.org/dev/peps/pep-0008/),
with one exception: line length must not exceed 120 characters (PEP8 requires 79).
