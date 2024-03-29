******
Pinout
******

Here you can find all the connectors pinout. 

.. note:: All the part number are for the female connector!

Top view
========

.. figure:: _img/pinout/pinout_top.jpg
   :align: center
   :width: 400px

.. csv-table::
   :widths: 10, 20, 20
   
   **Number**, **Description**, **Part Number**
   1, `Micro USB <1. Micro USB_>`_,
   2, `SD <2. SD_>`_,
   3, `Contactor <3. Contactor_>`_, Wurt Elektronik - 662008113322
   4, `Power input <4. Power input_>`_, Wurt Elektronik - 662004113322
   5, `Current sensors <5. Current sensors_>`_, JST - PHR-6

Bottom view
===========

.. figure:: _img/pinout/pinout_bottom.png
   :align: center   
   :width: 400px

.. csv-table::
   :widths: 10, 20, 20
   
   **Number**, **Description**, **Part Number**
   6, `Ethernet <6. Ethernet_>`_, 
   7, `AUX <7. AUX_>`_, JST - PHR-10
   8, `AUX2 <8. AUX2_>`_, JST - PHR-3
   9, `RCD <9. RCD_>`_, JST - PHR-4
   10, `I2C <10. I2C_>`_, JST - PHR-5

Front view
==========

.. figure:: _img/pinout/pinout_front.png
   :align: center   
   :width: 400px

.. csv-table::
   :widths: 10, 20, 20
   
   **Number**, **Description**, **Part Number**
   11, `Front Panel <11. Front Panel_>`_, JST - PHR-5

Connectors
==========

1. Micro USB
------------
Useful for USB host device

.. warning:: Max 250 mA


2. SD
-----
Micro SD slot to expand storage space 

3. Contactor
------------

Connect to contactors control input and relays outputs to verify their opening/closing.

.. figure:: _img/pinout/contactor_connector.jpg
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1,
   2,
   3,
   4,
   5,
   6,
   7,
   8,

4. Power input
--------------

Connects to neutral and all phases available (1 or 3).

.. figure:: _img/pinout/pwr_connector.jpg
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, L3, Third phase
   2, L2, Second phase
   3, N, Neutral
   4, L1, First phase

5. Current sensors
------------------

Connects to the TA current sensor(s).

.. figure:: _img/pinout/curr_sensor_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, A_P, Phase A TA input 1
   2, A_N, Phase A TA input 2
   3, B_P, Phase B TA input 1
   4, B_N, Phase B TA input 2
   5, C_P, Phase C TA input 1
   6, C_N, Phase C TA input 2

6. Ethernet
-----------

Needed for internet connection where WiFi is not available.

7. AUX
------

.. figure:: _img/pinout/aux_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1,
   2,
   3,
   4,
   5,
   6,
   7,
   8,
   9,
   10,

8. AUX2
-------

.. figure:: _img/pinout/aux2_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, VCC, 5V
   2, LEDOUT, "Programmable digital output, internally pulled up" 
   3, GND, Ground

9. RCD
------

Connects to an RCM14-03 residual current monitor.

.. figure:: _img/pinout/rcd_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, GND, Ground
   2, +12V, 12V
   3, TEST, RCD test output
   4, RCD_FAULT, RCD fault input

10. I2C
-------

I2C bus for communications

.. figure:: _img/pinout/5x1_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, NC, "\-"
   2, SCL, I2C SCL
   3, SDA, I2C SDA
   4, 3V3, "3.3V"
   5, GND, Ground

11. Front Panel
---------------

Connects to front panel for light effects and user input.

.. figure:: _img/pinout/5x1_connector.png
    :align: center
    :height: 150px

.. csv-table::
   :widths: 10, 20, 20
   
   **Pin**, **Signal**, **Description**
   1, RST, Reset
   2, RX, Serial receive
   3, TX, Serial transmit
   4, 5V, 5V
   5, GND, Ground
