# ML_models_Research

Research Topic : CLASSIFICATION OF DIABETES AND HYPERTENSION:A PERFORMANCE COMPARISON BETWEEN CLINICAL DATA AND SINGLE OMICS DATA

This repo contains the data set and machine learning models build for the clasification of each diabetes and hypertension


# Diabetic clinical:
Data set : 
    491 - false(0)
    253 - true(1)
    8- features

model_set_01 
    - no feature selection, 
    - udersampled, sampling_strategy= 0.7, random_state = 0 so false instances become 361. (130 samples removed)
    - then oversapled, random_state = 0,  (108 dummy samples were added)
    - 361/361 samples - (total = 722)
    - use train_test_split for validation



# Diabetics transcriptome:



# Hypertension clinical:

Data set : 
    203 - false(0)
    96 - true(1)
    8- features

model_set_01 
    - no feature selection, 
    - udersampled, sampling_strategy= 0.7, random_state = 0 so false instances become 137. (66 samples removed)
    - then oversapled, random_state = 0,  (41 dummy samples were added)
    - 137/137 samples - (total = 274)
    - use train_test_split for validation


model_set_02
    - no feature selection, 
    - udersampled, random_state = 0 so false instances become 96. (107 samples removed)
    - 96/96 samples - (total = 192)
    - use train_test_split for validation

model_set_03
    - no feature selection, 
    - no sampling
    - 96/203 samples - (total = 192)
    - use train_test_split for validation

model_set_04
    - no feature selection, 
    - udersampled, sampling_strategy= 0.7, random_state = 0 so false instances become 137. (66 samples removed)
    - then oversapled, random_state = 0,  (41 dummy samples were added)
    - 137/137 samples - (total = 274)
    - use cross validation for validation vc = 5


# Hypertension transcriptome:
