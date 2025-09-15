**Name**: Shivan Ajay Iyer

**Roll number**: be22b048
  
This repo has the code and analysis to explore how creating artificial data (SMOTE) and different undersampling and oversampling approaches (CBO and CBU) can address class imbalance.
Crucially, it examines how using GMMs is a better method to recreate multimodal data that oversamples the minority class. I also employ a hybrid approach that uses both GMM-based oversampling and CBU based down-sampling. 

Logistic Regression is used as a proxy performance measure of the success of different sampling approaches.


The credit card fraud dataset, available on Kaggle, was used for this analysis as it is a highly imbalanced dataset with very few instances of fraud as compared to the majority class. 


The repository has all notebooks and saved data in the **analysis folder**. 
I have not pushed the saved credit dataset as it is over the 100 MB limit. 

**Files**:


1. **GMM_corrected**: 
_This file has the complete code for the entire analysis required in the Problem Statement 4_
3. **credit_dataset**: 
The scaled and processed credit CSV. This is only on my local system. However, running the complete_analysis file will save it on your system

4. **GMM_based_approach**
Contains my initial exploration of the problem statement using GMMs

5. **Pure_GMM_coarse_Search**
Contains the results of the grid search(GS) to find optimal model parameters for the pure GMM approach. 

6. **Hybrid_Configuration_GS_Results**
Contains the results of the GS for the hybrid model parameter optimisation. 

7. **SMOTE_CBU_CBO_logreg_analysis**
Contains the solution to the problem statement in as 3. Explores SMOTE, CBU, and CBO approaches to address class imbalance

8. **Da5401_as3_report**: 
Provides a detailed report that explains and compares each method used to address the class imbalance. Also, summarises key results from the code. 


