# About

Minimal configuration to begin using jupyter-notebooks with python and octave. 

Useful for me for coursera or other MOOCs.

# Pre-install

Ensure you have `python3.6` installed. [More info](https://www.python.org/downloads/)

Ensure `pip` or `pip3` is installed. [More info](https://pip.pypa.io/en/stable/installing/)

Ensure `octave` is installed. [More info](https://www.gnu.org/software/octave/download.html)

### Unbuntu/Debian

If you have a linux machine, you only need to do this:

```
sudo apt install python3.6 python3.6-dev curl octave
curl -sL https://bootstrap.pypa.io/get-pip.py | python3.6 -
sudo pip install pipenv
```

# Installation

1. Clone or download this repo.

```
git clone git@github.com:Woile/jupyter-notebooks-lab.git
cd jupyter-notebooks-lab
```

2. Install dependencies:

```
pipenv install
```

3. Launch your jupyer-notebook!

```
pipenv run jupyter notebook
```

# Using different Kernels in same notebook

1. Open your notebook
2. Go to `Kernel > Change Kernel` and select whatever u want

By doing this you can write in both languages in the same notebook.
