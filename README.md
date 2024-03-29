# HW3-of-Embedded-System
This is the code of HW3 of Embedded System. The code was modified from the given code taught in class, which let us to revise the CCCD value of BLE tool app. The procedures to connect a GATT server to the Raspberry Pi are listed in the following:
1. Open BLE tool, and choose "GATT server".
2. Go to "set Service" (in the upper right three-dots icon), click "Property", and tick "Notify". Then click "Apply".
3. Run the Python code.
4. Find you device.
5. Go to "SHOW LOG", and you will find that the CCCD value has been changed (in this example, the value change to 0x0002).
