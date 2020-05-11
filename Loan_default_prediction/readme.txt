Install libraries:
	1: pip install -r requirements.txt

DATA:
	1.train_v2.csv: original data
	2.feature_without_cor.csv: preprocessed data without correlated features
	3.feature.csv: Preprocessed data with correlated features
	4.label.csv: label file
Code:
	1:feature.ipynb: Data preprocessing and features building
	2: Model: Model buidling
	3: logistic_with_WoE.ipynb
Run code:
	1. First run feature.ipynb, then Model_final.ipynb
	2. Logistic_with_WoE.ipynb(run independently)

