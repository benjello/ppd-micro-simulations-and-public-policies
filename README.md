# PPD Micro-Simulations and Public Policies


Actions students have to take

* [Before first session](#before-first-session)
* [Before second session](#before-second-session)

## Before first session

### Install the software

We will try to work on the desktop computers in the room R2-07 (computer lab) but it is strongly recommended that you install the python software on your laptop computer.

For the tutorial, you will need to install the Python langage together with some specific packages. You need to have a functional internet connection.

#### Python

You can install a minimal Python or use Anaconda

##### Minimal install

Start by downloading Python 3.9 from [this page](https://www.python.org/downloads/).

*Be careful to download the right version, i.e at least a Python 3 version !*

Install the software.

##### Anaconda

Download Anaconda for Python 3.9 from [this page](https://www.anaconda.com/products/individual) and install the software.

Create an environment for this class

```shell
conda create --name ppd python=3.9
```

#### Install additional packages.

Open a console/terminal/command tool on your computer and type:

```shell
pip install matplotlib jupyter
```

or if you use Anaconda

```shell
activate ppd
conda install matplotlib jupyter
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
  - Add the Python `Scripts` directory (it looks like `C:\Python37\Scripts`) to your `PATH`
  - Type the command
```
python -m pip install jupyter matplotlib
```
  - If  you get an SSL certificate error
```
python -m pip install --index-url=http://pypi.python.org/simple/ --trusted-host pypi.python.org jupyter matplotlib
```

#### Worst case scenario

Nothing works, try the launch binder badges whenever the appear below.


### Take the Python crash course (*required*)

#### Get familiar with the notebook

It is require to read [this excellent introduction to the notebook](http://nbviewer.jupyter.org/github/ipython-books/minibook-2nd-code/blob/master/chapter1/13-nbui.ipynb).

#### Learn some Python

It is require to read and try to execute [this introductory notebook to the Python langage](http://nbviewer.jupyter.org/github/ipython-books/minibook-2nd-code/blob/master/chapter1/14-python.ipynb). [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/benjello/ppd-micro-simulations-and-public-policies/master?filepath=notebooks%2F14-python.ipynb)

You can also have a look at one of these Python tutorials:
  - [The official learn Python tutorial]( https://www.learnpython.org/)

  - [Learn Python in 10 minutes](https://www.stavros.io/tutorials/python/)

  - [Learn Python in Y minutes](https://learnxinyminutes.com/docs/python/)

### Load the following notebooks for the first session

- [Python crash course with exercises](./notebooks/python_crash_course_student.ipynb). [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/benjello/ppd-micro-simulations-and-public-policies/master?filepath=notebooks%2Fpython_crash_course_student.ipynb)

- [Explore the Senegalese tax and benefits system](./notebooks/Senegal-student.ipynb). [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/benjello/ppd-micro-simulations-and-public-policies/master?filepath=notebooks%2FSenegal-student.ipynb)

## Before second session

- [Complete the exploration of the Senegalese tax and benefits system by doing the exercises](./notebooks/Senegal-student-2.ipynb). [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/benjello/ppd-micro-simulations-and-public-policies/master?filepath=notebooks%2FSenegal-student-2.ipynb)

- Install the survey capabilities of openfisca-senegal:
```
pip install openfisca-senegal[survey]
```

- We will manipulate [dataframes](http://pandas.pydata.org/): learn how to use them by having a look at this [introduction](http://pandas.pydata.org/pandas-docs/stable/10min.html)

- Download the [the second session notebook](./notebooks/Fake-data-Senegal.ipynb). [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/benjello/ppd-micro-simulations-and-public-policies/master?filepath=notebooks%2FFake-data-Senegal.ipynb)

<!--

## After the second session:

You now have access to the complete notebooks with exercise solutions
 - Download the [the first session notebook with exercises solutions](./notebooks/Senegal-exercices-solutions.ipynb). [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/benjello/ppd-micro-simulations-and-public-policies/master?filepath=notebooks%2FSenegal-exercices-solutions.ipynb)

 - Download the [the second session notebook with exercises solutions](./notebooks/Fake-data-Senegal.ipynb). [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/benjello/ppd-micro-simulations-and-public-policies/master?filepath=notebooks%2FFake-data-Senegal.ipynb) -->
