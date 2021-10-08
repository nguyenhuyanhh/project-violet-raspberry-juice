# Python Demo

## Installation

* Latest version: 3.10.0 (just released few days ago!)
* Windows: download Python installer from https://www.python.org/ (Python 3.9+ requires Windows 10)
* Windows (VDI): get it from Dev Shell
* Unix-like (Mac/ Linux): it's probably already installed! If not, it is easily obtainable from package manager.

## Virtual environments (`venv`) & package management (`pip`)

Create a virtual environment:

```bash
$ python3 -m venv .venv 
```

Virtual environment would be created in a `.venv` subfolder, but not *active* yet. To *activate* the virtual environment:

```bash
$ source .venv/bin/activate
```

To deactivate from the virtual environment:

```bash
$ deactivate
```

Within the virtual environment, you can install dependencies using `pip`. Usually they are specified in a text file, `requirements.txt`:

```bash
$ pip install -r requirements.txt
```