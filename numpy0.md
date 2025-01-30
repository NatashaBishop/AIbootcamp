https://github.com/01-edu/public/tree/8b1e94b56245f406770ea20083e5e03b3a42984f/subjects/ai/numpy/
NumPy
Overview
The goal of this day is to understand practical usage of NumPy. NumPy is a commonly used Python data analysis package. By using NumPy, you can speed up your workflow, and interface with other packages in the Python ecosystem, like scikit-learn, that use NumPy under the hood. NumPy was originally developed in the mid 2000s, and arose from an even older package called Numeric. This longevity means that almost every data analysis or machine learning package for Python leverages NumPy in some way.

Role Play
You’re standing in the NumPy Training Room, a sleek, tech-filled lab where aspiring data scientists sharpen their skills. Here, you’re ready to get hands-on with Python’s powerful NumPy library, learning the basics of creating, slicing, and manipulating data arrays.

Learning Objectives
Master fundamental NumPy operations and techniques to efficiently manipulate, analyze, and extract insights from numerical data in Python.

Virtual Environment
Python 3.x
NumPy
Jupyter or JupyterLab
Version of NumPy we used to do the exercises: 1.18.1. We suggest using the most recent one.

Exercise 0: Environment and libraries
The goal of this exercise is to set up the Python work environment with the required libraries and to learn to launch a jupyter notebook. Jupyter notebooks are very convenient as they allow to write and test code within seconds. However, it really easy to implement instable and not reproducible code using notebooks. Keep the notebook and the underlying code clean. Notebook can be used for most of the exercises of the piscine as the goal is to experiment a lot. But no worries, you'll be asked to build a more robust structure for all the projects.

Note: For each quest, your first exercise will be to set up the virtual environment with the required libraries.

We suggest utilizing:

The latest stable version of Python for your work. However, in this exercise, you'll install and use a specific Python version for educational purposes.
Choose a virtual environment that aligns with your familiarity. Common choices among Data Science practitioners are virtualenv and conda.
Install the most recent versions of the required libraries to ensure compatibility and access to the latest features
Begin by creating a virtual environment named ex00 that utilizes Python version 3.8. Install the required libraries numpy and jupyter. Save the installed packages to a file named requirements.txt, located in the current directory.

Launch a jupyter notebook or JupyterLab on port 8891. Create a new notebook named Notebook_ex00.

In the first cell of the notebook, set H1 TITLE as a heading level 1 and H2 TITLE as a heading level 2.

Execute print("Buy the dip ?") in the second cell to display the message.

Resources :
python
Conda Documentation
jupyter
numpy
Jupyter Notebook Shortcuts
Why You Should be Using Jupyter Notebooks
========================================
Audit:  
Exercise 0: Environment and libraries
Install the virtual environment with requirements.txt
Activate the virtual environment. If you used conda, run conda activate ex00
Does the shell specify the name ex00 of the environment on the left?
Run python --version
Does it print Python 3.x? x >= 9
Does import jupyter and import numpy run without any error?
Have you used the following command jupyter notebook --port 8891?
Is there a file named Notebook_ex00.ipynb in the working directory?
Is the following markdown code executed in a markdown cell in the first cell?
# H1 TITLE
## H2 TITLE
Does the second cell contain print("Buy the dip ?") and return Buy the dip ? in the output section?
