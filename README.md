# Flatiron-Project-4-
The final notebook can be found in the main branch along with the prsentation: 
- Notebook: https://github.com/RaymondLeong94/Flatiron-Project-4-/blob/main/Project%204%20Final.ipynb
- Presentation: https://github.com/RaymondLeong94/Flatiron-Project-4-/blob/main/Twitter.pdf

# Introduction
- The purpose of this project was to analyze tweet sentiments through various string manipulation techniques and through VADER. This allowed us to hone in onto the problems associated with negative tweets and seek to address issues such as Google's service delay's on their mobile devices. 

- By building a model we are able to create the fundamentals necessary to run this as an actual application for Google, where generating a pipeline in the future would be necessary for a dynamic 'tweet analysis machine

- We will utilize only the tweet columns of the crowdflower source, since the dataset is incomplete/biased

-The final model consisted of a TFIDF vectorizer that is then passed into MNB. This allows for a CM to be displayed for model adjustments for precision and even F-1 scores. Acessible here: https://data.world/crowdflower/brands-and-product-emotions
![image](https://user-images.githubusercontent.com/98904682/202356720-8e8f928f-7f9b-4f64-b07f-9082e58880e0.png)

![image](https://user-images.githubusercontent.com/98904682/202356775-fc3d0347-8b8d-41c7-abdf-99b28648bdc3.png)


# Purpose and Goals
- The purpose of this project was to assist Google in making buisness decisions on what they need to improve on based on the sentiment of the tweet

- For neutral tweets it should be necessary to monitor the content for production purposes, as 'launch' 'store' and other unigrams was extremely important towards the #SWSX launch.

- For positive tweets, it represented what Google was doing well
 ![image](https://user-images.githubusercontent.com/98904682/202356118-b9607c0e-67e2-4438-8d48-c1cc38faec63.png)

-Likewise it was the same for negative tweets
![image](https://user-images.githubusercontent.com/98904682/202356160-99ed1dd2-1eed-4f78-831d-d8297627465d.png)

-As long as the precision matched the accuracy and the percentage wasnt terrible, (75% accuracy 77% precision), we can accept the model as is, but it is recommended to improve on the stopwords and possibly stem it.

# Results
 - Model Timeline
 -- Initial commit - had the backbone of the project ready, EDA was conducted, models were not determined
 -- Second commit - Models were evaluated and polished
 -- Third commit - Discussions and Finalized the notebook 
 - CM results
  ![image](https://user-images.githubusercontent.com/98904682/202356818-dc7a9763-d663-4480-a758-6deec773e982.png)
 -- **Results are not indiciative of any action needed by Google in order to enhance their products**
 
 # Conclusion
 - Despite my best efforts, NLP requires many iterations in order for it to be fully functional. Scores don't matter unless you can analyze the uni- bi/tri/etc grams and how it can affect the corpus 
 - Twitter as of 11/16/22 is under the acquisition of a new CEO; the platform may change from this point and this project's relevancy may be outdated soon.
