libmpsse
========

Open source library for SPI/I2C control via FTDI chips

Updated for usage with python 3 (version 3.6 tested):
1. Changed configure to use python 3 instead of python 2
2. Changed Open in mpsse.c for system to work with declared frequency
3. Changed Write in mpsse.py to work with compatible string type
4. Changed PyString to PyBytes in mpsse.i for compatibility
