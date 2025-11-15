# PersonalityPrediction
---

This is a project from STAT 705 - Regression and Analysis of Variance. It involved extracting and cleaning of publicly available personality data from a psychology study and performing at first a linear regression and later a ridge regression for predicting the personality of a student. The aim of the project was to exercise the utility of a linear regression on a non-linear dataset, and determine other models that would be better suited for prediction, such as the ridge regression.

Dataset: https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data/data

# Setup
1. Create virtual environment:
    - `python3 -m venv .venv' in root project directory.
2. Activate virtual environment:
    - `source .venv/bin/activate` if using UNIX/LINUX.
    - `./.venv/Scripts/activate` if using Windows.
3. Install packages:
    - `pip3 install -r requirements.txt`
4. Start in `ExploratoryAnalysis.ipynb` and set kernel to `.venv`, and execute all cells.
5. Move to `Preprocessing.ipynb` and execute all cells.
6. Move to `LinearRegressionAnalysis.ipynb` and execute all cells.

**NOTE**:
`scikit-learn 1.15.3` must be installed to use statsmodels library.
