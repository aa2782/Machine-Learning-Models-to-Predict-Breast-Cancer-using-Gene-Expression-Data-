# Machine-Learning-Models-to-Predict-Breast-Cancer-using-Gene-Expression-Data-

Introduction:

Breast cancer occurs when the cells in the mammary gland grow and multiply in an uncontrollable way. It is most prevalent in women, although there are cases with men having breast cancer as well.

Research has revealed different types of breast cancer cells based on the factors involved in the growth of the tumor. The four primary molecular subtypes are determined by the presence or absence of proteins. They are Luminal A, Luminal B, HER2, and basal like. Since each type of breast cancer cell type behaves differently, classifying a breast cell to a molecular type is crucial. Classification allows for more targeted breast cancer treatment because each different molecular subtype has a different treatment option. Each treatment has a different response from the cancer cells, leading to a different clinical outcome.

The goal of this project is to build a machine learning model that will classify a given specimen into one of the four subtypes. It is important to determine, which genes have the most impact in this classification given the data. Subsequently, this gene or a set of genes can be used as a predictor for breast cancer.

This particular Breast Cancer dataset has 151 different measurements with 54,677 features in total. Some features for each measurement include, sample ID, type of breast cancer (Basal, HER, luminal_B, luminal_Aplus, cell_line, or normal tissue), and quantified values for different types of genes. The ‘sample ID’ feature specifies the  sample number that was examined. The ‘type’ feature specifies the type of breast cancer that the sample is. The rest of the features each correspond to a single gene, and the values present in the columns indicate the gene expression of each gene in the given sample. 

For this model, we are only focused on classifying samples into breast cancer types. Therefore, the ‘Normal’ and the ‘Cell Line’ samples were dropped from the dataset. They will not be used to train the model.

As such, we used the following models to analyze the data: logistic regression, K-neighbor classifier, Random forest classifier, and support vector classifier.

We also used PCA and GridSearchCV to see the performance changes in the models.

Finally we also used the Sequential Deep Learning model. 

Data source: https://www.kaggle.com/dataset/134765b899e1df132438692cdd193baa3142bbbd849d5129c4537f56e04671df
