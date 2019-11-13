## Start a local Jupyter server

1. Download the project and install the requirements from requirements.txt
2. Make sure you have Python installed on your local system (https://www.python.org/downloads/). If you installing on Windows, please click the option during installation that allows the installer to add Python to the environment variable.


Start off by downloading a zip file of this repository above. Then, navigate to directory (after extraction of the downloaded zip file), and run the following commands:

Mac/Linux
```bash
source venv/bin/activate
pip install -r requirements.txt
```

Windows
```bash
venv/bin/activate
pip install -r requirements.txt
```

2. Start your Jupyter server

Run the following command to start your jupyter server:

```bash
jupyter notebook
```

## Run the notebook from a Binder server

If you are having trouble installing the notebooks (Windows machines could be problematic), you can click on the "launch binder" icon below to launch a binder server.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/Jc11235/ML_Class_Jupyter_Demos/master)

This binder server is setup by [https://github.com/kennethreitz/setup.py](https://github.com/kennethreitz/setup.py) by @cranmer

