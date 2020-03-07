# ESP32-FirstYear
ESP32 First Year Project

## Running the ESP32 code on Arduino IDE:

Install the boards needed through the ARDUINO file. Under preferences, look for Arduino Boards Manager URLs.

You need to add the following URL's so you can choose to compile to an ESP 32 board:

```https://dl.espressif.com/dl/package_esp32_index.json```
```http://arduino.esp8266.com/stable/package_esp8266com_index.json ```


Once you start compiling your computer might have problems compiling. The problems we faced was the ports Arduino selected was wrong. We manually had to check for which port the ESP32 connected to from the device manager. Then we check under tools fir ports and see if Arduino has the right port selected for compiling.

***

##  

## Running the python code on your computer

Make sure you have the required libraries installed before running the code

On top of that, you need to specify the image that you wish to analyze for face detection

The full command is as follows:

```python detect_faces.py --image your_image.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel```

***
***You must run server.py before running the command above. The code is currently set to not do anything until it can talk to the server***

***You need to specify your own image file, and include it in the same folder (this repository)***

***
