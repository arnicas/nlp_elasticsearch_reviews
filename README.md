# NLP in Python and ElasticSearch

Conference talk materials for the Dato/Turi data science symposium in SF, July 12-13, 2016.
Online slides to go with: http://ghostweather.slides.com/lynncherny/deck-6.

Three parts:

* Mostly pandas analysis of Yelp  eviews in Python, and some simple NLP.  Create dataframes that can be read into Elasticsearch.  This is the "1. Yelp Reviews Explored in Python" notebook.
* Elasticsearch demo and examples in another notebook, using saved df's, in "2. ElasticSearch-Tricks-and-Tips.ipynb".
* Web demo using the elasticsearch-js library, in the web directory.  Assumes a running localhost instance of your indexed data.

All of them assume localhost usage.

### Python Environment

Install and use miniconda from Continuum. Create your environment with:

```` 
conda env create -f environment.yml
[.... say yes to everything...]
source activate esnlp
````

It's called "esnlp".

### Slides

Again: online slides to go with: http://ghostweather.slides.com/lynncherny/deck-6.

I'm @arnicas on Twitter.

