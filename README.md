# Distributed-Representations-Made-Easy
Distributed Representations (DR) play a significant role in machine learning. DR is a principled way of representing entities (say, cats or dogs) in terms of vectors.  Entities sharing common properties have  vector representations that are nearer to each other.

* The input and output of the Machine Learning (ML) models are often numeric. This requires finding a suitable numeric representation of text. Hence, they are encoded into numeric forms. One such example is One Hot Encoding. However, this kind of encoding does not capture the syntactic and semantic similarity of words in a corpus. This is taken care of by Distributed Representations. The famous Word2Vec model captures these similarities when provided with a corpus. 

* Although Word2Vec model provides us with good results, we have also attempted at getting word-embeddings by building a DNN and training it on the [Large Movie Review Dataset](https://aclanthology.org/P11-1015/) to achieve a certain acceptable value of accuracy (above 80%) by choosing a task of sentiment classification. We have achieved this with the help of Embedding module in Keras library. The sentiment classification task involved classifiying a movie reiview as a positive or negative review. Another interesting task that can be tried for getting the word-embeddings is word prediction by using sequential networks (like LSTM/GRU).

* You can find the data here{https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz}.
