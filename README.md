# ImgCaption-DL
A supervised learning model using MLPs, CNNs, RNNs, Transfer Learning, Word Embeddings.
A supervised model using MLPs, CNNs, RNNs, Transfer Learning, etc. We have used a dataset with images with their respective captions. Using ResNet50, a pre-trained deep CNN to extract our images to feature vectors. And also, Glove for processing our image descriptions to embedding layer. Finally, image features are feeded to a Dense layer (MLP implementation in Keras), text features are passed through the embedding layer to LSTM. Then we combined both features into one matrix and passed to Dense layers to output probabilities over entire vocabulary size.

### The output results are in the ipynb project
