

****
## Features
1. Drap and drop file from local system for training.

2. Simple Data Exploration.

3. Many Preprocessing methods:
     * Sample and Split
     * Data Preprocessing (Missing Values Imputation, One Hot Encoding, Handle Unknown Levels, Fix Imbalance for Classification)
     * Scale and Transform (Normalization, Transformation, Target Transformation)
     * Feature Engineering (Feature Interaction, Polynomial Features, Trigonometry Features, Group Features, Bin Numeric Features, Combine Rare Levels)
     * Feature Selection (Feature Importance, Remove Multicollinearity, Principal Components Analysis, Ignore Variances)
     * Unsupervised (Create Clusters, Remove Outliers)

4. Model Training:
   * Compare all available Machine Learning Algorithm automatically.
   * Train a selected single model
   * Train an ensemble model
   * Hyperparameter tuning for single model

5. Model Result Visualization:
   * All plots for Regression and Classification
   * SHAP Value

6. Prediction and Save Model:

   * Online Prediction  
   * Batch Prediction  
   * Save whole Machine Learning Pipeline as pickle file

****
## Install and Run
Drap and drop file from local system for training.

Simple Data Exploration.

Many Preprocessing methods:

Sample and Split
Data Preprocessing (Missing Values Imputation, One Hot Encoding, Handle Unknown Levels, Fix Imbalance for Classification)
Scale and Transform (Normalization, Transformation, Target Transformation)
Feature Engineering (Feature Interaction, Polynomial Features, Trigonometry Features, Group Features, Bin Numeric Features, Combine Rare Levels)
Feature Selection (Feature Importance, Remove Multicollinearity, Principal Components Analysis, Ignore Variances)
Unsupervised (Create Clusters, Remove Outliers)
Model Training:

Compare all available Machine Learning Algorithm automatically.
Train a selected single model
Train an ensemble model
Hyperparameter tuning for single model
Model Result Visualization:

All plots for Regression and Classification
SHAP Value
Prediction and Save Model:

Online Prediction
Batch Prediction
Save whole Machine Learning Pipeline as pickle file
Install and Run
Clone the repository to you computer:

git clone https://github.com/jrderek/private.git
cd private
Creata a conda virtual or python virtual environment and then activate it.
conda create -n myvirtual-name python=3.8 -y
conda activate myvirtual-name
Install requirements
pip install -r requirements.txt
Run streamlit locally and start web service:
streamlit run app.py
Run on Docker
Pull the Docker image:
docker pull jrdegbe/privately/github-action:0.1.0


2. Run the  Docker image locally:
docker run -p 8501:8501 privately/github-action

3. Open the localhost:8501

  * [http://localhost:8501](http://localhost:8501)
