**Cheat dataset**
https://github.com/botianzhe/CHEAT
https://www.kaggle.com/datasets/robikiso/cheat-dataset

**Competitions**
https://www.kaggle.com/c/llm-detect-ai-generated-text/data

**Notebook**
https://www.kaggle.com/code/harshitjais14/bert-pretrainingdetector/edit
In this notebook I tried to use the CHEAT dataset to create a pre-training classifier for LLM generated Text.
The cheat dataset has human,polished , fusion and generated segments but i have use only 2000 instances of human and generated each with a label of 0 and 1 to train the model. 
The test dataset has 400 instance of both classes and the accuracy we got is around 97 % in classification.
