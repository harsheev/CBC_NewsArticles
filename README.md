# CBC_NewsArticles
LDA on 7000 news articles from CBC Canada website.

Note: This project was made entirely on google colab

1. The project comprises of 3 jupyter notebooks
  - Data_cleaning.ipynb 
  This notebook goes over the process of loading in the data set, cleaning the data and creating the corpus, dictionary and text files needed to train an LDA model using gensim.
  
  - Creating_models.ipynb
  This notebook goes over creating LDA models with different number of topics and chossinf the best model based on C_v coherence.

  - Model_visualization.ipynb
  This notebook uses pyLDAvis toolset to visualize the selected LDA model and draw other insights which help in better understanding the different topics.

NOTE: Click on the "Open in Colab" button in the .ipynb files to access them in an interactive google colab environment.

2. The data set used is stored as a csv file in CA_news.zip

3. Files named- corpus.pkl, dictionary.gensim, text_data.pkl are files created in Data_cleaning.ipynb and are used to create LDA models later on.

4. Files ending in .gensim, .gensim.expElogbeta.npy, .gensim.id2word, .gensim.state were created in Creating_models.ipynb by the gensim library while creating different models.

LIBRARIES USED:
Pandas
Numpy
Matplotlib
Gensim
Spacy
NLTK
Random
Pickle
pyLDAvis

References:
- https://nlp.stanford.edu/events/illvi2014/papers/sievert-illvi2014.pdf 
- https://www.os3.nl/_media/2017-2018/courses/rp2/p76_report.pdf       
- https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/ 
