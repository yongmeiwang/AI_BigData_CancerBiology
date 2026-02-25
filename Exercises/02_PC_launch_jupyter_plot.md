## 🪟 Windows Users

### Step 1 — Install Python

Download Python from:

https://www.python.org/downloads/

During installation:

☑ **IMPORTANT:** Check the box  
“Add Python to PATH”

Then click Install.

---
It is best to install a stable version of python as to not run into compatibility problems with your desired
packages. NOTE: newer isn’t always better! My suggestion is to install Python
3.9.12 - March 23, 2022 using the Windows installer (64-bit). During the
installation prompting for installing your python version it is very important
that you select to add Python ___ to PATH. Besides that, the express installation
options should be fine.
Note: if your system is very old it could be 32-bit. You can check if your system is
64bit or 32bit by opening file explorer and navigating to “This PC” tab on the left
side of the file explorer. In “This PC” you’ll see a OS (C:) listed, you’ll need to right
click on a blank portion of the explorer (Not on the OS (C:) itself) and click the
properties option. You will see your System > About page, under System type will
be whether your system is 64bit or 32bit. (E.g. System type: 64-bit operating
system, x64-based processor)



### Step 2 — Open Command Prompt

Press:

Windows Key → type:

cmd

Open **Command Prompt**.

---

### Step 3 — Verify Python Installation

Type:

python --version

If you see a version number (e.g., Python 3.11.x), installation was successful.

---

### Step 4 — Install Jupyter Notebook

In Command Prompt, type:

pip install notebook

Wait for installation to complete.

---

### Step 5 — Create Course Folder

Inside Command Prompt, type:

mkdir AI_Cancer_Course
cd AI_Cancer_Course

---

### Step 6 — Launch Jupyter Notebook

Type:

jupyter notebook

Your web browser should open automatically.

If it does not open automatically, copy the URL shown in the terminal and paste it into your browser.
