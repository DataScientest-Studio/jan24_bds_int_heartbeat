The code in the notebooks stores all models and classification reports.
Since some pickle models are >100mb, they cannot be pushed onto github.
The function to save those models will transfer them to ../data/models_too_big_for_git.
The whole ../data folder is only locally available, so in order to get those models, the corresponding notebook code 
has to be run.

The following models are too big for git:
- KNN_Basemodel_no_gridsearch_MITBIH_A_Original
- KNN_Basemodel_no_gridsearch_MITBIH_B_SMOTE
- KNN_Optimized_Model_with_Gridsearch_MITBIH_A_Original
- RFC_Basemodel_no_gridsearch_MITBIH_B_SMOTE