# bart-bert-project
Plan B project: enhance BERT text classification by generating synthetic data with BART

- Data: ag_news(https://huggingface.co/datasets/ag_news) from HuggingFace. Extract 4000 data for trainset (imbalance data with class 0:1:2:3=5:8:12:15), 3000 data for test set.
- Baseline model: BERT. Accuracy=0.91
- BART
- BART with AuxiliaryClassifier
