|License|

==================================================
SOLO Motor Controller PYTHON RASPBERRY PI Library
==================================================
SOLO Motor Controller PYTHON RASPBERRY PI Library It can be used with UART line of RASPBERRY PI or any similar controller to control, command
or read all the parameters that are stored or existing in command set of SOLO.
More information about it on `the SOLO website <https://www.solomotorcontrollers.com/>`_.

How To Use
===========
Open Command Line In Your Directory:
.. code-block::

   $ git clone https://github.com/Solo-FL/SOLO-motor-controllers-PYTHON-RASPBERRY-PI-library.git SoloMotor
   $ cd /SoloMotor/examples

Enter The following Command:
.. code-block::

   $ main.py

There is Other Examples That You Can Use,Some Of Them Need Actions To Work Correctly Please Read Comments In Each Example

For List All Available Methods Read `DataSheet <https://www.solomotorcontrollers.com/resources/specs-datasheets/>`__




Configure UART on Raspberry Pi
=================================

In Raspberry Pi, enter following command in Terminal window to enable UART::
.. code-block::

   $ sudo raspi-config

#. Select -> Interfacing Options
#. After selecting Interfacing option, select Serial option to enable UART
#. Then it will ask for login shell to be accessible over Serial, select No shown as follows.
#. At the end, it will ask for enabling Hardware Serial port, select Yes,
#. Finally, our UART is enabled for Serial Communication on RX and TX pin of Raspberry Pi 3.
#. Then, reboot the Raspberry Pi.
#. `S <https://www.electronicwings.com/raspberry-pi/raspberry-pi-uart-communication-using-python-and-c>`__

Dependencies
=============
`Python 3 <https://www.python.org/downloads/>`__
`pyserial <https://github.com/pyserial/pyserial>`__



Authors
=======

SOLO Motor Controller PYTHON RASPBERRY PI Library is created by SOLO Motor Controllers team


License
=======

GNU General Public License v3.0 or later

See `COPYING <COPYING>`_ to see the full text.

.. |License| image:: https://img.shields.io/badge/license-GPL%20v3.0-brightgreen.svg
   :target: COPYING
   :alt: Repository License
