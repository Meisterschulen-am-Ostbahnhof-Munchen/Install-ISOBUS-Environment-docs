# Installation Setup

## Step 1

Background information can be found here:
https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/
Please check beforehand that your username under C:\Users is without umlauts and spaces.
Otherwise, you will encounter serious problems.

Download the ESP-IDF Tools.

https://dl.espressif.com/dl/esp-idf/?idf=4.4

https://dl.espressif.com/dl/esp-idf-tools-setup-online-2.9.exe

https://dl.espressif.com/dl/esp-idf-tools-setup-offline-2.10.exe

## Step 2

![Setup step Step 2](https://user-images.githubusercontent.com/69573151/127839833-d287df63-63ee-4f83-8144-ec901b59e1e2.png)

## Step 3

![Setup step Step 3](https://user-images.githubusercontent.com/69573151/124079826-edadf300-da49-11eb-9f2c-09df6762d1d3.png)

If it looks like this, that's great.

If not:

![Setup step Step 3](https://user-images.githubusercontent.com/69573151/127839959-f86d3cbb-3f00-47b1-8695-aadd0b243e50.png)

![Setup step Step 3](https://user-images.githubusercontent.com/69573151/127840060-62ca0063-0bc0-4efe-8c67-be0569275592.png)

Please click "Apply Fixes"

and then yes.

## Step 4

Select 4.3

The installer will suggest "desktop" here, but I don't like that!

![Setup step Step 4](https://user-images.githubusercontent.com/69573151/127840259-084f3ce9-8d0c-4779-b7a0-6bc28cbf8860.png)

## Step 5

C:\\Users\\hoepffr\\.espressif

This folder must also not contain any umlauts or spaces.

![Setup step Step 5](https://user-images.githubusercontent.com/69573151/124080125-4c736c80-da4a-11eb-8b2a-84fb4fa06eca.png)

## Step 6

![Setup step Step 6](https://user-images.githubusercontent.com/69573151/130443695-329490e6-8fac-427f-aa90-7981b7c79663.png)

## Step 7

![Setup step Step 7](https://user-images.githubusercontent.com/69573151/124080464-b1c75d80-da4a-11eb-8bf5-773fbe59612f.png)

## Step 8

![Setup step Step 8](https://user-images.githubusercontent.com/69573151/124080562-cdcaff00-da4a-11eb-8764-e3bd49ac888b.png)

## Step 9

![Setup step Step 9](https://user-images.githubusercontent.com/69573151/124081041-55b10900-da4b-11eb-8b47-22a968f55e4d.png)

## Step 10

![Setup step Step 10](https://user-images.githubusercontent.com/69573151/124081144-737e6e00-da4b-11eb-83ef-0ee6f492b41d.png)

![Setup step Step 10](https://user-images.githubusercontent.com/69573151/124081164-7b3e1280-da4b-11eb-9c4f-f358c59daa36.png)

![Setup step Step 10](https://user-images.githubusercontent.com/69573151/124081200-86913e00-da4b-11eb-97c1-8a3e3532f13d.png)

>
## Step 11: (Information only)
>
> idf.py menuconfig
>
> idf.py build
>
> https://docs.espressif.com/projects/esp-idf/en/latest/get-started/index.html#step-6-connect-your-device
>
> https://docs.espressif.com/projects/esp-idf/en/latest/get-started/establish-serial-connection.html
>
> https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers
>
> https://www.ftdichip.com/Drivers/VCP.htm
>
> https://docs.espressif.com/projects/espressif-esp-iot-solution/en/latest/hw-reference/ESP-Prog_guide.html
>
> idf.py flash
>
> idf.py monitor
>
> So, you could already work from the command line here.

>
> ![Setup step Step 11: (Information only)](https://raw.githubusercontent.com/Meisterschulen-am-Ostbahnhof-Munchen/Install-ISOBUS-Environment-docs/main/images/SettingUp/Schritt_12.png)

## Step 12

Now open Eclipse and create a new workspace.

![Setup step Step 12](https://user-images.githubusercontent.com/69573151/124082234-c147a600-da4c-11eb-9f46-4c323b9664d6.png)

![Setup step Step 12](https://user-images.githubusercontent.com/69573151/124082195-b2f98a00-da4c-11eb-9750-39be52277e92.png)

Done.

You don't need to install Java, Python, or Git beforehand.
