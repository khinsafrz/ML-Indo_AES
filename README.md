# ML-Indo_AES

Khinsa Fairuz Zahirah
CONTENT-BASED INDONESIAN LANGUAGE AUTOMATED ESSAY SCORING SYSTEM USING MACHINE LEARNING ALGORITHMS

This project explores the application of machine learning techniques for Automated Essay Scoring (AES) system. It uses two different datasets (IQA and ASAP AES) and three ML algorithms (Multinomial Naive Bayes, XGBoost, Neural Networks) to be evaluated.

- The project is conducted in Google Colab.
- The project uses Python version 3.10.12.
- Four CSV files:
   - CMP_dataset.csv: original IQA dataset
   - cmp_id.csv: original ASAP AES dataset
   - Preprocessed_data.csv: preprocessed IQA dataset
   - Preprocessed_data_ID.csv: preprocessed ASAP AES dataset
- Six .ipnyb files:
   - Two preprocessing files (one for each dataset):
	- CMP IQA preprocessing
	- CMP ASAP AES preprocessing
   - Two classification algorithms (MNB and XGBoost) files (one for each dataset):
	- CMP IQA Classification
	- CMP ASAP AES Classification
   - Two regression algorithm (NN) files (one for each dataset):
	- CMP IQA Regression
	- CMP ASAP AES Regression
- Three text files:
     - id.stopwords.txt (Indonesian language stop words)
     - id.allwords.txt (Indonesian language vocabularies)
     - glove_id.txt (GloVe embeddings for Indonesian words) (this one cannot be uploaded to github because it is larger than 25MB, can be shown on req)
   - The first two text files play a role in pre-processing steps.
   - The GloVe text file is specifically utilised within the Neural Networks model.
