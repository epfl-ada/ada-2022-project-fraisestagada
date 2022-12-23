# ADA DATA STORY

<<<<<<< HEAD
[View Data Story](https://constig.github.io/beer-data-story/)
=======
___ A geographical study on the link between drinking habits and their influence on online beer reviews

## Project data story

Our data story can be visualized by clicking on this link:  
*https://kieranvaudaux.github.io*


## Abstract 

The world can be divided by regions based on their alcohol consumption habits. The world is then not split into countries 
anymore but into four *culturally similar*, (based on alcohol consumption) regions. We can distinguish: the predominantly
**beer drinking** countries, the predominantly **wine drinking** countries, the predominantly **spirit drinking** 
countries and the countries that don't have any predominance. \
The idea is to see if these habits have an influence on their beer reviews. We will conduct a two steps analysis: first, 
we will study the semantic of the comments let by the user on the website and according to their drinking habits. 
Then, we will analyse the ratings (scores) according to their drinking habits and look if the drinking habits of users
have an impact on their ratings and preferences in term of style of beer.
We realized that making a study on all types of beers together was to general, and decided to group the beer types in eight general beer types.

## Research questions

* Will the consumption habits of a country influence the comments given by the users?
* Will they have writing patterns corresponding their drinking habits? 
* Will people that come from *wine drinking countries* often use more words initially used to describe wine? 
* Will people that come from *beer drinking countries* give higher marks than the other to beers?
* Will people  that come from *beer spirit countries* give higher marks to strong beer (in term of taste or
alcohol) than the others?
* Will we discover, per consumption habits, some preferences regarding the general beer types?

## Additional datasets

We use additional datasets from *WHO, Global Health Observatory* released in 2022 that gives:
*  Beer as a share of total alcohol consumption in 2016
*  Wine as a share of total alcohol consumption in 2016
*  Spirit as a share of total alcohol consumption in 2016
We already read it and extracted the information needed to give a label of the predominantly drunk beverage (if any).
We can download them in: *https://ourworldindata.org/alcohol-consumption*.

To study the semantic of the comments we use the following lists of words:
* Words from wine terminoly: *https://fandbtraining.net/advanced-service/wine-service/words-to-describe-wine/* Note that this is list of word has been converted to a txt file that can be found here:
*https://drive.google.com/file/d/1RbJm9Kqf3XTNHwlDY1bprD9BQDSCU9ai/view?usp=sharing*
* Positive words: *"https://ptrckprry.com/course/ssd/data/positive-words.txt"*
* Negative words: *"https://ptrckprry.com/course/ssd/data/negative-words.txt"*

## Methods

We made the choice of splitting the dataset in four categories, as we already mentioned. We will conduct analyses on the ratings and comments, using these listed methods:

**Key word detection**: pretrained NLP algorithm KeyBERT
**Language detection**: use langdetect library translation: from deep_translator library, use GoogleTranslator
**Beer clustering**: data augmentation, k-means clustering, SVM clustering, TF-IDF

Our first step was to translate the none english comments in order to incorporate them in out comments analyses. In order to deal with the text, we try different ways to extract informations, such as important words or key words. We also used TF-IDF as the first step of the clustering of comments. 

Conducting analyses on 70 different beer types was to large. Grouping the beers in larger groups enabled us to get a better overview of the results. 

## Organization within the team

**Teammate 1** = Clustering for grading analysis + helping for the website  
**Teammate 2** = Creating website  
**Teammate 3** = Finishing translation and key-words highlighting  + Comment analysis 
**Teammate 4** = Comment analysis + Grading analysis  
>>>>>>> 7f4efdd9e6f74a4fe84a56895982e225402bfb56
