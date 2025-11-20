# Predicting High Income Using US Census Data 💰

## Overview 

This project aims to build a machine-learning model to predict whether an individual earns more than $50k per year using the US Census Income dataset.
The goals of the project are:
	•	Explore and understand the socioeconomic factors associated with income level
	•	Build a reproducible ML pipeline (EDA → Feature Engineering → Modeling → Evaluation)
	•	Select a final model that balances recall, F1-score, and PR-AUC given the dataset’s class imbalance
	•	Provide interpretable insights and a business-ready presentation


## GitHub Organisation 📁

```
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_FE_Model_Evaluation.ipynb
│   └── 03_Future_Work_and_Limitations.ipynb
│
├── models_saved/
│   └── best_xgboost_model.pkl
│   # (Random Forest models not included due to large file size)
│
├── csv_preparation/
│   ├── Census_Income_Test.csv 
│   # Census_Income_Data.csv and df_post_eda.pkl not included (exceed GitHub size limit)
│
├── References.md -> Contains all external references, research papers, and resources cited in this project.
│
└── Presentation.pdf ->  Final project presentation summarizing:
``` 


## Installation

Here are the steps to follow to correctly install the package.

1. If using conda:
    - Create a new conda environment with Python 3.12  -> conda create -n Dataiku python=3.12
    - Activate it -> conda activate Dataiku

    If not using conda:
    - Create a new python environment -> python -m venv Dataiku
    - Activate it -> for MacOs/Linux : source Dataiku/bin/activate for Windows: mcsim\Scripts\activate

2. Clone the repository -> git clone url_github_repository
3. Go to the direcotry -> cd repo_name
4. install the package -> pip install -r requirements.txt or pip install .