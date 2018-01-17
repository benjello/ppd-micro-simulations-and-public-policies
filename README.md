# PPD Micro-Simulations and Public Policies

## Before first session

### Installing the software

We will try to work on the desktop computers in the room R2-07 (computer lab) but it is strongly recommended that you install the python software on your laptop computer.

For the tutorial, you will need to install the Python langage together with some specific packages. You need to have a functional internet connection.

#### Install Python 2.7

Start by downloading Python 2.7 from [this page](https://www.python.org/downloads/).

*Be careful to download the right version, i.e 2.7 !*

Install the software.

#### Install additional packages.

Open a console/terminal/command tool on your computer and type:

```shell
pip install matplotlib jupyter
```

You should be able to use Jupyter Notebook wich is now installed on your computer.

```
jupyter notebook
```

#### Troubleshouting on Microsoft Windows systems:

 If the command

```
pip install jupyter matplolib
```

does not install the packages, you should try the following steps:
  - Add `C:\Python27\Scripts` to your `PATH`
  - Type the command
```
python -m pip install jupyter matplotlib
```
  - If  you get an SSL certificate error
```
python -m pip install --index-url=http://pypi.python.org/simple/ --trusted-host pypi.python.org jupyter matplotlib
```

### Take the Python crash course (*required*)

#### Get familiar with the notebook

It is require to read [this excellent introduction to the notebook](http://nbviewer.jupyter.org/github/ipython-books/minibook-2nd-code/blob/master/chapter1/13-nbui.ipynb)

#### Learn some Python

It is require to read and try to execute [this introductory notebook to the Python langage](http://nbviewer.jupyter.org/github/ipython-books/minibook-2nd-code/blob/master/chapter1/14-python.ipynb)

You can also have a look at one of these Python tutorials:
  - https://www.learnpython.org/

  - [Lear Python in 10 minutes](https://www.stavros.io/tutorials/python/)

  - [Learn Python in Y minutes](https://learnxinyminutes.com/docs/python/)

