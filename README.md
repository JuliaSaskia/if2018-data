# Data Analysis with Python

## Prerequisites

### 1. Ensure you have Python 3.6 or 3.7 installed, otherwise install it
* Windows: Download from https://www.python.org/downloads/, activate the
option "Add Python to PATH"
* Mac: Download from https://www.python.org/downloads/ (or install via brew)
* Linux:
    * Ubuntu 18.04 has Python 3.6 preinstalled, however one additional package is required:     
    `apt-get install python3-venv`

### 2. Install Jupyter within a virtualenv
* Create a new directory and put the requirements.txt there (or clone the git repo)
* Within the directory create a virtualenv:
    * Depending on your system and previous installed Python versions you need to either use python3 or just python
    * `python3 -m venv venv`
    * `python -m venv venv`
* Activate the virutalenv
    * Windows: `venv\Scripts\activate.bat`
    * Mac and Linux: `source venv/bin/activate`
    * Afterwards your command prompt is prefixed with "(venv)"
* Install Jupyter:
    * `pip install -r requirements.txt`

### 3. Start Jupyter
* `jupyter notebook`
