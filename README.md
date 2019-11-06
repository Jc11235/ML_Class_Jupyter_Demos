[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/Jc11235/ML_Class_Jupyter_Demos/master)

This setup.py was originally adapted from [https://github.com/kennethreitz/setup.py](https://github.com/kennethreitz/setup.py) by @cranmer





## Start a local Jupyter server server

1. Requirements

* Python 3.7
* Python modules defined in `requirements.txt` (installed in the second step)
* Virtual environment
* Homebrew (OSX users)

Start by installing Python 3.7 or greater on your local machine. See this link, https://www.python.org/downloads/ , for information on how to do this on your system. 

If you install python 3.7, you will replace the X in the following command with 3.7. If you use pip without some value for X you will be using your system's default python version, which may not be greater than or equal to 3.7.

```bash 
pipX install virtualenv
```

If you are using OSX it is in your best interest to install Homebrew to make installing matplotlib smoothly. Please see this link, https://brew.sh/ , for Homebrew installation.

2. Clone the project and install the requirements from requirements.txt

```bash
git clone git@github.com:Jc11235/ML_Class_Jupyter_Demos.git demos && cd demos
virtualenv venv -p python3.7
source venv/bin/activate
pip install -r requirements.txt
```

