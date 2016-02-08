Image_Processing_for_Wedding
====

This tool is making Dialogue Model for Slack

Thsi tool has 3 functions

1: Slack Communication
2: Learning by the Chainer 
3: Collect Twitter Data

## Description
This tool is making the Dialogue Model

If you see the detail about it, you see the below<br> 

http://qiita.com/drafts/79ca7deeb976f50126d7

#
### Install

If you don't install pyenv and virtualenv you have to install bellow
####Prepare Install
linux
```
apt-get install pyenv 
apt-get install virtualenv 
```
Mac
```
brew install pyenv 
brew install virtualenv 
```

####Prepare Inastall2
```
pyenv install 3.4.1
pyenv rehash
pyenv local 3.4.1
virtualenv -p ~/.pyenv/versions/3.4.1/bin/python3.4 my_env
source my_env/bin/activate

```

```
pip install -r requirement.txt 
```

####Prepare the Code

Computer Vision Sample Code

```
git clone https://github.com/jesolem/PCV
```



####Prepare the Data

```
Python Imaging Library (PIL)
>[Python Imaging Library (PIL)]http://www.pythonware.com/products/pil/<br>


Installing a library bellow

##Requirements


```
    Python 3.4+
	numpy
    chainer
    ipython
    notebook
    jinja2
    pyzmq
    tornado
    PyYAML
```

####Confirm library

```
ipython
```

#
### Usage 
#
Learning Chainer

```
*You execute python 
ipython notebook
```

#
### Code Directory Structure 
#
```
Image Processing for Wedding
  - computer_vision.ipynb　　... notebook
  - PIL/ 　　　　　　　      ... Python Image Library
  - PCV/ 　　　　　　　      ... Python Computer Vision Code
```
#
### Licence
#
```
The MIT License (MIT)

Copyright (c) 2015 Masaya Ogushi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
#
### Author
#
[SnowMasaya](https://github.com/SnowMasaya)
### References 
#
>[Programming Computer Vision with Python]http://programmingcomputervision.com/downloads/ProgrammingComputerVision_CCdraft.pdf<br>
