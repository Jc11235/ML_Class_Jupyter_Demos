## Start a local Jupyter server

1. Requirements

* Anaconda
* Python modules defined in `requirements.txt` (installed in the second step)
* Virtual environment

Start by installing anaconda, https://docs.anaconda.com/anaconda/install/ , on your local machine. You should install an anaconda version that uses Python 3.7 or greater. Then install a python virtual environment by the following command:

```bash 
pip install virtualenv
```

2. Clone the project and install the requirements from requirements.txt

```bash
git clone git@github.com:Jc11235/ML_Class_Jupyter_Demos.git demos && cd demos
virtualenv venv -p python3.7
source venv/bin/activate
pip install -r requirements.txt
```

3. Start your Jupyter server
Run the following command to start your jupyter server:

```bash
jupyter notebook
```

## Run the notebook from a Binder server

If you are having trouble installing the notebooks (Windows machines could be problematic), you can click on the "launch binder" icon below to launch a binder server.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/Jc11235/ML_Class_Jupyter_Demos/master)

This binder server is setup by [https://github.com/kennethreitz/setup.py](https://github.com/kennethreitz/setup.py) by @cranmer

