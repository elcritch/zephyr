.. _mikroe_feather_click:

MikroElektronika Feather Click Expansion Shield
##########################

Overview
********

Feather Click Shield with two mikroBUS sockets as wings.

Pins Assignment of the Eth Click Shield
=======================================

+-----------------------+---------------------------------------------+
| Shield Connector Pin  | Function                                    |
+=======================+=============================================+
| RST#                  | Ethernet Controller's Reset                 |
+-----------------------+---------------------------------------------+
| CS#                   | SPI's Chip Select                           |
+-----------------------+---------------------------------------------+
| SCK                   | SPI's ClocK                                 |
+-----------------------+---------------------------------------------+
| SDO                   | SPI's Slave Data Output  (MISO)             |
+-----------------------+---------------------------------------------+
| SDI                   | SPI's Slave Data Input   (MISO)             |
+-----------------------+---------------------------------------------+
| INT                   | Ethernet Controller's Interrupt Output      |
+-----------------------+---------------------------------------------+


Requirements
************

This shield can only be used with a board which provides a configuration
for Feather connectors and corresponding SPI, I2C, UART, and GPIO's. 

Programming
***********

Set ``-DSHIELD=mikroe_eth_click`` when you invoke ``west build``. For example:

References
**********

.. target-notes::

.. _Eth Click Shield website:
   https://www.mikroe.com/feather-click-shield

