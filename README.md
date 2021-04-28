# Sentip: Thai Social Data Sentiment Classifier
> Bidirectional GRU-CNN with Self-Attention Model for Thai Social Data Sentiment Classifier




# Requirements
- Tensorflow 2.0+
- Keras 2.0+
- Python 3.6.x
- pip install -r requirements_dev.txt


## How to use and Examples
- pip install Sentip
- Version 1.0.0
- [Notebook Example](https://colab.research.google.com/drive/1WCpulJ62ZpXiOnSn3NBw61qBg1d4mQ1p#scrollTo=67WNaDomSazh)


## Limitation 
- Max Word for feeding: 450 words / paragraph
## Dependency
- POS apply pythainlp.tag.pos_tag(_sentence_ls, corpus="orchid") 
- Tokenization apply pythainlp.tokenize.word_tokenize(_text_ls, engine="newmm")



# Contributor
Panjapol Ampornratana
