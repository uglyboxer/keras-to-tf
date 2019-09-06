Notebooks for:

- Creating a toy model in "classic" Keras
- Converting it the Tensorflow 1.x Keras API
- Wrapping the model with an embedding lookup
- Exporting to saved_model format for TF-Serving

```
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```


Grab the IMDb Sentiment Dataset from [here](https://ai.stanford.edu/~amaas/data/sentiment/).  You'll need to unpack it into a directory of your choosing, here we'll call it `data/`.

And we'll also grab the Glove word vectors from [here](http://nlp.stanford.edu/data/glove.6B.zip).  We can unpack that in `data/` too.

Attributions for the imdb dataset and the glove vectors.

```
'''
@InProceedings{maas-EtAl:2011:ACL-HLT2011,
  author    = {Maas, Andrew L.  and  Daly, Raymond E.  and  Pham, Peter T.  and  Huang, Dan  and  Ng, Andrew Y.  and  Potts, Christopher},
  title     = {Learning Word Vectors for Sentiment Analysis},
  booktitle = {Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies},
  month     = {June},
  year      = {2011},
  address   = {Portland, Oregon, USA},
  publisher = {Association for Computational Linguistics},
  pages     = {142--150},
  url       = {http://www.aclweb.org/anthology/P11-1015}
}
'''

# Glove attribution
'''
@inproceedings{pennington2014glove,
  author = {Jeffrey Pennington and Richard Socher and Christopher D. Manning},
  booktitle = {Empirical Methods in Natural Language Processing (EMNLP)},
  title = {GloVe: Global Vectors for Word Representation},
  year = {2014},
  pages = {1532--1543},
  url = {http://www.aclweb.org/anthology/D14-1162},
}
'''
```
