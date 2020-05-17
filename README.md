# ESP32 Development Environment using Arduino IDE in Windows 10

1.	[Download](https://www.arduino.cc/en/Main/Software) and install the Arduino IDE


2.	Open Arduino


3.	Click on: File -> Preferences
![preferences](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/preferences.png)


4.	Copy & paste (in Additional Boards Manager URLs section):

	`https://dl.espressif.com/dl/package_esp32_index.json`

5.	Click OK


6.	[Download](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers) and install the CP210x USB to UART Bridge VCP Drivers

	`This is to allow the ESP32 to communicate with your computer`


7.	Connect a USB micro lead from your PC to your ESP32


8.	Ensure the correct port is selected:	Tools -> Port
![port](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/port.png)


9.	Open an example:	File -> Examples -> ESP32 -> ChipID -> GetChipID
![openExample](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/openExample.png)


10.	Code loaded for the GetChipID example
![example](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/example.png)


11.	Open the Serial Monitor:	Tools -> Serial Monitor
![openSer](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/openSerialMon.png)


12.	To display the Serial Monitor
![serMon](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/serialMon.png)


13.	Upload the sketch into your attached ESP32:	Sketch -> Upload
![up](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/sketchUpload.png)

14.	Or click on the Upload icon
![upIcon](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/uploadIcon.png)


15.	The Arduino IDE will compile the sketch
![compSt](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/compilingStart.png)

16.	...connect to the ESP32
![conx](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/connecting.png)

17.	...and upload the sketch
![up](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/uploading.png)


18.	When completed a message will be displayed in the lower dialogue box stating: Hard resetting via RTS pin...
![complete](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/completed.png)


19.	The program will now run & you should see the Serial Number of your attached ESP32 presented in the Serial Monitor. Refreshed every 3 seconds:
![complete](https://raw.githubusercontent.com/derrickr/ArduinoDevEnvESP32/master/images/running.png)


20.	You should now have a working ESP32 Development Environment using Arduino IDE
