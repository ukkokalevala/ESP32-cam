you can find ESP32-CAM examples in the Arduino IDE under the File menu, then Examples, then ESP32, and then Camera and CameraWebServer: 

Requirements:

    ESP8266 NodeMCU or ESP32
    ESP32-CAM AI Thinker
    Arduino IDE with ESP8266 and ESP32 board support installed
    Appropriate wiring

Wiring:

    ESP8266 TX - ESP32 RX
    ESP8266 RX - ESP32 TX
    ESP8266 GND - ESP32 GND
you will also need to Connect a wire between the EN and GND pins on the Node MCU effectively disables the Node MCU’s microcontroller, allowing it to function as a USB-to-serial adapter without interference. This setup ensures that the MCU doesn't try to send any data during the upload process, preventing serial noise or corruption.
