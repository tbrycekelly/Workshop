# Python for Oceanographers #

Workshop dates: TBA
Workshop Location: Florida State University

## Course Topics ##

* Introduction
* Python Does Data
* Python Does plotting
* Python as a Scientific language

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

### Windows ###

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

    git clone https://github.com/tbrycekelly/Workshop _dir_

Here _dir_ is simply the location you want to save your copy of the workshop files. For example, _~/Desktop_ would place it on your desktop.
