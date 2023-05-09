# Data Preprocessing
In this folder, we demonstrated how to process raw data downloaded from the Shamsara paper (https://data.mendeley.com/datasets/fdb8f5hjyd/1) in the following steps.

1. Upload data and creat a table in pandas dataframe that have genetic variants as columns, patient samples as rows, and one additional column labeling the stage of prostate cancer.

2. Process data
    a. Omit zero value and use Mean Imputation to remove NA value.
    
    b. Remove features with zero variance
    
    c. Remove features with high correlation (>0.9)
    
    *See graph VisializeDataPro.png for a visualized understanding of step 2.*
    
3. Compare with the data description of the original paper.

After running codes in this folder, you will gain a csv table of processed data read for all other machine learning analysis.

## Coding Files
1. The Creat_mRNATable.ipynb file described Step 1.

2. The ProcessData.ipynb file described Q2.

3. The Verification.ipynb file described Q3.

## Output Files
After running this folder, you will get

1. mRNA_table.csv from Creat_mRNATable.ipynb that contains a table that have genetic variants as columns, patient samples as rows, and one additional column labeling the stage of prostate cancer.

2. data_processed.csv from ProcessData.ipynb that remove undesiring features from the mRNA_table.

## Explantory Files
1. Use VisializeDataPro.png for a visualized understanding of step 2.


