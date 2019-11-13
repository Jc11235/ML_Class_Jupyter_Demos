Before you start, download the project by clicking the green download button above. Once it's downloaded, unzip the file and place it in your Desktop.

## Start a local Jupyter server via Anaconda
1. Download Anaconda ( https://www.anaconda.com/distribution/ )
2. Open the Anaconda navigator using:

Mac/Linux via a shell terminal
```bash
anaconda/navigator
```

Windows via search
```bash
anaconda navigator
```

3. Once the navigator is open, click the lauch button under the Jupyter icon.
4. Once the notebook is open, navigate to the unzipped folder.
5. Click on a given notebook to run it.

## Start a local Jupyter server via Python

1. Make sure you have Python installed on your local system (https://www.python.org/downloads/). If you installing on Windows, please click the option during installation that allows the installer to add Python to the environment variable.


Then, navigate to directory (after extraction of the downloaded zip file) by running *be aware that backslahes and forward slahses are OS dependant*:

```bash
cd PATH/TO/DIRECTORY
```

2. Once in the directory, run the following commands:

Mac/Linux
```bash
source venv/bin/activate
pip install -r requirements.txt
```

Windows
```bash
.\venv\bin\activate
pip install -r requirements.txt
```

3. Run the following command to start your jupyter server:

```bash
jupyter notebook
```

## Run the notebook from a Binder server

If you are having trouble installing the notebooks (Windows machines could be problematic), you can click on the "launch binder" icon below to launch a binder server.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/Jc11235/ML_Class_Jupyter_Demos/master)

This binder server is setup by [https://github.com/kennethreitz/setup.py](https://github.com/kennethreitz/setup.py) by @cranmer

