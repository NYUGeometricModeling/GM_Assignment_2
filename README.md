[![Build Status](https://travis-ci.org/NYUGraphics/GM_Assignment_2.svg?branch=master)](https://travis-ci.org/NYUGraphics/GM_Assignment_2)
# Assignment 2: Implicit Surface Reconstruction

This repository contains the viewer code and data files you'll need for
assignment 2.

## Getting Started
To begin, follow the link from Assitant to create the repository in this organization.

Next, please refer to the [General Rules and Instructions](https://github.com/danielepanozzo/gp/raw/master/guidelines.pdf)
handout for instructions on installing LIBIGL and its dependencies.

## Building and Completing the Assignment
You
should be able to build the viewer code:
```
mkdir build && cd build && cmake ..
make
```
Please report any problems you run into on this repository's Issues tab on
GitHub.

When the build completes successfully, begin implementing the missing blocks in
src/main.cpp as described by the assignment PDF.

## Submitting
When you finish the assignment, you will submit it by pushing it to a the
repository on our organization.

1. Follow the link sent out by Assistant
2. Push your code to the repository (which will be created automatically):
```
git push https://github.com/NYUGeometricModeling/Geometric_Modeling_Assignment2_USER
```

## Travis-CI
Every submission must build on Linux before it can be graded/considered
complete. To check this, you will use Travis-CI, a tool for automatically
rebuilding your code each time you push it to GitHub.
