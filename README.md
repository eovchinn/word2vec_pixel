This repo contains modifications of [gensim word2vec](https://github.com/RaRe-Technologies/gensim) for calculating a model for 2-D data. 
For each pixel, ions/formulas occuring in a window around it are considered to constitue a context.

The following parts of the original gensim code have been modified.
* class [PixelCorpus](https://github.com/eovchinn/word2vec_pixel/blob/master/word2vec_pix.py#L1797-L1847) in word2vec_pix.py
* [build_vocab_pix()](https://github.com/eovchinn/word2vec_pixel/blob/master/word2vec_pix.py#L598-L691) in word2vec_pix.py
* [train_pix()](https://github.com/eovchinn/word2vec_pixel/blob/master/word2vec_pix.py#L924-L1127) in word2vec_pix.py
* [train_batch_cbow_pix()](https://github.com/eovchinn/word2vec_pixel/blob/master/word2vec_inner/word2vec_inner.pyx#L404-L505) in word2vec_inner.pyx
