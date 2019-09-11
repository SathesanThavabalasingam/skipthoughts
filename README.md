# skipthoughts
Evaluation of skip-thoughts model outlined in Kiros paper (https://arxiv.org/pdf/1506.06726.pdf)

An encoder decoder model that tries to reconstruct the surrounding sentences of an encoded passage. Sentences that share semantic and syntactic properties are thus mapped to similar vector representations. The skip-gram model is abstracted to the sentence level. Instead of a word predicting surrounding words within a setnence, this model aims to encode a sentence to predict surrounding sentences!

## Dependencies

This code is written in python. To use it you will need:

* Python 2.7
* Theano 0.7
* A recent version of [NumPy](http://www.numpy.org/) and [SciPy](http://www.scipy.org/)
* [scikit-learn](http://scikit-learn.org/stable/index.html)
* [NLTK 3](http://www.nltk.org/)
* [Keras](https://github.com/fchollet/keras) (for Semantic-Relatedness experiments only)
* [gensim](https://radimrehurek.com/gensim/) (for vocabulary expansion when training new models)
