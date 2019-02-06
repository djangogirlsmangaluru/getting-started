![](images/dg-banner.png)

<h1 align="center">Getting Started</h1>
<p align="center">
<a href="https://djangogirls.org/mangaluru"><img src="https://img.shields.io/badge/DjangoGirls-Mangaluru-orange.svg?style=for-the-badge"/></a>
<a href="https://sosc.org.in" rel="nofollow"><img src="https://camo.githubusercontent.com/4ba098b6ff52af60dce4bd3cac70831c603df40f/68747470733a2f2f69732e67642f76697369745f736f73635f6261646765" alt="SOSC" data-canonical-src="https://is.gd/visit_sosc_badge" style="max-width:100%;"></a>
</p>

This repository contains setup instructions for all the resources required for the workshop. Please go through them carefully and install in your system. For any queries open an issue or contact a mentor.

# Python Installation on windows

## Downloading python

1. Go to (https://www.python.org/downloads/) to download the current version of python, that is python 3.7.2.
 
2. Click on <b>download python 3.7.2.</b>

3. A python 3.7.2.exe file will be downloaded.
   
## Installing python

1. Double click on the icon labeling the file <b>python 3.7.2.exe </b>. An <b> Open File - Security Warning </b> pop-up window will appear. Click on <b>run</b>.

2. A Python 3.7.2 (32-bit) Setup pop-up window will appear.

3. Ensure that the <b> Install launcher for all users (recommended)</b> and the<b> Add Python 3.7 to PATH checkboxes </b> at the bottom are checked. If the Python Installer finds an earlier version of Python installed on your computer, the Install Now message may instead appear as <b>Upgrade Now </b>.

5. Highlight the <b>Install Now (or Upgrade Now) message</b>, and then click it. A User Account Control pop-up window will appear, posing the question Do you want to allow the following program to make changes to this computer?

6. Click the <b>Yes button.</b> A new Python 3.7.2 (32-bit) Setup pop-up window will appear.

7. <b>Python 3.7.2 (32-bit) Setup pop-up window</b> will appear with a Setup was <b>successfuly message.</b>

Voila you now have python 3.7.2 installed!!


## Install a code editor
A code editor is a tool which will help you write code owing to it's many features. We recommend installing [VS Code](https://code.visualstudio.com/) or [Atom](https://atom.io/). 

## Setting up a virtual environment
A virtual environment lets us keep the libraries and packages that a certain project requires seperate from the local installation. In order to create a virtual environment, follow the instructions below:
(**Please note that ** `Name` ** here refers to the username of the person logged in to the system.**)

    C:\Users\Name> mkdir djangogirls
    C:\Users\Name> cd djangogirls

We will make a virtualenv called myvenv. The general command will be in the format:

    C:\Users\Name\djangogirls> python -m venv myvenv

Here, myenv is the name of your virtual environment.<br>
We can make use of the virtual environment by entering the following command:

    C:\Users\Name\djangogirls> myvenv\Scripts\activate

If you are succesful, the command line should look like this:

    (myenv) C:\Users\Name\djangogirls>
## Install django
With this step, we will install django in the virtual environment that was created. This lets us make use of django **only** when we activate this environment.
Now, in the command prompt, enter the following command:
    
    (myenv) C:\Users\Name\djangogirls> pip install django

To verify the installation, run the following command: **django-admin --version** in your command prompt.

## Install git

You can download Git from git-scm.com. You can hit "next" on all steps except for two: in the step where it asks to choose your editor, you should pick Nano, and in the step entitled "Adjusting your PATH environment", choose "Use Git and optional Unix tools from the Windows Command Prompt" (the bottom option). Other than that, the defaults are fine. Checkout Windows-style, commit Unix-style line endings is good.

Do not forget to restart the command prompt or powershell after the installation finished successfully. 

## Create a GitHub account

Go to GitHub.com and sign up for a new, free user account. Be sure to remember your password (add it to your password manager, if you use one).
