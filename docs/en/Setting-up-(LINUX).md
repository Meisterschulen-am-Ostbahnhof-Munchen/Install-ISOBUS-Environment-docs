# Setting up (LINUX)

<https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/linux-setup.html>
sudo apt install git wget flex bison gperf python3 python3-pip python3-setuptools cmake ninja-build ccache libffi-dev libssl-dev dfu-util libusb-1.0-0
![](https://user-images.githubusercontent.com/69573151/116203757-52905880-a73c-11eb-8d39-bdcecc446e7d.png)

Confirm with Yes.

Now download ESP-IDF.

mkdir -p ~/esp
cd ~/esp
git clone --recursive https://github.com/espressif/esp-idf.git
> ESP-IDF will be downloaded to this folder: `~/esp/esp-idf`

Now navigate to the folder using `cd ~/esp/esp-idf`.

Make the install file executable using `chmod +x install.sh`. Then run the file.

./install.sh`

Done.
