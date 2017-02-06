# Address Checker

Mobile app to scan QR code and show current bitcoin balance.


## Overview

* Scan QR code to get bitcoin address (public)
* Call an API to get balance of bitcoin address (public)
* Display amount of funds


## Requirements

* [Cordova](https://cordova.apache.org/)

## How to run it

```
For testing on android device you have to install the plugin and with the device connected via USB on debugging mode  run the command below:

```
cordova platform add android
```

```
cordova run android --device
```

For running in the browser:

```
cordova run browser -- --port=8001 --target=Chromium
```

```
