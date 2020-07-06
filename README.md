## Project: Finding Donors for CharityML

## Project Overview
In this project, we will apply supervised learning techniques and an analytical mind on data collected for the U.S. census to help CharityML (a fictitious charity organization) identify people most likely to donate to their cause. We will first explore the data to learn how the census data is recorded. Next, we will apply a series of transformations and preprocessing techniques to manipulate the data into a workable format. We will then evaluate several supervised learners on the data, and consider which is best suited for the solution. Afterwards, we will optimize the selected model and present it as our solution to CharityML. Finally, we will explore the chosen model and its predictions under the hood, to see just how well it's performing when considering the data it's given.


## Software Requirements

This project uses the following software and Python libraries:

- [Python 3.7](https://www.python.org/downloads/release/python-370/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Altair](https://altair-viz.github.io/index.html)

We will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

## Project Files

- `finding_donors.ipynb`: This is the main file where we will be performing your work on the project.
- `census.csv`: The project dataset. We'll load this data in the notebook

## Results

**Inital model evaluation:** Random Forest performs better compared to other Decision Tree and GaussianNB.

[inital_accuracy_comparison](screen_shots/initial_accuracy.png)

[inital_f_score_comparison](screen_shots/initial_f_score.png)

**Performannce of optimized Random Forest model**
- Accuracy: 0.8586
- F-Score: 0.7291

**Feature Weights**

[feature_weight](screen_shots/feature_weight.png)

## Acknowledgements

- [Udacity](https://www.udacity.com/)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income)

## Author
[Shahzeb Akhtar](https://www.linkedin.com/in/shahzebakhtar/)
