# Project 愛

## This is a ML project designed to analyze and recognize occuring trends in the stock market and indicate whether to buy.

## The folders you will find in this project directory are as follows:

### data/raw: Store raw, unprocessed data files here. This keeps the original data intact for reference and reproducibility.

### data/processed: Save cleaned and preprocessed data that is ready for training and evaluation. This separation ensures that raw data remains untouched.

### data/external: Use this directory for any external data sources that complement the primary dataset.

### notebooks: Jupyter notebooks are ideal for data exploration, visualization, and initial model prototyping. Keeping them separate from scripts helps maintain a clean structure

### scripts: Modular scripts for different stages of the pipeline ensure reusability and clarity:

### /preprocess.py: Handles data cleaning, feature engineering, and any transformations required before training.

### /train.py: Contains the code for training the machine learning model. This can include model selection, hyperparameter tuning, and saving the trained model.

### /evaluate.py: Focuses on evaluating the performance of the trained model using appropriate metrics and validation techniques.

### models: Save trained model artifacts here for easy access during deployment or further analysis.

### requirements.txt: List all the Python dependencies needed for the project. This ensures that the project environment can be replicated easily.

### README: Provide an overview of the project, instructions for setting up the environment, and guidelines for running the scripts.
