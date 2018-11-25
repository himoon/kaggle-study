# Kaggle Study 2018 - Chapter 02

## Prerequisites

```sh
# run terminal, then verify whether following commands work.
python --version
pip --version
virtualenv --version # if failed, run "pip install virtualenv"
```

## Setup

```sh
# run terminal, then execute following commands.
git clone https://github.com/himoon/kaggle-ch02.git
cd kaggle-ch02
virtualenv env
source env/bin/activate # macOS
.\env\Scripts\activate # Windows

pip install pylint autopep8 # install pip modules for vscode
pip install numpy scipy matplotlib pandas ipython jupyter kaggle # install pip modules for kaggle
```

## Download the data

```sh
# download the data, then copy the date into ./kaggle_santander_product_recommendation/input
kaggle competitions download santander-product-recommendation
```

## Jupyter

```sh
jupyter notebook
```

## References

https://blogs.msdn.microsoft.com/pythonengineering/2018/11/08/data-science-with-python-in-visual-studio-code/
https://code.visualstudio.com/docs/python/editing#_jupyter-code-cells
