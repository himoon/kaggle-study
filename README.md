# Kaggle study

## Prerequisites

```sh
# run terminal, then verify whether following commands work.
python --version
pip --version

# install pip modules for vscode
pip install pylint autopep8

# install pip modules for kaggle
pip install numpy scipy matplotlib pandas ipython jupyter

# install virtualenv module
pip install virtualenv
virtualenv --version # if failed, run "pip install virtualenv"
```

## Setup

```sh
# run terminal, then execute following commands.
git clone https://github.com/himoon/kaggle-study.git
cd kaggle-study
virtualenv env
```

## get data

```sh
kaggle competitions download santander-product-recommendation
```

## Jupyter

```sh
jupyter notebook
```
