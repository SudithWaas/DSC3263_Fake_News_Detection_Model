# DSC3263 Fake News Detection Model
### Project: Contextualized Fake News Detection Using Transformer Models 
## Description

Enhance the fake news detection project by leveraging transformer models, such as BERT, GPT for contextualized analysis. Instead of treating each news article as an isolated entity, consider the context and semantics of the surrounding text. By incorporating transformer-based models, the aim is to improve the accuracy and contextual understanding of fake news detection, considering the border context in which the articles are presented.

Group Members: 
  - S/18/332 - W.G.A.C. Chandrasena
  - S/18/337 - A.P.S.I. De Waas Gunawardhana
  - S/18/406 - P.K.K.N.S.Jayathilake

# Dataset

The Fake News Corpus, an open-source dataset primarily made up of millions of news articles collected from a carefully curated list of 1001 sites from http://www.opensources.co/ (currently, the website is broken), serves as the main dataset used for the false news identification challenge. According to the dataset description it contains merely 9,408,908 articles (745 out of 1001 domains) are present in the public edition. The label assigned to each article matches the label linked to its domain. There are 10 distinct 1GB sized zip files containing the news corpus.

# Results

Bert model performs 97.85% accuracy on test data, whereas the BiLSTM model performs 93.65% accuracy. Our results show that the BERT model improves 4.2% of the accuracy in fake news detection compared to the BiLSTM Model. 
