# ESP32-FirstYear
ESP32 First Year Project

## Running the python code on your computer

Make sure you have the required libraries installed before running the code

On top of that, you need to specify the image that you wish to analyze for face detection

The full command is as follows:

```python detect_faces.py --image your_image.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel```

***
***You must run server.py before running the command above. The code is currently set to not do anything until it can talk to the server***

***You need to specify your own image file, and include it in the same folder (this repository)***

