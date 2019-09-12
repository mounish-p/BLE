# BLE
## To find the Characteristic of a BLE device

**Install pygatt for python**

```sudo apt-get isntall python-pip```

```sudo pip install pygatt```

## **USAGE**
Use Bluehydra or hcitool to scan your target BLE device and copy the BD_ADDR of the target device. Then run the programm as we usually run python3

```sudo python Find_characteristic.py```

Then it will ask for the user to enter the BD_ADDR of the target device, just paste the BD_ADDR of the target device which is found using Bluehydra or hcitool, then it will display all the characterstic of the device
indicating all characterstic adapted by Bluetooth SIG.

