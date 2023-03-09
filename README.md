# Teamsight Project, Attrition Prediction

## Introduction
This github is the programming related storing repository of a Final Thesis' Master. This thesis has been possible thanks to the agreement between the company *BIMEXAnalytics* and *Universtitat de Barcelona* to enable the student **Adrián Chacón Candia**. The final master project pretends to study and predict attrition values of companies and later model a solution of the problem. Attrition is weather a group of people or someone in particular decides to leave the company he's been working.

## To Start Coding

Firsts things to do:

1. Clone the repository
https://github.com/Bimex-es/Attrition.git

2. Then create your own notebook.  

3. Upload your notebook and sync it frequently from your local folder (from your terminal):
  
  git stash #leave your changes aside
  
  git pull #pull current version in website
  
  git stash pop #combine your changes
  
  git add .
  
  git commit -m "Comment here your updates"
  
  git push
  
4. Before coming back to work locally: 
  git pull

-------
Files Description
-------

  - ### Coding 
    - **Machine_Learning_Python_TFM.ipynb:** Here we study the Machine Learning part of the project. We strive to do a Machine Learning device to predict the attrition probability of a subject or a group.
    - **Probability_and_main_Python_TFM.ipynb:** Here we study the Probability part of the project. We strive to implement probability knowledge to relate it to attrition rates.
    - **TFM_first_dataframe_found.ipynb:** This code consists on the replication and improvement on a code found in Kaggle with the link [https://www.kaggle.com/code/vincentlugat/ibm-attrition-analysis-and-prediction#3.-Feature-engineering-and-selection].
    - **TFM_segundo_DataFrame_GitHub(NO_USE).ipynb:** This code consists on the replication and improvement of a code relatied to attrition rates found in a public GitHub repository named *employee-attrition-aif360*.
    - **WA_Fn-UseC_-HR-Employee-Attrition.csv:** DataFrame implemented in all the codes above. It consists on a category based description of 1470 people regarding personal and labour related aspects with the characteristic of having an Attrition column.

  - ### Figures
    - **Correlation_over10.png:** plot of the correlation of the different variables with respect to attrition.
    - **1_QinDfRawRskupf4mU5bYSA.png:** image that depicts the use of Principal Components Analysis.
    - **(Text)_freq_of_attrition.png:** The frequency of attrition for each category of each variable in the data_n DataFrame from the *Probability_and_main_Python_TFM.ipynb* code.
    - **Captura de pantalla 2023-03-02 a las 11.09.19.png:** Image that depicts a plot of two histograms and two evolutions with curves.
    - **CorrelationMatrix.png:** plot of the correlation matrix obtained from the data_n DataFrame of the *Probability_and_main_Python_TFM.ipynb* code.
    - **EnvSat_JobSat.png:** plot that compares the distribution of attrition frequencies between Environment Satisfaction and Job Satisfaction.
    - **JobLev_StockOptLv.png:** plot that compares the distribution of attrition frequencies between Job Level and Stock Option Level.
    - **TotWorkYears_YearsAtComp.png:** plot that compares the distribution of attrition frequencies between Total Working Years and Years At Company.
    - **TotWorkYears_YearsAtComp.png:** plot that compares the distribution of attrition frequencies between Years in Current Role and Years With Current Manager.
    - **FirstConfMatrix.png:** plot of the confusion matrix obtained from the first random forest machine learning study from the *Machine_Learning_Python_TFM.ipynb* code.
    - **SecondConfMatrix.png:** plot of the confusion matrix obtained from the second random forest machine learning study (some data curation has been done) from the *Machine_Learning_Python_TFM.ipynb* code.
    - **Learning_Curve_PCA.png:** plot that shows the learning curve from the different eigenvalues of the PCA method from the *Probability_and_main_Python_TFM.ipynb* code.
    - **dendrogram.png:** depiction of what a typical dendrogram looks like.
    - **random-forest-diagram.svg:** depiction of what a typical random forest looks like.
    - **CorrConfMatrix.png:** plot of the confusion matrix obtained from the forest machine learning study (with some data curation) of the correlation DataFrame (`df_ML_corr`) from the *Probability_and_main_Python_TFM.ipynb* code.
    - **PCAConfMatrix.png:** plot of the confusion matrix obtained from the forest machine learning study (with some data curation) of the PCA DataFrame (`FDS_PCA`) from the *Probability_and_main_Python_TFM.ipynb* code.
    - **CorrPCAConfMatrix.png:** plot of the confusion matrix obtained from the forest machine learning study (with some data curation) of the Correlation+PCA DataFrame (`df_corr_PCA`) from the *Probability_and_main_Python_TFM.ipynb* code.
    

## Objectives of the study

The main objetive of this study is to create a MachineLearning/Probability based computing system to calculate the probability fo attrition of certain people or groups in a given company. Furthermore, after this first step being completed, we strive to understand why the main reasons this person/group wanted to leave in the first place.

This project strives to be as simple and understanding as possible for companies to implement in their daily basis. The final model will be later joined with a broader description of the company being studied with the SAC platform.
