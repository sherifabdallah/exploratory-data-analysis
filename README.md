# EDA

# Egyflix
Egyflix is a free streaming service that allows our members to watch TV shows and movies, You can also download TV shows and movies to your iOS, Android, Windows 10, Macos or Linux and watch.

   

## Table of Content
- [EDA](#eda)
  * [Tools](#tools)
  * [How to run](#how-to-run)
  * [Author](#author)
 
## Tools
1. Python
2. Pandas
3. Matplotlib
4. Seaborn


## How to run
* Enter the directory where the script is located then type the following to the console
```sh
$ git clone https://github.com/sherif-abdallah/exploratory-data-analysis exploratory-data-analysis
```
* Install Python 3.8 venv, pip and compiler

```sh
$ sudo apt-get install python3.8 python3.8-venv python3-venv
```

* Create a virtual environment to install dependencies in and activate it:

```sh
$ python3.8 -m venv venv
$ source venv/bin/activate
```

* Then install the dependencies:

```sh
(venv)$ cd exploratory-data-analysis
(venv)$ python -m pip install --upgrade pip
(venv)$ python -m pip install -r requirements.txt
```
Note the `(venv)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv`.


* Finally open  the Jupyter Notebook Script
```sh
(venv)$ python -m notebook notebook.ipynb
```
* And navigate to `http://127.0.0.1:8888`.

## Author
[Sherif Abdullah](https://github.com/sherif-abdallah)
