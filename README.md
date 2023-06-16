# LLMs vs. Humans: Representation of Different Senses of Homonyms

In this repository, I conducted an experiment with BERT to understand how it represents the different senses of the homonym words.
In the literature, behavioral studies demonstrated that concepts denoted with the same homonym word are represented as more semantically related in the mind.
In this experiment, I aimed to conduct a parallel study using BERT.
Using BERT multilingual base model (cased), I generated word embeddings for different senses of English homonyms and calculated their similarity with cosine similarity.
Then, I translated these sentences into Turkish (where these senses are not homonyms anymore).
Using cosine similarity, I found the word in Turkish translation that has the most similar word embedding to English sense word embedding and accepted it as the translation of the sense in English.
Then, calculated the word embeddings for the Turkish translations of the senses and calculated their similarity using a t-test.
The results showed that BERT represents English homonym senses as less similar to each other than their Turkish translations.
