

## Python Image Color Detection Tool


This Python application helps to detect color name from a image file. This program takes an image as an input and then shows that image in a new window. Whenever a user double clicks at any part of the image, this program will take the (x,y) coordinate of the click from the image and displays the name of that particular pixel color corresponding to that coordinate of the image.

**Python Version-** 3.9
**Used Libraries-** OpenCV, Pandas, Numpy

**Install libraries**
In order to install the required packages on the terminal, run the following command---

    python3 -m pip install opencv-python pandas numpy

**Files**
There are in total three files.
1. *"detect-color.py"* - The main python code file, written in python version 3.9.
2. *"colors.csv*" - This is the color dataset, that I'll be using to map color values to its corresponding names. This dataset has 865 color names, along with their RGB & hex values. This dataset was downloaded from- https://github.com/codebrainz/color-names/blob/master/output/colors.csv
3. *"Saarschleife.jpg"* - This is a sample image file, that I'll be using to test my python code. The python program will use this image file to detect colors, whenever a user double clicks at any part of the image, the program will show the name of that pixel.
Image source- https://500px.com/photo/1050840125/saarschleife-by-tariqul-dipu

**Usage Instructions**
To run the program, first make sure all the necessary files are in the same folder. Then on the Terminal, we'll have to change the directory to that particular folder by using the "cd" command.

Then we'll have to run the following command---

    python3 detect_color.py -i <add your image path here>

For my case, as I've already downloaded my sample image *Saarschleife.jpg* in my working directory, I'll run the following command on Terminal---

    python3 detect_color.py -i Saarschleife.jpg


After that, this program will open a new window with the sample image. Whenever a user double clicks at any part of the image, the name of the pixel (along with the RGB values) referring to that particular click will be shown at the upper side of the window.


#python #opencv #numpy #pandas # image #color_detection #python_project
