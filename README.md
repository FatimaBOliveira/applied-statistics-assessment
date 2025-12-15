# Applied Statistics Assessment

This subdirectory contains my project for the module Applied Statistics in the Higher Diploma in Science in Computing in Data Analytics course, [ATU Galway Mayo](https://www.gmit.ie/).

This README follows the instructions from [Github](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) on how to write README files.

<img src="https://www.simplypsychology.org/wp-content/uploads/bell-curve.jpg" width="500" height="350"> *Image from [simplypsychology](https://www.simplypsychology.org/normal-distribution.html)*

## About this project

This project focuses on solving statistical problems using Python. This subdirectory includes:

- [problems.ipynb](https://github.com/FatimaBOliveira/applied-statistics-assessment/blob/main/problems.ipynb), a Jupyter Notebook that presents detailed solutions to 4 statistical problems:

    **1. Extending the Lady Tasting Tea** - probability analysis of random guessing in an extended 12-cup experiment;

    **2. Normal Distribution** - simulation comparing sample (ddof=1) and population (ddof=0) standard deviation estimators for normally distributed data.;

    **3. t-Tests** - analysing how type II error rates change with increasing mean differences in two-sample t-tests;
    
    **4. ANOVA** - analysing group mean differences using one-way ANOVA versus multiple t-tests.

- The [requirements.txt](https://github.com/FatimaBOliveira/applied-statistics-assessment/blob/main/requirements.txt) file, shows the libraries and packages needed to run Python code.

The Python code used follows the [PEP 8](https://realpython.com/python-pep8/) coding style as standard.

The main resources for this project are based on the lectures given, web searches, and ChatGPT.

## Purpose of this project

The main objectives of this work are:

- Analyse the data and solve statistical problems with Python packages;
- Explore the different statistical tests available through documentation, to understand when and how these should be used in the field;
- Generate plots that support the analysis and make the results easier to understand;
- Interpret the problems and make meaningful insights with the results obtained.

These assessments were very important for me as a Data Analyst to put into practice the contents learned in class, develop critical thinking in statistical problems and to understand what is being done through the Python packages and functions.

## Getting Started

To use this project, [Anaconda](https://www.anaconda.com/download) and [Visual Studio Code](https://code.visualstudio.com/Download) (VSC) need to be installed. After that, this directory can be [cloned in VSC](https://github.com/MicrosoftDocs/azure-dev-docs/blob/main/articles/javascript/how-to/with-visual-studio-code/clone-github-repository.md) as instructed by Microsoft. 

If the programs are not installed, any user with a GitHub account can access the [GitHub Codespaces](https://docs.github.com/en/codespaces/about-codespaces/what-are-codespaces#benefits-of-github-codespaces) that provides a virtual computer, with many programs included. All the code in the problems can be executed through here.

Alternatively, the notebook can be run virtually in a cloud, through Google Colab at the following link::<a target="_blank" href="https://colab.research.google.com/github/FatimaBOliveira/applied-statistics-assessment/blob/main/problems.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Dependencies

This project was developed and tested using Python 3.12.7, but it should work with other Python 3.x versions as well.

The requirements.txt file, found in the root of this repository, indicates all the packages needed in order to run the Python code. This file was generated through the command line with the code `pip freeze > requirements.txt`, as instructed by [Microsoft Docs](https://github.com/MicrosoftDocs/visualstudio-docs/blob/main/docs/python/managing-required-packages-with-requirements-txt.md). To run this project on any machine, clone this repository and download the packages through the terminal of VSC with `pip install -r requirements.txt`.

## Usage

To run this project, users need the programs listed above, and ensure that all dependencies are installed.

The code in the problems.ipynb notebook can be run through Visual Studio Code, or in the cloud with GitHub Codespaces or Google Colab. In GitHub Codespaces, ensure all dependencies are installed as well, as some of the packages are not pre-installed. please follow the instructions in the section above.

To avoid issues, the notebook should be run sequentially from top to bottom, as most of the codes depend on each other and need to follow this running order to successfully work.

## Get help

If there's any problem with this project, please submit [issues](https://github.com/FatimaBOliveira/applied-statistics-assessment/issues) in this repository.

## Author

**by Fatima Oliveira** 

Email: g00438857@atu.ie or Fatima.21.00@hotmail.com