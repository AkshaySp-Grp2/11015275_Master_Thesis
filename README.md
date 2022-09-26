# 11015275_Master_Thesis
Thesis
Baseline_Thesis.ipynb file consist of independent line of code where in one can insert there dataset
and figure out which could be best Baseline model out of the 3 which are being included in the code.

1) Baseline model 1 -- No language translation and use of all-mpnet-base-v2 from sentence transformer.
2) Baseline model 2 -- Language Translation using MarianMT and use of all-mpnet-base-v2 from sentence transformer
3) Baseline model 3 -- No language translation and use of paraphrase-multilingual-mpnet-base-v2

Implementing_data_augmentation_strategies.ipynb 
Consists of 6 different classes:
1) DataCollect
2) Backtranslate
3) AEDA
4) EDA
5) Sbert
6) AllStrategy

Data collect is used to gather the data and make is sutaible for the data augmentation.
Backtranslate, EDA, AEDA and Sbert are different augmentation strategies.
All strategy a method which integrates all Backtranslate, AEDA , EDA and Sbert into one.
and functions such as run_with_eda etc performs the task of model generation and getting the evaluation metrics.
