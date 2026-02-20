# Main_Project

## 🚀using uv over pip to install dependencies?

`uv` is an extremely fast Python package installer and dependency manager.  

uv is significantly faster and simplifies dependency management.

---

## 📦 Features of uv

- ⚡ Very fast package installation
- 📁 Automatic virtual environment management
- 📜 Uses `pyproject.toml`
- 🔒 Reproducible dependency locking
- 🐍 Python version management via `.python-version`

---

## 🛠️ Project Setup

### 1️⃣ Install uv

```bash
curl -Ls https://astral.sh/uv/install.sh | sh
```
```bash on terminal
pip install uv
```

## After installing uv on your terminal or system
```bash
uv init
```
this helps to initialize the project
it Creates:

pyproject.toml:-This will show you the details of the project

.python-version:-This will tell you the version of the python

## After initializing we will create an virtual enviornment for our project
```bash
uv venv
```
🐍 What is venv?

venv = Virtual Environment

It creates an isolated Python environment for your project.

That means:

Each project can have its own packages
No conflict between projects
No pollution of global Python

## Activating the venv

In windows write on terminal
```
.venv\Scripts\activate
```

In mac
```
source .venv/bin/activate
```


## Installing Depandancies
if we use pip we can write 
pip install numpy
pip install pandas

if we use uv we just write
```
uv add numpy pandas
```

if we want to run the project 
In terminal write
```
uv run main.py
or
python main.py
```

## If You Want To Know More About uv 
check this out:-
YT-- Tech With Tim
Search:-- Uv introduction or uv initializion or uv (only)

