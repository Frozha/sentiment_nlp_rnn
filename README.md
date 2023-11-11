# Sentiment analysis (Natural Language Processing) using Recurrent Neural Networks
This project aimed to analyse PM Narendra Modi's 2023 US visit, whether it was viewed as positively or negatively by **scraping Tweets, Comments and News Articles** from the internet and then using recurrent neural networks to classify them as **Positive or Negative sentiments**.

### Motivation
The motivation behind the project was that similar AI models could be developed to analyse public sentiment on newly released products by its parent company, so that investors and product designers can get a better overview of how the product is performing in the market and if it is contributing positively towards the company's brand image.

### Results
We were successful in creating a RNN model that was able to correctly classify positive and negative sentiments.
Here is the output snippet from [predict.ipynb](https://github.com/Frozha/sentiment_nlp_rnn/blob/main/Twitter/predict.ipynb).

![image](https://github.com/Frozha/sentiment_nlp_rnn/assets/116617959/83d11717-7085-4c40-8fff-e606b1e09e35)

Sentiment Values greater than 0 represent Positive Sentiment whereas values lesser that zero represent Negative Sentiment. Higher the magnitude, stronger the expression of sentiment.

### Replicating Results
dependencies are provided in [requirements.txt](https://github.com/Frozha/sentiment_nlp_rnn/blob/main/requirements.txt)
- it is suggested to created a [virtual environment in python](https://docs.python.org/3/library/venv.html)
- then install dependencies by
    > pip install -r requirements.txt

### This Project was brought to completion as a result of a joint effort by
- **Biswajit Das** - [Newspaper and Youtube Data Extraction and Analysis](https://github.com/Frozha/sentiment_nlp_rnn/tree/main/YouTube%2BNewspaper)
- **Devajyoti Das Adhikary** - [Newspaper and Youtube Data Extraction and Analysis](https://github.com/Frozha/sentiment_nlp_rnn/tree/main/YouTube%2BNewspaper)
- **Someshwar Banerjee** - [Newspaper and Youtube Data Extraction and Analysis](https://github.com/Frozha/sentiment_nlp_rnn/tree/main/YouTube%2BNewspaper)
- **[Hrithvik Kondalkar](https://github.com/Frozha)** - [Twitter data extraction and analysis](https://github.com/Frozha/sentiment_nlp_rnn/tree/main/Twitter)

