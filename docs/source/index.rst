Welcome to: How to convert an A1 Smart Home Gateway into a WiFi Access Point that also provides a Zwave and a ZigBee module.
===================================

.. note::

   This project is under active development.

The `Sercomm <https://www.sercomm.com>`_ NA502 is a ZigBee/Z-Wave gateway sold under various brands (e.g. A1 Smart Home Gateway in Austria). It is based on the MediaTek MT7621 SoC with a Gigabit Ethernet port.

The NA502 and NA502s_(3G) gateway models form the basis of the smart home services of various providers, such as A1, Mios, Hornbach, etc.

They are ZigBee/Z-Wave gateways with a LAN port and 2.4/5-GHz WiFi adapters. 

It is based on the MediaTek MT7621 SoC and has a Gigabit Ethernet connection.

Important: Some variants, like the Vera gateway, seem to have a crippled U-Boot that don't allow loading code to SDRAM via TFTP. So far, no solution exists for those gateways.

.. note::

   The NA502s also has a 3G cellular module, but this will no longer play a role in the future as this cellular service is being phased out.

Contents
--------

.. toctree::

   Installation
   TFTP installation instructions
   Z-Wave and ZigBee
