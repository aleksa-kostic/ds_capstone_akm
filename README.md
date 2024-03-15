# ds_capstone_akm
Masters of Data Science Online Capstone 2024

Contributors: 
- Aleksa Kostic
- Marlene Arredondo
- Kevin Pham

Contents:
- `data/`
    - `processed/`
        - Data files after performing data preprocessing
    - `raw/`
        - There are no raw data files pulled directly from anywhere as data is pulled through Python from the UCI Machine Learning repository. 
- `notebooks/`
    - `data_processing/`
        - Notebooks for preprocessing the data pulled from the UCI Machine Learning repository. Output files are under `data/processed/`.
    - `models/`
        - Notebooks for building the models and getting our results.
        - `Results/`
            - All outputs and notes as a result of model building

Running the code: Please note that the notebooks were built under a different folder structure. If you'd like to run the code using our dataset, please change the data sources within the files to `data\processed\cleaned_augmented_2.csv`, `data\processed\CDCDiabetesHealthIndicators.csv`, or `data\processed\diabetes130Hospitals10Years.csv` as necessary.

Data processing (in specific order): 
1. notebooks/data_processing/Capstone_Aleksa_Dataset_1_Rework.ipynb
2. notebooks/data_processing/Capstone_Aleksa_Dataset_3.ipynb
3. notebooks/data_processing/Capstone_Aleksa_Merging.ipynb
4. notebooks/models/Cleanup and PCA.ipynb
5. notebooks/models/Cleanup Part 2 and PCA.ipynb

Model building (in no particular order):
- notebooks/models/Aleksa_Capstone_Neural_Nets_Without_PCA.ipynb
- notebooks/models/Aleksa_Capstone_Neural_Nets_With_PCA.ipynb
- notebooks/models/Decision Trees.ipynb
- notebooks/models/Decision Trees_PCA.ipynb
- notebooks/models/KNN.ipynb
- notebooks/models/KNN_PCA.ipynb
- notebooks/models/Logistic Regression.ipynb
- notebooks/models/Logistic Regression_PCA.ipynb
- notebooks/models/NaiveBayes.ipynb
- notebooks/models/PCA_NaiveBayes.ipynb
- notebooks/models/Random Forest.ipynb
- notebooks/models/Random Forest_PCA.ipynb
- notebooks/models/SVM.ipynb
