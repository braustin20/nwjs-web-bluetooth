# nwjs-web-bluetooth
This project is a test using NW.js version v0.41.3 to verify that it can utilize the [web bluetooth API](https://webbluetoothcg.github.io/web-bluetooth/) to connect and communicate with other bluetooth devices.

## What is it?
This project is a simple html page ran with NW.js to function similar to a native application. With this approach we are able to add additional items to the system toolbar for the page's window.

An additional menu called "Bluetooth" can be found in the toolbar, with a menu option to "Request Bluetooth Device". When this option is selected the bluetooth API's pairing menu will appear. Once successfully paired to a device, a browser alert will be shown containing the device information.

## How to run
- Download v0.41.3 of the NW.js binaries https://dl.nwjs.io/v0.41.3/
- Run index.html using the downloaded binaries using the following commands:
    - `cd /path/to/your/app`
    - `/path/to/nw .`
- When the page opens, use the toolbar menu Bluetooth>Request Bluetooth Device
- Select a device to pair
- Observe the alert containing the device information

For more information see https://nwjs.readthedocs.io/en/nw44/For%20Users/Getting%20Started/
