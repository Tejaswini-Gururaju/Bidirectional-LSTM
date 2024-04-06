# Bidirectional-LSTM

In this project I have taken a dataset with 2 labels basically classifying if an artical has fake news or genuine ones. 
* I have preprocessed the data by dropping the least priority features and applying stopwords,padding and more.
* Once the data is ready for training I have built a sequential model with one hidden layer and used Bi-Directional LSTM to memorize the important key points.
* Once the model is ready I have trained my data with "Adan" optimizer to update the weights and "Sigmoid" activation function since it has 2 target labels.
* Once the model is trained, few evaluation tasks are performed based on "binary_crossentropy".
* Conclusion : Model accuracy is 90%
* Key points : we can add drop out layers to reduce the accuracy amd make the model more robust.
