# Natural_language_processing
## By Franklin Vaca
Use of natural language processing: NLTK. tokenization, n-grams, word clouds, NER and Sentiment Analysis in Crypto. 
The news articles used for this analysis came from newsapi.org
Date: 09/18/2021

## **1. Sentiment Analysis**
### **1.1: Which coin had the highest mean positive score?**<br>
><p>Bitcoin had a slightly higher mean positive score than Ethereum (BTC: 0.0643 vs ETH: 0.0641)</p><br>
### **1.2: Which coin had the highest positive score?**<br>
><p>Ethereum had the highest positive score at 0.288 compared to Bitcoin (BTC Positive Max: 0.213)</p><br>
### **1.3: Which coin had the highest negative score?**<br>
><p>Ethereum had the highest negative score at 0.312 compared to Bitcoin (BTC Negative Max: 0.208))</p><br>
### **1.4: Which coin had the highest compound score?**<br>
><p>Ethereum had the highest compound score at 0.844 compared to Bitcoin (BTC Compound Max: 0.811)</p><br>

*Summary Statistics of Sentiment Scores for Bitcoin*

![image](Analysis_graphs/Bitcoin_sentiment_scores.PNG)


*Summary Statistics of Sentiment Scores for Ethereum*

![image](Analysis_graphs/Ethereum_sentiment_scores.PNG)

## **2. Natural Language Processing**
### **2.1: Tokenizer**<br>

*Tokenizer - Bitcoin (Only first five news articles shown here)*

![image](Analysis_graphs/Bitcoin_tokenizer.PNG)

*Tokenizer - Ethereum (Only first five news articles shown here)*

![image](Analysis_graphs/Ethereum_tokenizer.PNG)


### **2.2. NGrams and Frequency Analysis**<br>

*Bitcoin N-grams where N=2*

![image](Analysis_graphs/Bitcoin_n_grams.PNG)

*Ethereum N-grams where N=2*

![image](Analysis_graphs/Ethereum_n_grams.PNG)

*Bitcoin News Articles Top 10 words*

![image](Analysis_graphs/Bitcoin_top.PNG)

*Ethereum News Articles Top 10 words*

![image](Analysis_graphs/Ethereum_top.PNG)

### **2.2. Word Clouds**<br>

*Bitcoin Word Cloud*

![image](Analysis_graphs/Bitcoin_word_cloud.PNG)

*Ethereum Word Cloud*

![image](Analysis_graphs/Ethereum_word_cloud.PNG)


## **2. Named Entity Recognition**
### **2.1: Bitcoin NER**<br>

![image](Analysis_graphs/Bitcoin_ner.PNG)

### **2.2: Bitcoin NER - Entity Word Cloud (GPE, PERSON, NORP)**<br>

![image](Analysis_graphs/Bitcoin_ner_entity.PNG)

### **2.3: Ethereum NER**<br>

![image](Analysis_graphs/Ethereum_ner.PNG)

### **2.4: Ethereum NER - Entity Word Cloud (GPE, PERSON, NORP)**<br>

![image](Analysis_graphs/Ethereum_ner_entity.PNG)