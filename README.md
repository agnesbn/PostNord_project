# TITLE!
**Kirsten N. Nielsen & Agnes B. Nielsen**

## Structure of the repository
<img src="https://img.icons8.com/?size=512&id=JHFYPQIPcXti&format=png"  width="25" height="25"> __`in`: Here you will find the data (or input) used in the code.__\
\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=63488&format=png"  width="25" height="25">`balanced_dataset.csv`\
\
<img src="https://img.icons8.com/?size=512&id=JHFYPQIPcXti&format=png"  width="25" height="25"> __`notebooks`: Here you will find the code.__\
\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=JHFYPQIPcXti&format=png"  width="25" height="25"> `old` (_it's quite messy, so no need to look in there_)\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=J0SgMWzAxqFj&format=png"  width="25" height="25">`postnord_classification.ipynb`\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=J0SgMWzAxqFj&format=png"  width="25" height="25">`preprocessing.ipynb`\
\
<img src="https://img.icons8.com/?size=512&id=JHFYPQIPcXti&format=png"  width="25" height="25"> __`out`: Here you will find the output from running the code (plots, reports etc.).__\
\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=102179&format=png"  width="25" height="25"> `classification_report.txt`\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.icons8.com/?size=512&id=112856&format=png"  width="25" height="25"> `confusion_matrix.png`\
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
