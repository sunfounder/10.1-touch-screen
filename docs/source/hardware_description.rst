.. note::

    Hello, welcome to the SunFounder Raspberry Pi & Arduino & ESP32 Enthusiasts Community on Facebook! Dive deeper into Raspberry Pi, Arduino, and ESP32 with fellow enthusiasts.

    **Why Join?**

    - **Expert Support**: Solve post-sale issues and technical challenges with help from our community and team.
    - **Learn & Share**: Exchange tips and tutorials to enhance your skills.
    - **Exclusive Previews**: Get early access to new product announcements and sneak peeks.
    - **Special Discounts**: Enjoy exclusive discounts on our newest products.
    - **Festive Promotions and Giveaways**: Take part in giveaways and holiday promotions.

    👉 Ready to explore and create with us? Click [|link_sf_facebook|] and join today!

HARDWARE DESCRIPTION
=======================


.. image:: img/back.jpg

* Main Board: It is mounted on top to control the display.
* Control Board: It is a cross slot structure with one side movable, so you can mount different size of control board.
* Touch Module: This is the module used to let the display get the touch function, you need to connect it to the USB port of the control board through the USB cable provided by us.


**Touch Module**

.. image:: img/touch_module.jpg

There are two types of 4pin connector on the touch module, with the pin serial number shown on the figure.

Here are the definitions of the pins:

* Pin 1: VDD(5V)
* Pin 2: D-
* Pin 3: D+
* Pin 4：GND

**LED Indicators**

.. image:: img/inch2.png

There are 2 LED indicators on the main board of the screen to show different signals: 

* Power on the screen, after the green LED flashes one time, it lights on continuously; and the red LED lights on immediately.
* If there's no HDMI signal, only the red LED will turn on.
* If there's an HDMI signal, these two LEDs will turn on.
* If you press the power button, the green LED will turn off and the red LED will keep turning on.
* If you remove the power cord, both of the two LEDs will turn off.

**Buttons**

Buttons on the main board and their functions: 

.. image:: img/inch3.png

Power: Short press to switch ON/OFF(go into the sleep mode) the screen. Long press to power ON/OFF the device(Raspberry Pi).

* B+: Increase screen brightness.
* B-: Reduce screen brightness.
* V+: Volume up.
* V-: Volume down.

**Interfaces**

On one side of the main board there are ports of HDMI input, 12V power input, and 5V/3A USB power output. Also equipped with a 4pin PH2.0 speaker port.

.. image:: img/main_board.jpg
