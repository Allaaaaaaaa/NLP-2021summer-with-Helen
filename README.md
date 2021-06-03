# NLP-2021summer-with-Helen

# Topic
- Chatbot Development
- Research
  - Multi-language word embedding
  - Relation between word clusters

# Chatbot Developent
There is a contest about FAQ bot.

Link: 

Three features need to be achieved.
- The database has 2 parts. One part is our own knowledge base, and the other is some FAQ data. What we need to do first is to identify the user's question and check whether we can solve the question with our knowledge base. If not, then we go to the FAQ part.
- The 2nd feature is to correspond the user's question to the FAQ data, which means we should find the FAQ data we can use to answer the question.
- The 3rd feature is to extract the information from the corresponding FAQ, and then reorganize the information to generate our answer corresponing to user's question.(NLG)

# Cross-lingual word embedding

For different lang, we can represent the word in different word spaces. Then can we generate a universe word space to contain multi-lang words together?

Here we just need to consider ***Chinese and English***.

One recent popular direction is ***unsupervised cross-lingual word embeddings***.

Review paper: 
- A Survey of Cross-lingual Word Embedding Models  
  https://arxiv.org/pdf/1706.04902.pdf
- [A long version of last paper](Cross-Lingual Word Embeddings.pdf)
Two related unsupervised cross-lingual word embedding paper:
- A robust self-learning method for fully unsupervised cross-lingual mappings of word embeddings  
  https://www.aclweb.org/anthology/P18-1073.pdf
- Word translation without parallel data  
  https://arxiv.org/pdf/1710.04087.pdf

# Relation between word clusters

Now we can cluster similar words, but no one do the research about the relation between the words. For example, the word "computer" is not similar with the word "code", and they are definitly not in the same cluster. But we can code on computers, which means there is some relation between them. Then how to represent this relation? How to identify this relation?
