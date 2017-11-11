List of Supported Displays
**************************

.. module:: rgb

All of those displays support the methods of the :class:`Display` class.

.. module:: hx8353
.. class:: HX8353(spi, dc, cs, rst=None, width=128, height=128)

    A TFT display.

.. module:: ili9341
.. class:: ILI9341(spi, dc, cs, rst=None, width=240, height=320)

    A TFT display.

    .. method:: scroll(dy=None)

        Get or set the vertical scroll position.

.. module:: s6d02a1
.. class:: S6D02A1(spi, dc, cs, rst=None, width=128, height=160)

    A TFT display.

.. module:: ssd1331
.. class:: SSD1331(spi, dc, cs, rst=None, widht=96, height=64)

    An OLED display.

.. module:: ssd1351
.. class:: SSD1351(spi, dc, cs, rst=None, width=128, height=128)

    An OLED display.

.. module:: st7735
.. class:: ST7735(spi, dc, cs, rst=None, width=128, height=128)

    A TFT display.
