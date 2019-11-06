[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/Jc11235/ML_Class_Jupyter_Demos/master)

This setup.py was originally adapted from [https://github.com/kennethreitz/setup.py](https://github.com/kennethreitz/setup.py) by @cranmer


## Start a local Jupyter server

1. Requirements

* Python 3.7
* Python modules defined in `requirements.txt` (installed in the second step)
* Virtual environment
* Homebrew (OSX users)

Start by installing anaconda, https://docs.anaconda.com/anaconda/install/ , on your local machine. Then install apython visrtual environment by the following command:

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

If you are having trouble installing the notebooks (Windows machines could be problematic), you can click on the "launch binder" icon at the top of this readme file to launch a binder server.

