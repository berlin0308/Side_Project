# Image Process Widget

2022.8.11-8.14 | NTU BME LAB405 Summer Project

## Features

- Qt Creator 7.0.2 (Community)
- OpenCV C++


- "File" : select an image file from the local side

- Adjust BGR / HSV channel pixels by adjusting spinBox / slider values
- View the region in the HSV range by adjusting spinBox / slider values
- Select a Filter: Box filter/Gaussian/Median/Sharpen/Noise
- Set kernel size by spinBox / slider

- "flip_V", "flip_H": flip vertically / horizontally
- "rotate_L", "rotate_R": rotate by 90 degree CCW / CW

- Display the image by setPixmap
- Save the processed image

## Files

- OpenCV_HW3.pro - project file
- main.cpp - the main program
- mainwindow .h/.cpp - setting widgets, signals & slots
- uitilities .h/.cpp - functions called
- mainwindow.ui - UI design & typesetting 

## To let the Widget run...

- "/Download/OpenCV_HW3.rar" : Unzip, find the executable file in the folder
- Click "OpenCV_HW3.exe", select an image, enjoy your OpenCV trip! 

## Other features

- Warning MessageBox pops up if User moves widgets without selecting image file
- Design a class 'Process' to store the info of each move
- "reset," "undo," "redo" buttons - using 'stack' data structure
- Pop-up MessageBox with process info after the image is saved

