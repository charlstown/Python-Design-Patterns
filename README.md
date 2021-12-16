# Python Patterns

[TOC]

## 0. Python patterns

I wanted to share my Jupyter notebook with some notes from the **Jungwoo Ryoo** Python Design Patterns course. Dr. Jungwoo Ryoo educates people in the field of Software Security/cybersecurity, Computer networking, Data Science and others.

## 1. Installing Jupyter Notebook

### Installation in Windows with Anaconda

Anaconda is an open-source software that contains Jupyter, spyder, etc that are used for large data processing, data analytics, heavy scientific computing. Anaconda works for R and Python programming language. Spyder(sub-application of Anaconda) is used for python. Opencv for python will work in spyder. Package versions are managed by the package management system called conda.

Head over to [anaconda.com](https://www.anaconda.com/distribution/#windows) and install the latest version of Anaconda. Make sure to download the “Python 3.7 Version” for the appropriate architecture.



### Installation in Linux

#### Step 1 Update and Upgrade Packages

First, we always start our installations before we ensure our system is updated. Run the following command to update the APT list of available packages and their versions. Moreover, use the upgrade command to actually install newer versions of the packages.

```
$ sudo apt update && sudo apt -y upgrade
```



#### Step 2 Install Python

Next you have to install Python 3, pip, and other required packages to build Python dependencies.

```
$ sudo apt install python3-pip python3-dev
```



#### Step 3 Install Jupyter Notebook

Write down the following command in your terminal to install Jupyter using `pip`.

```bash
pip install jupyter
```



## 2. Opening the notebook

### In Windows with anaconda

Open Anaconda Prompt console, and navigate to the path where you downloaded the Jupyter Notebook.

```
$ (base) C:\> cd "PathToTheJupyterNotebookFile"
```

Type & run the command *jupyter notebook* to open Jupyter Notebook

```
$ (base) C:\Path\To\The\Jupyter\Notebook\File> jupyter notebook
```



### In Linux

Open Linux terminal **ctrl + t** and navigate to the path where you downloaded the Jupyter Notebook.

```
$ C:\> cd "PathToTheJupyterNotebookFile"
```

Type & run the command *jupyter notebook* to open Jupyter Notebook

```
$ (base) C:\Path\To\The\Jupyter\Notebook\File> jupyter notebook
```



## 3. Help Wanted

This repository does provide the required files to open the notebook, you should run it by your own.

## 4. Other links

To find more projects, resources, articles and more you can visit my site http://carlosgrande.me/