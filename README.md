This repo contains modifications of [gensim word2vec](https://github.com/RaRe-Technologies/gensim) for calculating a model for 2-D data. 
For each pixel, ions/formulas occuring in a window around it are considered to constitue a context.

The following parts of the original gensim code have been modified.
* class PixelCorpus in word2vec_pix.py
* build_vocab_pix() in word2vec_pix.py
* train_pix() in word2vec_pix.py
* train_batch_cbow_pix() in word2vec_inner.pyx
