# MSE TSM MobCom
## Hands-on of lesson 7
For slides and example code, see [lesson 7](../../../mse-tsm-mobcom/blob/master/07/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) Android BLE scanner, 10'
* Build and run the [MyBleScannerApp example code](https://github.com/tamberg/mse-tsm-mobcom/tree/master/07/Android/MyBleScannerApp).
* Check the Logcat output with filter "MainActivity".
* If it works, you should see BLE devices around you.
* Test the app by disabling Bluetooth, location, etc.

Done? Add a button to the UI to start a scan. 

### b) Android BLE central, 10'
* Build and run the [MyBleCentralApp example code](https://github.com/tamberg/mse-tsm-mobcom/tree/master/07/Android/MyBleCentralApp).
* Also, a nRF52840 with [HRM BLE peripheral code](https://github.com/tamberg/mse-tsm-mobcom/blob/master/06/Arduino/nRF52840Sense_HrmBlePeripheral/nRF52840Sense_HrmBlePeripheral.ino).
* Check the Logcat output with filter "MainActivity".
* If it works, you should see heart rate measurements.

Done? Read the Android app source code in detail.

### c) Android BLE issues, 10'
* It looks easy, but BLE on Android has many issues.
* Read some of the tips how to [make it actually work](https://punchthrough.com/android-ble-development-tips/).
* Also check this [list of issues](https://github.com/iDevicesInc/SweetBlue/wiki/Android-BLE-Issues) to get an impression.
* iOS BLE seems more stable. Why could that be?

Done? Find some stats about the Android OS.
