# Notebook *What Is Digital Humanities?*

This note book illustrates the creation of a word cloud with data form [What Is Digital Humanities?](https://whatisdigitalhumanities.com/), available as a .csv table in [GitHub](https://github.com/hepplerj/whatisdigitalhumanities).

## Setup

[Anaconda](https://www.anaconda.com/products/individual) is the intended enviroment to use this notebook. In order to run this notebook, you have to install some missing libraries and download the nltk list of english stopwords.

* Start *JupyterLabs* from *Anaconda Navigator*
* Open new *Terminal* in *JupyterLabs*
* in *Terminal*
  * type *python* to start python console
    * type *import nltk* to load nltk library (and wait a few seconds)
    * type *nltk.download('stopwords')* to download stopwords
    * type *exit()* to leave python console
  * type *pip install wordcloud* to install wordcloud library
  