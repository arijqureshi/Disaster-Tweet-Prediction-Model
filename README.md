Arij Qureshi, Neel Patil, Sunfee Kim

Pantelis Monogioudis

CS 301

27 March 2022

Project Proposal Group 6


  The problem we will be investigating is tweets about disasters or unsafe situations. We would like to create a model to predict whether or not a certain tweet is about a disaster or not. People are looking to actively monitor twitter to respond to emergency situations, as Twitter is often used as a quick way to relay information.
  
	We will use different documentation and articles that delve into different ways of solving natural language processing problems. Some of the reading already found is based on ensemble learning algorithms, multinomial naive bayes theorem, and other methods to work on and improve our algorithm. These will be further explored as we dive deeper into the problem as well.
	
The data used will be the dataset given in the Kaggle competition we are entering. (https://www.kaggle.com/competitions/nlp-getting-started/overview/description) If we need more data we will scrape Tweets and hand classify tweets, but this may not be necessary.

  With natural language processing, our reading and interpretation of the algorithm helped us decide that the Multinomial Naive Bayes approach will be the best way to classify headlines as either a disaster or fake news. The first steps of this algorithm† will involve stemming and lemmatization of the words and making tokens of each word. Since we know the probability of a word appearing in a headline that is either fake or real,we can use conditional probability to classify if it is real or not.
  
  Our results will really be a 0 or 1 output for whether or not a certain tweet is about an actual emergency. To analyze them, we can create graphs between loss test and lost training against model complexity or other parameters within our natural language processing model. 
  
  A concept we would like to work towards is to confirm the locations/settings of the disasters if it is real. This would require additional learning algorithms and possibly setting news rules that can help us narrow down locations.
 
 Bibliography
https://www.datasciencecentral.com/top-nlp-algorithms-amp-concepts/
https://publish.tntech.edu/index.php/PSRCI/article/view/686 
https://machinelearningmastery.com/tour-of-ensemble-learning-algorithms/ 
https://www.mygreatlearning.com/blog/multinomial-naive-bayes-explained/ 

