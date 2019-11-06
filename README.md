[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/Jc11235/ML_Class_Jupyter_Demos/master)

This setup.py was originally adapted from [https://github.com/kennethreitz/setup.py](https://github.com/kennethreitz/setup.py) by @cranmer





## Start a local Jupyter server server

1. Requirements

* Python 3.7
* Python modules defined in `requirements.txt` (installed in the second step)
* Virtual environment

Start by installing Python 3.7 or greater on your local machine. See this link, https://www.python.org/downloads/ , for information on how to do this on your system.

```bash 
pip install virtualenv
```

2. Clone the project and install the requirements from requirements.txt

```bash
git clone https://gitlab.com/kuelumbus/agniweb AgniWeb && cd AgniWeb
virtualenv venv -p python3.7
source venv/bin/activate
pip install -r requirements.txt
```

