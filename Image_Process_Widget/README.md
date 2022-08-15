# Image Process Widget

2022.8.11-8.14 | NTU BME LAB405 Summer Project

## Features

- Qt Creator 7.0.2 (Community)
- OpenCV C++


- "File" : select an image file from the local side
- "reset" : reset to the initial state
- "undo" : to the previous state 
- "redo" : to the next state

- Adjust BGR / HSV channel pixels via spinBox / slider
- View the region in the HSV range by adjusting  spinBox / slider values
- Select a Filter: Box filter/Gaussian/Median/Sharpen/Noise
- Set kernel size by spinBox / slider

- "flip_V": flip vertically
- "flip_H": flip horizontally
- "rotate_L": rotate by 90 degree CCW
- "rotate_R": rotate by 90 degree CW


- Display the image by .setPixmap(...)
- Save the processed image and a MessageBox showing the process info 

## Files

- OpenCV_HW3.pro - project file
- main.cpp - the main program
- mainwindow .h/.cpp - setting widgets, signals & slots
- uitilities .h/.cpp - functions called
- mainwindow.ui - UI design & typesetting 

## To let the program run...

- "/Download/OpenCV_HW3.rar" : Unzip, find the executable file in the folder
- Click "OpenCV_HW3.exe" ,select an image and enjoy your OpenCV trip! 
