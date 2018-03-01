# DataScienceTrack
HackRice 7.5 - Data Science Track

## Introduction

Have you ever looked for shoes online and found related advertisements on facebook and other websites continuously for a week? Or say, you’re chatting with your best friend and the keyboard suggests you the exact words that you want to use in your sentence? How does YouTube show all your favourite videos on your homescreen?

Well these are all the applications of Data Science. Over the last few years Data Science has really changed our concept of technology. Our lives are a lot easier as compared to 10yrs ago, and this is all because of data science. Data Science has really pulled the ends between fiction and technology. Right from LinkedIn to Tinder, data science is being used everywhere.

This tutorial will give you a brief introduction into some basic applications of machine learning and data science along with example prompts to compete in this track. To compete though, any data science project will do.

### A Quick Note on this Tutorial

The steps below outline how to setup your computer to view and run the code in this repository using JuPyter Notebook. If you just want to read through the tutorial, you can [view the notebook online through GitHub](https://github.com/abhmul/DataScienceTrack/blob/master/Tutorial.ipynb)

## Tools needed

Tools We Need
This tutorial requires Python and JuPyter Notebook. To run our Python code we need:

* Either [Python 2 or 3](https://www.fullstackpython.com/python-2-or-3.html) (Python 2 must be at least version 2.7.9, Windows will require python3)
* [pip](https://pip.pypa.io/en/stable/) and
  [virtualenv](https://virtualenv.pypa.io/en/stable/) to handle Python
  [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) to get the data and code
  
  
If you do not have python currently, we suggest installing [Anaconda](https://www.anaconda.com/download/) (use the python3 version) since it includes almost everything we need.

In addition, Windows users will need To install Cygwin (more on this below).

### Cygwin installation (Windows users only)

Visit [this website](https://cygwin.com/install.html) to install Cygwin.  For each screen on the installer where it provides a default option, the default is fine.  However, there is one screen that asks you to "Choose A Download Site".  Any site should work; however, some work better than others.  'https://mirror.steadfast.net' works well.

### Pip installation
If you don't already have pip installed, we'll go ahead an install that now because it will be essential 
for the rest of the project. 

Visit [this website](https://pip.pypa.io/en/stable/installing/) to install pip. Follow the instructions, and once you 
think you're done, type `which pip` to check that pip has been installed. You should see the version number of the pip 
you installed print to your terminal.

## Establishing your environment

### Using Virtualenv

We now know what tools we need for our project so let's get our development
environment set up. Go to the terminal (or Cygwin on Windows) and
change into the directory where you want to store this project. Within
that directory, create a new virtualenv to isolate our application
dependencies from other Python projects.

    virtualenv datascience

Activate the virtualenv (Mac/Linux):

    source datascience/bin/activate

Activate the virtualenv (Windows):

    source datascience/Scripts/activate

### Using Anaconda

Go to the terminal (or Cygwin on Windows) and
change into the directory where you want to store this project. Within
that directory, create a new conda environment to isolate our application
dependencies from other Python projects.

```
conda create --name datascience
```
Activate the virtualenv:this 

```
source activate datascience
```

### Downloading the code and data

You should currently be in the directory where you want to store this project. Run the following command to clone the data and code into this directory
```
git clone https://github.com/abhmul/DataScienceTrack.git
```

You should now have a folder called `DataScienceTrack`. Change your directory in your terminal to this directory (run something like `cd DataScienceTrack`). You now have all the code and data for the projects

### Installing necessary packages

We've included a `requirements.txt` file so `pip` knows which packages to install. To make sure we're using the right `pip` (the one associated with our virtual environment) run
```
which pip
```
The terminal should print out something along the lines `.../datascience/bin/pip` where the `...` is some stuff specific to your computer. **If this is not the case, flag down a mentor to help you out.** If you're all good, then run the following command (from inside the `DataScience` folder).
```
pip install -r requirements.txt
```
This should go ahead and grab any python packages we need that you don't already have. **If something goes wrong here, make sure to ask for help**.

## Preparing the data

You should currently still be in the `DataScienceTrack` folder. In here go ahead and extract `data.zip` into a folder called `data`. If you're curious, you can take a look at these data (they are just a bunch of images).

## Running the notebook



