# Open LCD Assistant



## Contents
***
- [General Info](#general-info)
- [Usage](#usage)
- [Dependency](#dependency)
- [Todo](#todo)
- [References](#references)






## General Info
***
Write down general information about your project. It is a good idea to always put a project status in the readme file. This is where you can add it. 


## Usage
***

- `(1)` Load the BMP image
- `(2)` Preview of the loaded image
- `(3)` Choose the conversion method
- `(4)` Convert the image into bitmap array
- `(5)` The generated byte array (can be copied to your arduino code)
- `(6)` To save the byte array to .txt file

![Image text](./images/GUI_Screenshot.png)


## Dependency
***
To make the script work, you must install the following modules:

Pillow, for  image manipulation module:
```
pip install Pillow
```
PyQt5, a framework for gui development
```
pip install PyQt5
```
NumPy package for array computing
```
pip install numpy
```



## Todo
***
- Add a Checkbox to give the user the possibility to invert the image colors




## References
***
Some helpful reference used to write this program:

- [Displaying an image using PyQt5 in Python](https://www.codespeedy.com/displaying-an-image-using-pyqt5-in-python/)
- [xbm editor](https://xbm.jazzychad.net/)
- [image2cpp](http://javl.github.io/image2cpp/)