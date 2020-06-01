# GAEN Detector

This app displays the beacons received from devices running apps with GAEN support (Google+Apple Exposure Notifications API). Based on STOP COVID DETECTOR by [Rémy Grünblatt] (https://remy.grunblatt.org/) . 

The UUID currently matched are:

- 0000fd6f-0000-1000-8000-00805f9b34fb (i.e. the 16 bit UUID 0xFD6F, listed on the [Bluetooth Consortium Website](https://www.bluetooth.com/specifications/assigned-numbers/16-bit-uuids-for-members/) = UUID 64879 - Apple Inc. 27/03/2020.


## Usage

This app can be used to check whether the GAEN app is really working as intended (sending beacons), for example when your phone is in sleeping mode or in standby. Of course, you'd need another phone to check, as your phone cannot detect the beacons it sends.

You can also use this app to illustrate the inner working of the application, as it underlines it's possible to check (without any contact) if someone is using the GAEN application or not.

It can also be used to check if your phone changes of MAC address regularly to avoid tracking.

## Screenshots

![](photo1.png)

![](photo2.png)
