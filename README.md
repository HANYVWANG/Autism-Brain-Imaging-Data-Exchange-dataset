# Autism-Brain-Imaging-Data-Exchange-dataset

The dataset comprises 47 subjects from the YALE study site, part of the ABIDE resting-state fMRI data (http://preprocessed-connectomes-project.org/abide/quality_assessment.html). 

The 'YALE_fmri' is a list where each element corresponds to a fMRI time series matrix for a single subject. Each matrix has dimensions of 196 × 110, where 196 represents the number of time points in the fMRI data and 110 denotes the number of brain regions. 

The 'YALE_demo_var' is a data frame containing demographic information for the corresponding subjects. Among them, `DX_GROUP` is the Diagnostic Group (1=Autism; 2=Control); `AGE_AT_SCAN` is the Age at time of scan in years; `SEX` is subject gender (1=MALE; 2=Female).
