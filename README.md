# TITLE!
_Exam project for Computational Linguistics Spring 2023_\
_Kirsten N. Nielsen & Agnes B. Nielsen_

## Structure of the repository
<img src="https://img.icons8.com/?size=512&id=JHFYPQIPcXti&format=png"  width="25" height="25"> __`in`:__ Here you will find the data (or input) used in the code.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=63488&format=png"  width="25" height="25">`balanced_dataset.csv`: The cleaned and balanced dataset (the output from running `preprocessing.ipynb`).\
\
<img src="https://img.icons8.com/?size=512&id=JHFYPQIPcXti&format=png"  width="25" height="25"> __`notebooks`:__ Here you will find the code.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=J0SgMWzAxqFj&format=png"  width="25" height="25">`postnord_classification.ipynb`: finds the best model for classification and then trains and evalutates it.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=J0SgMWzAxqFj&format=png"  width="25" height="25">`preprocessing.ipynb`: get the data in shape for the classification task.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=JHFYPQIPcXti&format=png"  width="25" height="25">`old`: a folder of previous editions of the code (_it's quite messy, so no need to look in there_)\
\
<img src="https://img.icons8.com/?size=512&id=JHFYPQIPcXti&format=png"  width="25" height="25"> __`out`:__ Here you will find the output from running the code (plots, reports etc.)\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=102179&format=png"  width="25" height="25"> `classification_report.txt`\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=102179&format=png"  width="25" height="25"> `correlated_terms.txt`\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=102179&format=png"  width="25" height="25"> `development_in_number_of_rows.txt`\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=112856&format=png"  width="25" height="25"> `distribution_of_datapoints_AFTER_preprosessing.png`\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=112856&format=png"  width="25" height="25"> `distribution_of_datapoints_BEFORE_preprosessing.png`\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=112856&format=png"  width="25" height="25"> `mean_length_pr_category.png`\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=112856&format=png"  width="25" height="25"> `model_accuracies.png`
## How to use the code
- Before running any of the code, please download the data from [this Kaggle-page](https://www.kaggle.com/datasets/nicklasstiborgm/reviews-of-postnords-trustpilot-page) and add it to the `in`-folder.
- Then go into the `notebooks`-folder, open the `preprocessing.ipynb`-notebook and run all the code chunks in the notebook. This should complete any necessary preprocessing of the data and save a cleaned and balanced dataset, which can be used for further analysis, in the `in`-folder.
    - _If you want to skip this step, you can already find the output from this notebook (`balanced_dataset.csv`) in the `in`-folder.
- Then open and run all the code in `postnord_classification.ipynb`, and you will get the different output seen in the exam paper.
    - _This might take a while!_
