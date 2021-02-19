# Deep-learning-examples
**Deep Learning models with baseline approach and also using pretrained models (VGG-16) for better accuracy.**

## Binary Classification with CNN.
### 1. Cats vs Dogs Classification (Without using Pretrained Model:
https://github.com/umairiqbal78/Deep-learning-examples/blob/master/New_practise_Dogs_and_Cats_my_work.ipynb

### 2. Cats vs Dogs Classification (With Pretrained model (VGG-16):
https://github.com/umairiqbal78/Deep-learning-examples/blob/master/new_using_pre_trained_model_on_cats_and_dogs.ipynb

### 3. Beautiful_and_average_datasets.
This Dataset was of images with labels as beautiful and average. So I trained a model on these images which can binary classify these images and predict for unseen image as beautiful or average image.

**Source Code for Beautiful-vs-Average Dataset.**
https://github.com/umairiqbal78/Deep-learning-examples/blob/master/Beautiful_and_average_datasets.ipynb

**Predictions from Beatiful-vs-Average Dataset.**
https://github.com/umairiqbal78/Deep-learning-examples/blob/master/Predictions_on_Beautiful_vs_avg.ipynb

### 4. Spoon-vs-Fork
The spoon and fork identification model build by me with using several techniques:
1. Firstly I just build a baseline model with the orignal dataset of just 576 photos. Overall accuracy was 80% but validation accuracy was not more than 50%.
2. Then I augmented the data and create images from existing images. Then I have about 3198 images on which I trained my model and validate it in 100 images. Accuracy down 64% and validation accuracy is about 56%.
3. Then I modify my model with several layers of Conv2d, Maxpool and dropout layer. Now the overall accuracy is upto 96% and validation accuracy is about 98%.

**Prediction test is also done in the last of the note book.**
https://github.com/umairiqbal78/Deep-learning-examples/blob/master/spoon_vs_knife.ipynb

### 5. Celebrity Identifier Dataset.
The dataset include pictures of 5 celebrities. My work on this dataset is given bellow.
https://github.com/umairiqbal78/Deep-learning-examples/blob/master/Celebrity_CNN_my_practise.ipynb

**Prediction from the Celebrity model is**
https://github.com/umairiqbal78/Deep-learning-examples/blob/master/prediction_on_celebrity.ipynb

### 6. Umair-vs-Salman 
This is completely end to end project done by me. Dataset include pictures of my friend and of myself.
I augmented the picture and create more dataset from the few images. This model attain an accuracy of 86% which is quite good with this dataset. 

**Dataset link**
https://drive.google.com/drive/folders/1mtfREfVR2p1LTu1dE27GxYx85NwPp-PL?usp=sharing

**Source Code**
https://github.com/umairiqbal78/Deep-learning-examples/blob/master/umair_vs_salman_cnn_practise.ipynb

**Prediction on model**
https://github.com/umairiqbal78/Deep-learning-examples/blob/master/prediction_on_umair_vs_salman.ipynb

### 7. IMDB Movie Dataset
It classify the movie reviews as negative or positive review.
https://github.com/umairiqbal78/Deep-learning-examples/blob/master/IMDB_movie_review_with_change(3_hidden_layer)%20.ipynb

