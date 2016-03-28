# Python for Oceanographers #

Workshop dates: TBA (June)
Workshop Location: Florida State University. TBA

To learn about me, see [here](./misc/About.md)

## Course Topics ##

* Introduction
* Python Does Data
** Loading Data from Various Sources
** Parsing Data
** Cleaning, Filtering, and Transforming Data
* Python Does plotting
** Introduction to Matplotlib
** More Advanced Examples for Oceanography
* Python as a Scientific language
** Python vs Fortran
** Cython for Mission Critical Functions
** Optimization Tips & Tricks

## Schedule (_tentative_) ##

Date | Time | Activity
--- | --- | ---
June 10 | 10:00am | Introduction to VM environment
--- | 12:00am | Break for Lunch
--- | 1:00pm | Working with Python and Modules
--- | 3:00pm | Wrap up for Day
June 11 | 10:00am | Loading Data into Python
--- | 11:30am | Introduction to Python plotting
--- | 12:30pm | Break for Lunch
--- | 1:30pm | Data Analysis and Parsing
--- | 3:00pm | Wrap up for Day

## Setting up the Environment ##

For this workshop, we have a virtual machine (VM) disk that will ensure that all participants will have a unified interface as well as a stream-lined experience.
The disk image will be available once the packages and workshop material has been finalized. (Note: it will be a large file download).

To follow this workshop without the VM image (or to partake in the workshop from home), you will need to download and install the following software packages.

1. Python (>3.0)
2. IPython
3. Jupyter (aka IPython) Notebook
4. git

Detailed instructions on the setup and requirements will be available below.

## Materials and Data ##



## Detailed Instructions ##

These instructions will hopefully allow you to setup all the software necessary for the workshop without recourse to the virtual machine disk image. While it is easiest to use the VM image since it already has the necessary software installed, I also recognize that it is not a long-term solution for those who will continue to use the software moving forward (which I hope is everyone!).

Below you'll find a list of instructions for each of the three usual operating systems (Windows, Mac and Linux). Hopefully these will be enough to get you going, but if not then I would direct you to the wealth of information available through Google, including [Stack Overflow](http://stackoverflow.com/). As always, feel free to contact me if you need assistance with anything specific to this workshop.

### Windows ###

For Windows, I would recommend installing VirtualBox and using the VM image unless you know that you'll want to use the same tools that I use here for you're own work moving forward. I don't want to dissuade you from continuing, but (A) I'm not very familiar with Windows and (B) the Windows environmental variables and commandline can be a genuine pain to setup.

Nevertheless, there is a wealth of information available to help you setup these software packages.

Link to Instructions for:
* python -
* IPython -
* git -
* Jupyter -

### Mac OSX ###



### Linux ###

The first thing you will need to setup is python. Python comes pre-installed on many distros, but to make sure type the following into a terminal Windows.

    which(python)

If it returns a path, then python is installed. If it does not then you will need to install it. For ubuntu-like distos type

    sudo apt-get install python3 python3-pip git

For rpm-based systems type

    sudo yum install python3 python3-pip git

Once you have a working python installation, you will need to use pip (the python package manager) to install the appropriate modules.

    pip3 install jupyter ipython3 nbconvert notebook matplotlib

This will install jupyter (our user interface for this workshop) as well as some helper packages (nbconvert and matplotlib).

Once all of these have been installed, we will need to download the files used in this workshop. For this we'll use git. Git is a popular version management tool used in programing. It can keep track of changes and allow many people to work on a project simultaneously, but for our purposes it is nothing more than a convenient downloader.

    git clone https://github.com/tbrycekelly/Workshop DIR

Here _DIR_ is simply the location you want to save your copy of the workshop files. For example, _~/Desktop_ would place it on your desktop.
