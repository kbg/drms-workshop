[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kbg/drms-workshop/master?filepath=index.ipynb)

# DRMS access using Python

## Prerequisites

If you want to follow the examples on your own laptop, you need a working Python installation, including the [Scientific Python](http://www.scipy.org/) software stack (NumPy/SciPy, Matplotlib, IPython, Pandas). In addition, you need to install the [DRMS Python package](https://pypi.python.org/pypi/drms), and if you want to clone the Git repository, you also need to install [Git](https://git-scm.com/).


### Python

The recommended way of installing Python, is to use the [Anaconda Python distribution](https://www.continuum.io/anaconda-overview), which is available for Windows, Mac and Linux. Just download the Python 3 version of the installer from the [Anaconda download page](https://www.continuum.io/downloads) and follow the instructions. After that you should have a working Python environment, including most of the commonly used scientific Python packages.

A good place to start out with the scientific use of Python is [scipy.org](http://www.scipy.org/). A very nice compilation of tutorials can be found in the [SciPy Lecture Notes](http://www.scipy-lectures.org/index.html).


### DRMS package

Install the [DRMS Python package](https://pypi.python.org/pypi/drms) using the shell command

    pip install drms

Make sure that you activated your Anaconda environment before you enter command above in your terminal, or put the Anaconda directory in your `PATH`. Feel free to contact me, if you have any problems, or ask somebody who attended the recent Python workshop (they should know how it works :o)).

The documentation for the `drms` module is available on [Read the Docs](http://drms.readthedocs.io/), which also includes a detailed [tutorial](http://drms.readthedocs.io/en/stable/tutorial.html). In addition, there are many [example scripts](https://github.com/kbg/drms/tree/master/examples) in the `examples` directory of the [source code package](https://github.com/kbg/drms/releases/latest) of the `drms` module. Finally there is also a [HMI Science Nugget](http://hmi.stanford.edu/hminuggets/?p=1757) on the DRMS Python package.


### Register at JSOC

To be able to make data export requests from JSOC, you need to register your email address on the [JSOC email registration](http://jsoc.stanford.edu/ajax/register_email.html) webpage. Just enter your email address in the "Notify" field and press the button below (the "Requester" field can be left empty). After that you should receive an email which you just need to reply to, in order to finalize the registration.


### Git

If you want to use Git, you can download and install it from the [Git download page](https://git-scm.com/downloads). If you never used Git before, you can learn more by following the Software Carpentry [Git Tutorial](http://swcarpentry.github.io/git-novice/).

Using Git is not necessary (but recommended) for this workshop. If you really don't want to use Git, you can click on the green "Clone or download" button and select "Download ZIP". Keep in mind that you cannot easily pull any updates this way, nor track your own changes.


### SunPy

[SunPy](http://sunpy.org/) is *not needed* for this tutorial. If you are interested in using it, you can have a look at material of the recent [Python/SunPy workshop](https://github.com/SolarDrew/freiburg-2017-02) that took place at KIS in February.


## Getting started

1. Clone the Git repository from Github:
```
    git clone https://github.com/kbg/drms-workshop.git
```
2. Change to the `drms-workshop` directory and start Jupyter:
```
    cd drms-workshop
    jupyter notebook
```
3. Open the `index.ipynb` from the file list in your webbrowser.


## Resources

- [SciPy.org](http://www.scipy.org/)
- [SciPy Lecture Notes](http://www.scipy-lectures.org/index.html)
- [DRMS module on Github](https://github.com/kbg/drms/)
- [DRMS module documentation](http://drms.readthedocs.io/)
- [HMI Science Nugget](http://hmi.stanford.edu/hminuggets/?p=1757)
- [JSOC webinterface](http://jsoc.stanford.edu/ajax/lookdata.html)
- [JSOC data access](http://jsoc.stanford.edu/jsocwiki/JsocDataAccess)
- [Python Workshop @ KIS, February 2017](https://github.com/SolarDrew/freiburg-2017-02)
