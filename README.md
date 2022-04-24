# Disaster-Tweet-Prediction-Model
A model to predict whether or not tweets are about emergency situations. For Kaggle Competition (https://www.kaggle.com/competitions/nlp-getting-started/overview/description)

# How to Run the Colab Notebook

If you are trying to replicate the results that we had from our implementation of the MNNB model, you must have a Kaggle account set up and authenticated. Enter the [Kaggle competition](https://www.kaggle.com/competitions/nlp-getting-started/overview) and make sure your phone number is verified with your kaggle account.

Then, make your own copy of the Colab notebook, and start a new runtime. Ideally, don't use a GPU, as this only slowed down the runtime for our model. Upload your kaggle.json file to the files tab on the left. Then, you should just be able to hit *Run All* underneath the Runtime tab at the top. So long as the kaggle authentication worked, everything else should run smoothly.

If you are trying to play around with some of the parameters involved in the model, you can do so under the final section titled **Optimal Run of Model**. The model is created as follows:


```
nb = NaiveBayes(labels, Laplace Smoothing Constant, Number of Synonyms per Tweet)
```

Feel free to play around with the parameters and mess with some of the class creation as well. If you would like to edit preprocessing and things like that, just change the methods within the section **Creating the Naive Bayes Model** accordingly. Have fun experimenting!
