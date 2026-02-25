# Hands-On Activity 02  
## Introduction to Linux and Launching Jupyter Notebook

In this activity, you will:

- Learn basic terminal nagivation 
- Understand file system structure
- Install and Launch Jupyter from the command line
- Create your first scientific plot


This is your first computational setup exercise.

---
# Part 0 -Watch the Video to open your terminal on Mac (PC users: skip this)

Watch:

https://www.youtube.com/watch?v=d4COz-7qKQg

While watching, focus on:

- What is the terminal?
- What is a working directory?

Following this tutorial to learn more about Linux Commands 
https://people.ischool.berkeley.edu/~kevin/unix-tutorial/toc.html

Complete:

- Section 1
- Section 3
- Section 4

Skip:

- Section 2

Focus only on these commands:

pwd  
ls  
cd  
mkdir  
rm  

Do not worry about advanced topics.


---
# Part 1 — Installation and Setup

## Operating System Instructions

This activity includes separate instructions for Mac and Windows users.

- 🍎 **Mac users**: Follow the instructions below in this file.
- 🪟 **Windows users**: Please open and follow:

  `02_PC_launch_jupyter_md_plot.md`([Windows Users: Click here for PC Instructions](02_PC_launch_jupyter_md_plot.md))

Make sure you follow the instructions corresponding to your operating system.

Open Terminal (Mac) or Command Prompt / PowerShell (Windows).

Type:

python3 -version 

If Python is installed, you should see a version number (e.g., Python 3.10.x).

If not, download Python from:
https://www.python.org/downloads/

---


## Step 2 — Install Jupyter

In the terminal, type:

pip3 install notebook 

(If `pip3` does not work, try `pip install notebook`.)

Wait until installation completes.

---

# Part 2 — Basic Terminal Navigation

Before launching Jupyter, let’s understand where we are in the system.

### Check Current Location

pwd

(pwd = print working directory)

---

### List Files in Current Folder

ls 

you can also use the command ls in this format

ls -alh 

The second part offers different output from the command ls. 

---

### Create a New Folder for This Course

mkdir AI_Cancer_Course

cd AI_Cancer_Course

Now you are inside your project folder.

---

# Part 3 — Launch Jupyter

Inside your project folder, type:

jupyter notebook

Your browser should open automatically.

If not, copy the URL shown in the terminal and paste it into your browser.

---

# Part 4 — Create Your First Notebook

1. Click **New → Python 3**
2. Rename the notebook:

matplot_lib_functions.ipynb

An example of the jupyter notebook to be created can be found in Examples directory, 02_matplot_lib_functions.html 
You can follow the cells in that html and try to run them. 

when you see "import numpy as np", and if you failed to run, that most likely you did not install the packages numpy

on your terminal, type

pip3 install numpy 

---

# 🧠 Notes About PC Users

Windows users may:

- Use Command Prompt
- Use PowerShell
- Or install Anaconda (simpler option)




