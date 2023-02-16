# Natural Language Processing Notebooks

Homework (jupyter) notebooks from a Natural Language Processing (NLP) course at CIMAT.

The notebooks cover several topics:
- tarea_1 - basic text mining, analysis of the stenographics from the (Mexico's) president  daily conferences.
- tarea_2 - classification (with a SVM) of aggressive tweets (from [mex-a3t](https://sites.google.com/view/mex-a3t/home)) using many tweet (document) representations, including Bag of Words (BoW) with different weights:
	- binary
	- frequency
	- tf-idf (term frequency inverse documen frequency) ...
- tarea_3 - an implementation of TCOR (term co-occurrence representation), a DTR (document term representation) and a comparison with the best performing BoW (in tarea_2) to classify aggressive tweets (again, with a SVM).
- tarea_4 - an implementation of N-gram language models, then training on those models with tweets and president conferences to generate tweets and conferences (respectively), and compute probabilities and perplexities.
- tarea_5 - an implementation of Bengio's Neural Language Model for words and characters (both using trigrams) using two slighly different network topologies, then training on those models with tweets to generate tweets and compute probabilities and perplexities.


**Note:** The code is written (including comments) in English, but the language of the pdfs, exercises and data sets is Spanish. The code should work for other languages with minor modifications (use the respective set of stop-words)

## Requirements

- numpy
- [NLTK](https://www.nltk.org/install.html)
- [WordCloud](https://amueller.github.io/word_cloud/)
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/#)
- pytorch
- sklearn.
