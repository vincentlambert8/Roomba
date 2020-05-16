# HOWTO - Control ESP8266 with Arduino IDE

The goal of this document is to quickly explain how to control an ESP8266 board with Arduino IDE. 

### 1. Install ESP8266 Add-on in Arduino IDE

1. In your Arduino IDE, go to **File **> **Preferences**

2. Enter **http://arduino.esp8266.com/stable/package_esp8266com_index.json** into the “Additional Boards Manager URLs” field as shown in the figure below. Then, click the “OK” button.
3. Open the Boards Manager. Go to **Tools** > **Board** > **Boards Manager…**
4. Search for **ESP8266** and press install button for the “**ESP8266 by ESP8266 Community**“
5. When the installation is completed, go to **Tools** > **Board** and select the “**Generic ESP8266 Module**“. 
6. Plug in your **ESP8266**. Go to **Tools > Port** and make sure the right Port is selected. 
7. That's it. 

### 2. Install the different libraries

1. Go to the folder **Roomba > src > Libraries** and copy everything.
2. Then, go to  **Documents > Arduino > libraries** (or whatever folder than contains your Arduino libraires on your computer) and paste everything. 
3. Compile the **RombaESP01_CONFIGURE**.
4. That's it

