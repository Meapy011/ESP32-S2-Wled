# **Wled on a S2 mini**: A light show in your back pocket!

<img src="pics/led-kat.jpg"  />

## Resources:
- [Wled Website](https://kno.wled.ge/)
- [Online Custom Compiler](https://wled-compile.github.io/?lang=en)

## How to Update your Nugget:
1.	[Download the latest binary file here](https://github.com/HakCat-Tech/USB-Nugget/releases/)
2.	Place your Nugget in [Device Firmware Upgrade (DFU) mode]().
4.	Open our [web flasher tool](https://hakcat-tech.github.io/esp-web-flasher/) in Google Chrome (other browsers not currently supported)
5.	Click on "Connect" and then select the "ESP32-S2" board. Click "Erase" and "OK" to continue.
6.	Once you see "Finished", click "Choose a file" and select the .BIN file you downloaded in step one. Click "Program" to flash your Nugget!
7.	When its done, unplug your Nugget and plug it in again to see the new features. 

## Accessing the Web Interface
To access the web interface, connect to `Nugget-AP` with the password `nugget123`.  In a web browser, navigate to `4.3.2.1'

## Updating AP Credentials & Keyboard ID
To edit your USB Nugget's default AP name & password, edit or create the `.usbnugget.conf` file on your NUGGET drive, and add the following 2 lines:
```
network = "Nugget-AP"
password = "nugget1223"
```

## Included Usermods

- Audio Reactive
	- [Read Me](https://github.com/wled/WLED/blob/main/usermods/audioreactive/readme.md)

- Four line display
