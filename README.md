# Do the alcohol consumption habits of a country influence its beer reviews?

A geographical study on the link between drinking habits and their influence on online beer reviews

## Abstract 

The world can be divided by regions based on their alcohol consumption habits. The world is then not split into countries 
anymore but into four *culturally similar*, (based on alcohol consumption) regions. We can distinguish: the predominantly
**beer drinking** countries, the predominantly **wine drinking** countries, the predominantly **spirit drinking** 
countries and the countries that don't have any predominance. \
The idea is to see if these habits have an influence on their beer reviews. We will conduct a two steps analysis: first, 
we will study the semantic of the comments let by the user on the website and according to their drinking habits. 
Then, we will analyse the ratings (scores) according to their drinking habits and look if the drinking habits of users
have an impact on their ratings and preferences in term of style of beer.

## Research questions

* Will the consumption habits of a country influence the comments given by the users?
* Will they have writing patterns corresponding their drinking habits? 
* Will people that come from *wine drinking countries* often use more words initially used to describe wine? 
* Will people that come from *beer drinking countries* give higher marks than the other to beers?
* Will people  that come from *beer spirit countries* give higher marks to strong beer (in term of taste or
alcohol) than the others?

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

Our preprocessed datasets can be found here:
*https://drive.google.com/drive/folders/1wTLd3ihuJyaspmlKB2DAXekbt8QjK5me?usp=sharing*

## Methods

- **Key word detection**: pretrained NLP algorithm KeyBERT
- **Language detection**: use langdetect library translation: from deep_translator library, use GoogleTranslator
- **Beer clustering**: data augmentation, k-means clustering, SVM clustering

## Proposed timeline

- **Week 10**: Finishing the translation and key-words highlighting for the whole datasets. Take into account the feed-back received and
finetuning the clustering to have relevant beer types
- **Week 11**: Doing the website skeleton + already have an introduction of our data story on our website
- **Week 12**: Finishing the analysis of the review and grading section
- **Week 13**: Finding and creating the best visualisation approaches
- **Week 14**: Finalizing the redaction of the datastory on the website

## Organization within the team

- **Teammate 1** = Clustering for grading analysis + helping for the website
- **Teammate 2** = Creating website
- **Teammate 3** = Finishing translation and key-words highlighting  + Comment analysis
- **Teammate 4** = Comment analysis + Grading analysis

## Questions for the TAs

- **Question 1**: Is it beneficial to remove users who have a high amount of reviews(e.g. 5 reviews a day for 20 years)? Or is there an explanation?
- **Question 2**: Is it feasible to detect formal language words occurence in comments, and it is interesting?
- **Question 3**: Enjoy our homemade video from section 1) II) b)! Sit back and relax!


https://user-images.githubusercontent.com/91135493/202773601-875aa211-31d6-4631-b72f-4768caa5c8a4.mp4



