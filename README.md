# Code-Comment Coherence Prediction using Co3D Approach  

### Problem Statement
+ Code comments play a crucial role in software development, as they provide programmers with practical information, allowing them to understand better the intent and semantics of the underpinning code. Nevertheless, developers tend to leave comments unchanged after updating the code, resulting in a discrepancy between the two artifacts. Such a discrepancy may trigger misunderstanding and confusion among developers, impeding various activities, including code comprehension and maintenance. Thus, it is crucial to identify if, given a code snippet, its corresponding comment is coherent and reflects well the intent behind the code.

### Purpose of this Project 
+ This work presents CO3D as a practical approach to the detection of code comment coherence. This approach pays attention to internal meaning of words and sequential order of words in text while predicting coherence in code-comment pairs, using a combination of Gensim Word2Vec Embedding and RNN, as well as CodeBERT.
