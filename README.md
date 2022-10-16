# Cohort-Analysis
Cohort Analysis Sample

Sarath Kareti - Cohort Analysis


1. Files
	a. orders.csv - table for orders
	b. customers.csv - table for customers
	c. df_final.csv - output as a result of code execution
	d. Sarath Kareti Cohort Analysis.ipynb - Jupyter notebook used to execute code and analysis
	e. Sarath Kareti Cohort Analysis - Jupyter Notebook.pdf - PDF of Jupyter Notebook including output
2. Dependencies
	a. Jupyter Notebook or Jupyter Lab
		i. Jupyter Notebook installation: (run in command line) pip install notebook
		ii. Jupyter Lab installation: (run in command line) pip install jupyterlab
	b. Python (3.7.x or greater)
		i. Download from https://www.python.org/downloads/ depending on your OS (Mac, Windows, Linux)
	c. Pandas 1.2.4
		i. !pip3 install pandas (provided in notebook)
	d. Plotly 5.7.0
		i. !pip3 install plotly (provided in notebook)
	c. Numpy 1.20.1
		i. !pip3 install numpy (provided in notebook)
	d. Datetime
		i. Built-in to python, otherwise !pip3 install date time
3. Execution
	a. The code is split up into two parts. The first part is the step-by-step version where each step is explained. The second part is the Class where the code is compiled and can be run when the .analysis() function is called. The user can run the first, second, or both parts depending on their preference. Both can run independently of each other.
	b. When the class function is called, the user is prompted to enter the path to their customers.csv and orders.csv. The user must enter the path without any quotes or else the program will repeatedly ask for the path until it finds a valid location (i.e.: path/to/file/file.csv and not ‘path/to/file/file.csv’)
	c. After the Class code, please execute cell 59 as well. It includes the global variable ‘fig’ which is a heat map and is necessary to understand the analysis below it.


Thank You,
Sarath Kareti
