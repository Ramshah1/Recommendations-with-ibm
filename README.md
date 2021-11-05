# Recommendations-with-ibm

## Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#project-motivation)
3. [File Description](#file-description)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing-authors-and-acknowledgements)

## Installation
### Dependencies
* Python >=3.7
* numpy >= 1.21.1
* pandas >= 1.3.1
* seaborn >= 0.11.1

### User Installation
Assuming you already have Python>3.7 up and running, the easiest way to install 
the requirements is using **pip** or **conda**. This tutorial assumes using _pip_
for the installation purposes.

Create a virtual environment to set up the project. (Optional Step)

``
python3 -m venv <my_env>
``

cd to the root directory of the code and install the requirements using

``
pip install -r requirements.txt
``

## Project Motivation
For this project, I have analyzed the interactions that users have with 
articles on the IBM Watson Studio platform, and make recommendations to them 
about new articles you think they will like.

## File Description
For the purpose of answering above questions, this project contains a single 
notebook that addresses the questions. The data under consideration is available
as two csv files in the data folder.

## Results
The findings of the analysis are discussed in the jupyter notebook with the 
title "Recommendations_with_IBM.ipynb"

## Licensing, Authors, and Acknowledgements
A special thanks to IBM for making this data available to explore, and 
to Udacity for all the resources and help in completing this project.
