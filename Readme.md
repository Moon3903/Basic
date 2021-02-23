## Basic Python

### Prerequisites
- [Anaconda navigator](https://docs.anaconda.com/anaconda/install/windows/)
- [PyCharm](https://www.jetbrains.com/pycharm/download/#section=windows) or [Visual Studio Code](https://code.visualstudio.com/download)
- python 3

### Installing NumPy, Matplotlib, and OpenCV
1. Open Anaconda Navigator
2. Go to Environment menu
3. Create a new environment 
4. Open your environment terminal (click your new environment then press the *play* button '►')
5. run this script in the terminal
```
python -m pip install --upgrade pip
pip install numpy
pip install matplotlib
pip install opencv-python
```

#### Check
test your environment by running these code
```
python3
```
Output Example:
```
Python 3.6.9 (default, Oct  8 2020, 12:12:24) 
[GCC 8.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
```
Input again
```
>>> import cv2
>>> cv2.__version__
```

Output
```
'4.5.1'
```
*note : example version of opencv

### Configure Interpreter
**Select from Existing environment**
- [For VSCode](https://code.visualstudio.com/docs/python/environments)
- [For PyCharm](https://docs.anaconda.com/anaconda/user-guide/tasks/pycharm) 

### For Mac
not recommended
https://www.pyimagesearch.com/2018/08/17/install-opencv-4-on-macos/
