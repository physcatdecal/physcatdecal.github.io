---
title: "Homework 1"
date: 2021-01-15T18:01:20-08:00
draft: false
---

This homework is due on 8 February 2021 at 11:59PM via Gradescope. Please submit a .zip file containing

- `physcat_sp21_hw1_p1.ipynb`
- `physcat_sp21_hw1_p3.ipynb`

which you can download below.

## Setup

Welcome to PhysCat! Like many courses, the first thing you're going to have to do is set up a programming environment that has all the libraries you'll need. For at least the first portion of this course we will be using anaconda to handle package management. There are three ways to install it, that we know to be compatible with this course. However, if you are new to computers we strongly recommend the first. If you encounter issues with any of these steps please let us know ASAP so we can help you with a workaround; chances are any issues are not your fault, as we have not been able to test these steps on every type of system.

#### Anaconda Navigator

Anaconda Navigator is a very featured Graphical User Interface which you can use to interface with anaconda. The best way to install it is to follow the instructions on [Anaconda's Website](https://docs.anaconda.com/anaconda/install/) for your machine. If you are not comfortable with a command-line, we **STRONGLY** recommend that you take this route. Once you have completed this setup move on to the *Environment Installation* section.

**Note:** You may get a warning during installation about having a space in your path name. You should be able to safely ignore this.

#### Miniconda

If you are comfortable with the Command Line and want a smaller command-line-only installation of conda without the cruft, follow the [miniconda setup instructions](https://docs.conda.io/en/latest/miniconda.html) for your platform. Although this is a more bare-bones installation, it takes up significantly less disk space and is probably more to the liking of people who have a little bit of python experience.

#### Distribution Package Manager (Linux Only)

If you happen to be running linux and don't want something like Anaconda cluttering up your system, you can simply install the `conda` package or its analogue for whatever system you are running. We will not officially support this, but feel free to message *`@Aled`* on Discord if you have any trouble with this route.

### Environment Installation

Environment configuration files for anaconda are stored in `.yml` files that contain a listing of all the packages you will need. Download the environment yml for your system [here](http://spooky.ld-cd.net/physcat/environment.yml) and save it in your downloads folder.
Once you've done this follow the step below matching how you installed Anaconda

#### Anaconda Navigator Environment Setup

If you installed Anaconda with Anaconda Navigator, open it up and click the environments button on the left hand side of the screen, then click the import button along the bottom of the window. Enter `physcat` for the name and select the yml you [downloaded](http://spooky.ld-cd.net/physcat/environment.yml) as the specification file and hit `import`. Anaconda will then think for a few minutes while it downloads all the software necessary for this course.

Once Anaconda finishes installing its packages click the "play" button next to the `physcat` environment and select "Open with Jupyter Notebook", and then move onto the checkpoint.

#### Command Line Environment Setup

If you chose to install conda through one of the other means, navigate to the directory in which you [downloaded](http://spooky.ld-cd.net/physcat/environment.yml) the environment yml and run the following command:

```shell
conda env create -f environment.yml
```

This will run for a few minutes and download all the required packages; when that is complete run the commands

```shell
conda activate physcat

jupyter-notebook
```

to enter the environment and launch a notebook session in your browser. If that all works, then proceed to the Checkpoint.

### Part 1: Checkpoint

Now that you've successfully completed installation download our test notebook from [here](/homeworks/physcat_sp21_hw1_p1.ipynb).

### Part 2: Python Review

Download and run through the Python Review notebook [here](/homeworks/physcat_sp21_hw1_p2.ipynb).

### Part 3: NumPy and Monte Carlo Simulation

Download and solve the NumPy and Monte Carlo Simulation notebook [here](/homeworks/physcat_sp21_hw1_p3.ipynb).

