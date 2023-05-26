# TITLE!
_Exam project for Computational Linguistics Spring 2023_

## Structure of the repository
__`in`:__ Here you will find the data (or input) used in the code.
- `balanced_dataset.csv`: The cleaned and balanced dataset (the output from running `preprocessing.ipynb`).


__`notebooks`:__ Here you will find the code
- `postnord_classification.ipynb`: finds the best model for classification and then trains and evalutates it.
- `preprocessing.ipynb`: get the data in shape for the classification task.
- `old`: a folder of previous editions of the code (_it's quite messy, so no need to look in there_)


__`out`:__ Here you will find the output from running the code (plots, reports etc.)
- PLOTS

## How to use the code
- Before running any of the code, please download the data from [this Kaggle-page](https://www.kaggle.com/datasets/nicklasstiborgm/reviews-of-postnords-trustpilot-page) and add it to the `in`-folder.
- Then go into the `notebooks`-folder, open the `preprocessing.ipynb`-notebook and run all the code chunks in the notebook. This should complete any necessary preprocessing of the data and save a cleaned and balanced dataset, which can be used for further analysis, in the `in`-folder.
    - _If you want to skip this step, you can already find the output from this notebook (`balanced_dataset.csv`) in the `in`-folder.
- Then open and run all the code in `postnord_classification.ipynb`, and you will get the different output seen in the exam paper.
    - _This might take a while!_


_Kirsten N. Nielsen & Agnes B. Nielsen_
