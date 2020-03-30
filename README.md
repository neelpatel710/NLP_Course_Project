# NLP_Course_Project
Semantic similarity of sentences is based on the
meanings of the words and the syntax of the sentence. The
semantic analysis plays an important role in the research related
to text analytics. The sentences are preprocessed by performing
tokenization, removal of stop-words and punctuations,
and lemmatization. The similarity of sentences are calculated
based on semantic vectors and word order vectors along with
considering the Part-of-Speech (POS). The semantic vectors are
computed using a Word2Vec model, which is trained and saved
upon the corpus. The word order similarity is computed using
word order vectors of both the sentences. Hence, the overall
semantic similarity between sentences is the summation of the
sentence similarity and word order similarity. The performance
of the algorithm is evaluated against the SICK dataset which
correctly predicts 81.30% of sentence pairs of SICK dataset.
