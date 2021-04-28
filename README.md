# Sentip: Thai Social Data Sentiment Classifier
> Bidirectional GRU-CNN with Self-Attention Model for Thai Social Data Sentiment Classifier
> 
This project is the part of my Senior Project in CSS403 Computer Engineering Project, Computer Engineering Department at SIIT

## **My Advisor**
- Assoc. Prof. Dr. Ekawit Nantajeewarawat

# Requirements
- Python 3.7.x
- pip install -r requirements_dev.txt


## How to use and Examples
- pip install Sentip
- Version 1.0.0
- [Notebook Example](https://colab.research.google.com/drive/1WCpulJ62ZpXiOnSn3NBw61qBg1d4mQ1p#scrollTo=67WNaDomSazh)

```
!pip install Sentip
from Sentip.Sentip import *

sentip = Sentip()
sentiment_result1 = sentip.sentiment('นี่มันแย่มาก ๆ เลย')

print(sentiment_result1)
> ['neg']

input_text = ['สวัสดี','ที่สุดไปเลย']
sentiment_result2 = sentip.sentiment(input_text)

print(sentiment_result2)
> ['neu', 'pos']
```


## Limitation 
- Must feeding with String | List | Numpy-Array
- Max Word for feeding: 450 words / paragraph
- Results: [sentiment1, sentiment2, sentiment3,..., sentiment4]

## Dependency
- Tokenization apply pythainlp.tokenize.word_tokenize(_text_ls, engine="newmm")
- POS apply pythainlp.tag.pos_tag(_sentence_ls, corpus="orchid") 



# **Contributor**
- Panjapol Ampornratana
- Phitchayapha Niyomwan
- Natnapin Maspakorn
