This Project contains code written and developed by me using references to Kernels on the Kaggle competition website for guidance. I have included links to these references at the end of this document.

This README file will provide you with any help related to running my code and reproducing the results.

This submission contains the following files:
1. proposal.pdf ==> The Capstone Proposal that was submitted in the previous section.
2. report.pdf ==> The final Capstone Report as per the template provided.
3. udacity_capstone.ipynb ==> executable code documented in a Jupyter Notebook
4. udacity_capstone.html ==> executable code in html format
5. train.csv ==> training dataset from Kaggle competition page in csv format
6. test.csv ==> test dataset from Kaggle competition page in csv format
7. sample_submission.csv ==> Sample submission format from Kaggle competition page
8. models.pckl ==> pickle file containing final tuned models.
9. README.txt ==> ReadMe file with instructions for setting up and running this code as well information about material used in this project.

The following software has been used:
1. Python 2.7.13 (Anaconda Build)
2. Windows 10 OS
3. Jupyter Notebook

Some of the major libraries used have been discussed below:
1.  pandas ==> To manipulate dataframes during feature enigneering and preprocessing.
2.  sklearn ==> For model implementations, validation, tuning, metrics.
3.  os ==> To get and set working directories.
4.  time ==> To print put time stamps while documenting results.
5.  pickle ==> To save pickle files of models in order to load them instead of retraining them which is time consuming.
6.  matplotlib.pyplot ==> To create visuals of results and the data.
7.  seaborn ==> To create visuals of results and the data.
8.  numpy ==> To perform mathematical and scientific operations.
9.  scipy ==> To perform mathematical and scientific operations.
10. xgboost ==> To implement Gradient Boosting models.
11. random ==> To set random seed states to ensure reproducibility of results.
12. warnings ==> To silence warnings produced while running code cells.
13. Ipython.display ==> To display jpeg images of visuals/graphs/plots.

Setup/Startup:
STEP 1:
All of my code is contained in the udacity_capstone.ipynb Jupyter Notebook.
You will be required to ensure the following packages/classes are installed in your Python Environment prior to running the notebook. The list below shows every package/class that I have used in the course of this capstone project:
1.  pandas
2.  os
3.  time
4.  pickle
5.  matplotlib.pyplot
6.  seaborn
7.  numpy
8.  scipy.stats
9.  sklearn.preprocessing
10. sklearn.metrics
11. sklearn.model_selection
12. sklearn.linear_model
13. sklearn.ensemble
14. sklearn.grid_search
15. sklearn.cross_validation
16. xgboost
17. random
18. datetime
19. warnings
20. IPython.display

NOTE: the xgboost package proved troublesome to install. I used the following link as guidance to build and compile the xgboost module in my virtual environment.
LINK - https://www.ibm.com/developerworks/community/blogs/jfp/entry/Installing_XGBoost_For_Anaconda_on_Windows?lang=en


Once these packages have been installed in your environment proceed to Step 2.

STEP 2:
Next set your working directory to the folder containing the train.csv and test.csv files made available in the capstone.zip folder that has been submitted. This will ensure that the code can read in the data files as well as write content like images, pickle files etc. to the same directory.

STEP 3:
Start running the code, one cell at a time, if your machine's hardware is limited, in order to prevent memory failure or a system crash. The initial cells contain lightweight code that will run relatively fast, but once you reach the cells that begin training the models, the execution time may increase drastically depending upon your machine's hardware. For convenience, I have included a pickle file with all of the final models obtained after training so you can skip the model training cells and proceed directly to this cell [#104] to view the models and run the subsequent code to visualize the results.

LINKS TO KERNELS USED FOR REFERENCE:
1. https://www.kaggle.com/serigne/stacked-regressions-top-4-on-leaderboard
2. https://www.kaggle.com/humananalog/xgboost-lasso
3. https://www.kaggle.com/dfitzgerald3/randomforestregressor
4. https://www.kaggle.com/eliotbarr/stacking-starter
5. https://www.kaggle.com/yassineghouzam/eda-introduction-to-ensemble-regression
6. https://www.kaggle.com/dansbecker/learning-to-use-xgboost
7. https://www.kaggle.com/humananalog/xgboost-lasso/code
8. https://www.kaggle.com/zyedpls/regularized-linear-models

LINK TO MY KAGGLE PROFILE CREATED FOR THIS CAPSTONE PROJECT:
1. https://www.kaggle.com/udapaulleon