# text-genre-classifier
Classify any text into various genres based on the plot summary of the text

## The model is trained and tested on the following dataset
http://www.cs.cmu.edu/~ark/personas/

## The model was again ran on IMDB movie dataset to test accuracy
https://www.kaggle.com/PromptCloudHQ/imdb-data


Sample Predictions
```
Movie:  An Arcadian Maid 
Predicted genre:  [('Romance Film',)]
Actual genre:  ['Short Film', 'Drama'] 

Movie:  Saw V 
Predicted genre:  [('Horror', 'Thriller')]
Actual genre:  ['Thriller', 'Crime Fiction', 'Horror', 'Psychological thriller', 'Cult', 'Slasher']

Movie:  Back Stage 
Predicted genre:  [('Comedy',)]
Actual genre:  ['Short Film', 'Silent film', 'Indie', 'Black-and-white', 'Comedy'] 

Movie:  Black Samurai 
Predicted genre:  [('Action',)]
Actual genre:  ['Crime Fiction', 'Action/Adventure', 'Blaxploitation', 'Martial Arts Film', 'Action', 'Spy'] 

Movie:  The Goodbye Girl 
Predicted genre:  [('Comedy', 'Drama', 'Romance Film')]
Actual genre:  ['Romantic comedy', 'Romance Film', 'Drama', 'Comedy', 'New Hollywood'] 

Movie:  A Secret 
Predicted genre:  [('Drama',)]
Actual genre:  ['Drama', 'World cinema'] 
```
# Desclaimer 
The threshold value is set to 0.5
Predictions with less than 0.5 accuracy won't be detected
