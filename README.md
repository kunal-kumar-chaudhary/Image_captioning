# Image_captioning
Image Captioning using encoder-decoder based model


* VGG16 model has been used for featrue extraction for image data and the extracted features have been combined with word embedding vectors and has been feed into LSTM layer.

* here LSTM layer works as decoder and VGG16 along with embedding layer works as encoder which has been used to convert image and words into feature vectors.

* flicker_8k open sourced dataset has been used for model training

* model has been trained upon google colab's Tesla T4 GPU for 5 epochs due to limitation of capable computation resources

* data has been preprocessed and accordingly molded into the shape for feedind the model as input
