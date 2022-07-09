# Humor Analysis with pretrained Models and HAHA2019 dataset

We wanted to test the results obtained with what we call nowadays the NLP State-of-the-art in Competitions already ended and Compare with the results shown in their [paper][paperhaha].

# Results

*(For First task)*

|Model|Preprocessing|F1-Score|
|---|:---:|:---:|
|Support Vector Classification| Deleting features correlated & TF-IDF|0.740|
|Logistic Regression| Deleting features correlated & TF-IDF|0.716|
|BERT|uncased|0.787|
|BERT|cased|0.768|
|mBERT|uncased|0.800|
|BETO|uncased|0.813|
|spanBERTa|uncased|0.799|
|roBERTa|uncased|0.757|

Models are base version and they have been trained for 3 epochs.

[paperhaha]: https://aclanthology.org/2020.lrec-1.628.pdf
