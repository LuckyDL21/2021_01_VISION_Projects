This README.txt file was generated on 20210617 by Jihwan Lee

#
# General instructions for completing README:
# For sections that are non-applicable, mark as N/A (do not delete any sections).
# Please leave all commented sections in README (do not delete any text).
#

-------------------
GENERAL INFORMATION
-------------------

1. Title of Dataset:

# Dataset: Plant-pathology-2021-fgvc8
# Download URL: https://www.kaggle.com/c/plant-pathology-2021-fgvc8/data
# You can download data from this link.

---------------------
FILE OVERVIEW
---------------------

Directory of Files:
   A. Filename: preprocess.ipynb        
      Short description: This code progresses removing duplicates, one-hot encoding,
                             making stratified folds, data pre-augmentation, making TF-Records files.        
        
   B. Filename: train.ipynb        
      Short description: This code progresses Data Augmentation, k-fold cross validation.
                             
        
   C. Filename: evaluation.ipynb      
      Short description: This code progresses prediction and creates submission.csv files.


--------------------------
CODE EXECUTION ORDER
--------------------------

1. Download Dataset from the Kaggle site. --> 2. Execute preprocess.ipynb --> 3. Execute train.ipynb --> 4. Execute evaluation.ipynb

--------------------------
* MENTION PRECAUTION *
--------------------------

# You have to change the dataset path in the code.
# I recommend training the model in the TPU environments.
