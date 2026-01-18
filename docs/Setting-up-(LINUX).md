# Setting-up (LINUX)

```{index} single: Setting-up (LINUX)
```

<https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/linux-setup.html>

```
sudo apt install git wget flex bison gperf python3 python3-pip python3-setuptools cmake ninja-build ccache libffi-dev libssl-dev dfu-util libusb-1.0-0
```

![](https://user-images.githubusercontent.com/69573151/116203757-52905880-a73c-11eb-8d39-bdcecc446e7d.png)

mit Yes bestätigen.

Nun laden Sie ESP-IDF herunter.
```
mkdir -p ~/esp
cd ~/esp
git clone --recursive https://github.com/espressif/esp-idf.git
```
> ESP-IDF wird in diesen Ordner heruntergeladen:  `~/esp/esp-idf`

Navigiere jetzt mit `cd ~/esp/esp-idf` in den Ordner. 

Mache die Install Datei mit `chmod +x install.sh` ausführbar. Danach führe die Datei aus.
`./install.sh`

Fertig.
