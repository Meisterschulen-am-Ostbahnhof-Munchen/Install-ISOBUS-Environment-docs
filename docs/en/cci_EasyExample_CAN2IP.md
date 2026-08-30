# cci_EasyExample_CAN2IP

Special circumstances require special measures:

- Execute a PULL command on cci_EasyExample
- "CAN2IP" should be selected in sdkconfig
- Screenshot:
<img src="https://user-images.githubusercontent.com/5702985/106381319-2cb31c00-63b8-11eb-9495-eec8ef277af3.png" />

- Explanation: We now have two ways to connect to the ISOBUS ECU:
- The "virtual" CAN, which is actually WLAN: CAN2IP
- The "familiar" physical CAN, which is also present in the tractor: CAN
- You also need to enter your SSID and password in sdkconfig
- Screenshot:

<img src="https://user-images.githubusercontent.com/5702985/106381351-6421c880-63b8-11eb-84b6-230eaffeff7f.png" />

- Now load the program onto the M5 Atom
- You don't necessarily need the CAN hardware for this.

<img src="https://user-images.githubusercontent.com/5702985/106381404-c2e74200-63b8-11eb-835a-5f214b1bbb6c.png" />

- An IP address now appears in the console.

<img src="https://user-images.githubusercontent.com/5702985/106381497-751f0980-63b9-11eb-8dca-34fd90130f16.png" />

- Enter this IP address in the farm display.
- For installation, see: [nx_farm_display](https://isobus-other-docs.readthedocs.io/de/latest/nx_farm_display.html)
- Select "router 2" as the CAN interface.
- Screenshot:

<img src="https://user-images.githubusercontent.com/5702985/106381516-95e75f00-63b9-11eb-8530-5676dae59199.png" />

- Click "Restart".
- The object pool should now appear in the farm display.

<img src="https://user-images.githubusercontent.com/5702985/106381552-dba42780-63b9-11eb-9d95-4bc40de0f0b6.png" />

You now have a completely virtual environment around the ISOBUS.

Advantage: You don't have to build any hardware!
