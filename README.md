# smart-door-lock

## Progress This week

**SETUP ESP8266 AT SCHOOL:**

To setup ESP8266 at school need to follow some instructions:

1. On the Arduino IDE need to go to **File > Preferences**

2. Enter http://arduino.esp8266.com/stable/package_esp8266com_index.json into the “Additional Board Manager URLs” field as shown in the figure below. Then, click the “OK” button.

3. Go to **Tools > Board > Boards Manager….** And install esp8266 by **ESP8266 Community**

4. Then go to **Tools > Board…** and select Node MCU 1

Also install drivers using this website: https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers … **Make sure it is a CP210x Universal Windows Driver.** This will make sure arduino read ports for ESP8266

**Conclusion:**

Sadly I wasn't able to connect to the KSU Wireless using HTTP Authentication. Here is the result.

![HTTP](https://user-images.githubusercontent.com/80173030/110221670-3d612100-7e93-11eb-9f86-d111b6a979a4.PNG)


As for now I will try to finish the project at home so that later we can focus on setting it up at school.

**DATABASE SETUP:**

Pin connections for ESP8266 to BME280. Here below is the picture

![pins](https://user-images.githubusercontent.com/80173030/110221799-d132ed00-7e93-11eb-9d7d-8fa7f44277e9.PNG)
