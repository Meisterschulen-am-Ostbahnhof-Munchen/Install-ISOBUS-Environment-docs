# JTAG
## JTAG Step 01:
Now we'll set up JTAG.
[https://docs.espressif.com/projects/esp-idf/en/v4.4.3/esp32/api-guides/jtag-debugging/configure-ft2232h-jtag.html](https://docs.espressif.com/projects/esp-idf/en/v4.4.3/esp32/api-guides/jtag-debugging/configure-ft2232h-jtag.html)
[https://docs.espressif.com/projects/espressif-esp-iot-solution/en/latest/hw-reference/ESP-Prog_guide.html](https://docs.espressif.com/projects/espressif-esp-iot-solution/en/latest/hw-reference/ESP-Prog_guide.html)
[https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-guides/jtag-debugging/index.html](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-guides/jtag-debugging/index.html)

### Switching the USB interface with ZADIG:

#### Before:

![](https://user-images.githubusercontent.com/69573151/203028255-a0b5e911-0242-4ecf-957d-ef70e81c8e86.png)

![](https://user-images.githubusercontent.com/69573151/203028864-2b13e1a3-9be6-4c23-bea2-b32463a38cdb.png)

#### Calling ZADIG:

See also: [https://docs.espressif.com/projects/esp-idf/en/v4.4.3/esp32/api-guides/jtag-debugging/configure-ft2232h-jtag.html#windows](https://docs.espressif.com/projects/esp-idf/en/v4.4.3/esp32/api-guides/jtag-debugging/configure-ft2232h-jtag.html#windows)

![Schritt_01](https://raw.githubusercontent.com/Meisterschulen-am-Ostbahnhof-Munchen/Install-ISOBUS-Environment-docs/main/images/JTAG/Schritt_01.png)

#### After:

![](https://user-images.githubusercontent.com/69573151/203028640-6106a050-2190-4467-86d0-e956cf905026.png)

Note: This process must be repeated if you connect the ESP-PROG to a different interface.

Therefore, ideally, always use the same USB ports.

Before:

See also:
...``

]

]
``````````````````````````````````````````````` ![Schritt_01a](https://raw.githubusercontent.com/Meisterschulen-am-Ostbahnhof-Munchen/Install-ISOBUS-Environment-docs/main/images/JTAG/Schritt_01a.jpeg)

![Schritt_01b](https://raw.githubusercontent.com/Meisterschulen-am-Ostbahnhof-Munchen/Install-ISOBUS-Environment-docs/main/images/JTAG/Schritt_01b.jpeg)

These pins are required at a minimum:

![](https://user-images.githubusercontent.com/69573151/203024137-ff74b56a-aa9c-4492-a743-da31df66fcb3.png)

![Schritt_01c](https://raw.githubusercontent.com/Meisterschulen-am-Ostbahnhof-Munchen/Install-ISOBUS-Environment-docs/main/images/JTAG/Schritt_01c.jpeg)

![](https://user-images.githubusercontent.com/69573151/203024448-ca6c2e56-4927-4140-aa36-bdfda1c0fcc1.png)

![](https://user-images.githubusercontent.com/69573151/203026388-1db50d10-e977-4246-aa9e-0755429acaee.png)

https://docs.espressif.com/projects/esp-idf/en/latest/api-guides/jtag-debugging/configure-other-jtag.html

## JTAG Step 2:

openocd --version

![Schritt_02](https://raw.githubusercontent.com/Meisterschulen-am-Ostbahnhof-Munchen/Install-ISOBUS-Environment-docs/main/images/JTAG/Schritt_02.png)

## JTAG Step 3:

https://docs.espressif.com/projects/esp-idf/en/v4.4.3/esp32/api-guides/jtag-debugging/index.html#run-openocd

openocd -f board/esp32-wrover-kit-3.3v.cfg

![](https://user-images.githubusercontent.com/69573151/203031746-93eec259-ef86-4e3e-95a5-7daafd7ebd21.png)

ATTENTION!!! Starting the GDB server from the command line is only necessary if you are also debugging from the command line.

--> OpenOCD is started automatically from within the ESP-IDF.

## JTAG Step\_04:

At this point, the documentation is hopelessly outdated.

If you are using the Espressif IDE, these links are no longer valid.

https://docs.espressif.com/projects/esp-idf/en/latest/api-guides/jtag-debugging/debugging-examples.html#jtag-debugging-examples-eclipse

[https://docs.espressif.com/projects/esp-idf/en/latest/api-guides/jtag-debugging/using-debugger.html#jtag-debugging-using-debugger-eclipse](https://docs.espressif.com/projects/esp-idf/en/latest/api-guides/jtag-debugging/using-debugger.html#jtag-debugging-using-debugger-eclipse)

I was able to debug immediately as follows:

1. Select only ESP-IDF GDB..., then click on the

![](https://user-images.githubusercontent.com/69573151/203037697-609963cb-6331-4772-95b8-35f5f93ed371.png)

icon in the upper left,

and start it.

No settings need to be changed.

![](https://user-images.githubusercontent.com/69573151/203036844-41313b50-3286-4cd1-bfde-dec157615413.png)

## JTAG Step\_05:

Not applicable

## JTAG Step\_06:

Not applicable

## JTAG Step\_07:

![](https://user-images.githubusercontent.com/69573151/203037819-ed99f4f7-3f08-4199-8075-e7261f328ff3.png)

And yes, you can run the console alongside the debugging session,

but the console must be open before the debugging session starts.
