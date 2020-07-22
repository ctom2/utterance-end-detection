# Utterance end detection

AlquistAI task.

Task: Recognize the end of an utterance based on already spoken words. 

The objective can be described as a binary classification task as the implemented models try to decide whether the input is a finished utterance (= the user already said everything he wanted) or if it was interrupted and it is necessary to keep listening to the user in order to analyse the desired task. 

Tests:
* utterance_end_detection.ipynb
* utterance_end_detection2.ipynb

Main notebooks:
* workshop_replication.ipynb - replication of the [Deep Learning for Text Processing Workshop at Machine Learning Prague 2018](https://github.com/rossumai/mlprague18-nlp) network
* BERT_tokenizer.ipynb - using the BERT tokenizer and a simple neural network
* BERT_ktrain.ipynb - using the full BERT model
