# KGS: Knowledge-Guided Causal AI System

Our code for KGS is based on the GES implementation from the repository: https://github.com/py-why/causal-learn

The simulated datasets as well as the real BnLearn datasets and all ground-truths are provided in the zipped file.

-------Step by step instructions to test KGS--------

1. To use KGS, please install the available package causal-learn using pip:  "pip install causal-learn"

2. The main file to run KGS is the test_KGS.py where the datasets and ground truth are loaded.

3. To use prior knowledge please refer to the KGS.py file located at:

KGS-Code\causallearn\search\ScoreBased\KGS.py. 

The way to load prior knowledge is mentioned in details in that file.
