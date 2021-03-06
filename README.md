### Project: ULMfit model to train the Twitter US Airlines sentiment and predict the airline_sentiment

#### Following steps are followed for the same.
- The stored input data in google drive is acessed and checked for the percentage of each sentiment (i.e., Positive, Negative and Neutral).
   We found that there are approximately "9178" negative sentiments, "3099" neutral sentiments, and "2363" positive sentiments.
- The data was shuffled in order to include all types of text in the training and testing phase.
- The data was then preprocessed by tokenization and replace new words into dictionary using numbers.
- The data was split into testing and training group.
- The accuracy and loss was checked before training the data.
   We found that the model has "4.108196" training loss, "3.806271" validation loss and "0.266161" accuracy rate.
- The encoders were used to train the data.
- The resultant ULMFiT model was saved and the data was applied on the training data. 
   It was found that the loss decreased and accuracy increased to following : "0.365991" training loss, '0.456449" validation loss and "0.820805" accuracy rate.
- The resultant model was applied on the testing data and found that 
   the model gave accuracy of "0.8060109289617486".
- The difference in the predicted and actual sentiments were also checked for.
