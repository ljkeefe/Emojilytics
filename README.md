# Emojilytics

## Abstract

Businesses care what their customers think and more people than ever are using Emojis to express themselves on social media. As their use increases so to does the expressive power these characters will hold for text analysis. Using emotion detection and machine learning classification on product review tweets I will determine if there exists significant linkages between certain tweets and emotion. This allowing a new way for businesses to know how their customers feel about them and facilitate more successful use of Emojis in advertisement. 

<!--- I'm a little unsure of what you are attempting here. What does it mean to have a linkage between tweets and emotion? -->

## Context

Invented in 1998 Emojis have become a popular, practical, and fun way to convey meaning and emotion. Sentiment analysis frameworks use lexicon to determine sentiment scores and classify emotions, but many models do not possess the ability to analyze characters such as Emojis unless they are manually annotated. Further, it has been found that when used in combination with other Emojis it <!--- what is "it" in this case? confused. --> can shift the meaning of the individual Emoji which further inhibits simple manual annotation methods since intensity scores are seemingly subjective. <!---what are intensity scores? should you expect your audience to know this? --> 

The fabrication of an emotion detection sentiment analysis that recognizes Emojis is important because as use continues to increase so to will the amount of expression is possessed by the Emoji in the text. <!--- fix your grammar --> While there does exist a lexicon of definitions for Emojis this instead is merely developer labeling of these characters which may not align with the actual use patterns of users since Emojis are used in combination and have developed new meaning through social media trends.<!--- fix your grammar and clarify--> Therefore for organizations, especially large global firms, the need to analyze how and why their consumers are utilizing emojis is ever-growing since a significant portion of market and customer retention analysis is centered around text analysis. <!--- what is customer retention analysis? Do you know? Avoid jargon-->

## Proposal

With Emojis being an ever growing facet of online language how are users utilizing them in their discourse regarding businesses and their products? <!--- is this the same question you asked in your intro? i'm a little confused --> I will evaluate the emotion profiles <!---what is an emotion profile?--> of Emojis with regard to their ability to predict word affect intensities as well as the difference in the sentiment scores of tweets possessing them. Further, if the use of combination <!--- what is "use of combination?"--> adds expressive intensity and transforms the underlying emotional state being expressed.<!---fix your grammar-->

To answer my research question I will conduct a emotional detective sentiment analysis and then machine learning classification. First, for the sentiment analysis I will utilize tidy text to unnest each word and Emoji and then apply the nrc emotional lexicon (Saif Mohammad and Peter Turney) to join on emotional sentiment classes. Lastly, I will conduct Naive Bayes Binary classification and Random Forest modeling to classify each tweet and predict which Emojis will appear in each tweet. <!---maybe ...I'm curious about your data. What is it and how will you get it?-->

Emojis are a new facet of our language and with gaining popularity they will begin to at large replace some words in messages so the expression and sentiment they hold is going to gain more and more interest. I expect that Emojis like 'the heart' or 'frowny face' will hold true to their constructed expression, but for a multitude of significantly used Emojis to have high variance in expression. <!--- I think I know what this means, but you should work to clarify your language--> Through this framework I hope to better understand not only how individuals are using Emojis to create discourse about businesses but also which Emojis have the most narrow use pattern and have high emotional intensity associated with them.

## Conclusion

With the creation of Emojis it has allowed users another medium of expression in their online messaging but with traditional sentiment analysis the expressive power and occurrence of Emojis has not been able to be analyzed. By analyzing the emotional intensity and sentiment of business and product review tweets it can provide insights on the underlying expression being conveyed by the Emoji. Through machine learning classification algorithms it can be revealed how predictive Emojis are of sentiment and emotional intensity which could provide great insight for researchers as well as businesses to better understand users in this new age.
  
  The limitations of this research fall are similar to those of traditional sentiment analysis. Because multiple targets could exist within a tweet (e.g. company and its product) the sentiment analysis will not distinguish between differing sentiment existing between the two targets. Instead if two companies are being compared the sentiment analysis may only recognize the strongest intensity emotion of the various targets. Further another limitation is the accuracy of the emotional lexicon which may not accurately score opinion words in the sense they are actually being utilized. But regardless from this project a future direction that could be explored is the effect of Emoji utilization in business advertisements. Since these characters have been shown to hold expression and emotional intensity the analyzation of how consumers respond to advertisements utilizing Emojis compared to those that dont could reveal how Emojis could serve to improve the successful conveyance of marketing messages online.
