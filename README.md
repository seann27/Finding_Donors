# Finding_Donors
Finding Donors project from Udacity

# Project Overview
This project applies machine learning algorithms with US Census data to determine if
a person will donate to charity and what kind of features are most important when
making this determination.

# Software Requirements (Reference: Udacity)

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)

# Files

- census.csv -> The main census data source modeled after the 1994 U.S. Census
	- Taken from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income)
- find_donors.py -> The main method that cleans the data, trains it on an optimized model, and outputs
	the results
- Models.py -> Package that takes in cleaned data and runs it with a variety of supervised learning
	algorithms. Picks the high scoring algorithm and optimizes it by tuning hyperparameters with the
	sklearn GridSearch module. Writes text files with results and returns an optimal classifier.
- show_eval_graphs.py -> Compares performance of supervised learning algorithms from Models.py by
	graphing their results on the cleaned dataset.

# Usage

- python find_donors.py
