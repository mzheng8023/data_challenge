## Download and unzip file. CD to Project Directory.
## Download Transactions Data to Project Directory
`Link to data found here: https://github.com/CapitalOneRecruiting/DS`

## Create a virtual enviroment (OPTIONAL)
## For Mac:
`$ python3 -m venv venv`
`$. venv/bin/activate`

## For Windows
`> py -3 -m venv venv`
`> venv\Scripts\activate`

## Setup the Environment
`$ pip3 install -r requirements.txt`

## Install Jupyter Notebook OR Convert .ipynb to .py
## Install Jupyter Notebook
`pip3 install notebook`

## Install and run ipynb-py-convert
`pip install ipynb-py-convert`
`ipynb-py-convert file.ipynb file.py`

## Important Files and Scripts (Jupyter Notebook)
[Report.docx]
- Contains all findings, graphs, and responses to the Data Science Challege. 

[load.ipynb]
- Load transactions.txt data file to dataframe. Look at structure of data, remove null columns, and pickle cleaned data to file for later use.

[exploratory_analysis.ipynb]
- Using cleaned data, generate visualizations for a deeper look at the data structure and correlations.

[duplicate_transactions.ipynb]
- Using cleaned data, identify duplicate transactions including multi-swipe and reverse transactions.  

[preprocessing.ipynb]
- Preprocess cleaned data to prepare for model training. Resample data due to imbalanced dataset. Create pipeline to transform categorical columns. Pickle preprocessed data to file for model training.

[models.ipynb]
- Using preprocessed data, prepare baseline models, set parameters, and retrain models. Pickle trained model to file for model performance analysis.

[model_performance.ipynb]
- Load trained models, test model performance, generate confusion matrix and ROC curve for all models. 

## Instructions on Model Training
- Make sure data (transactions.txt) is in the DSC_C1308917 directory, or change path variable in load.ipynb to the location of data.
- Run load.ipynb
- Run preprocessing.ipynb
- Run models.ipynb
- Run model_performance.ipynb 

## Instructions on Checking Duplicate Transactions
- Make sure data (transactions.txt) is in the DSC_C1308917 directory, or change path variable in load.ipynb to the location of data.
- Run load.ipynb
- Run duplicate_transactions.ipynb

## Instructions on Exploratory Analysis
- Make sure data (transactions.txt) is in the DSC_C1308917 directory, or change path variable in load.ipynb to the location of data.
- Run load.ipynb
- Run exploratory_analysis.ipynb
