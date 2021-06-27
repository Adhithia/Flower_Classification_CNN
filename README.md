# Flower_Classification_CNN
Classifying images of Flowers using CNN

## 1. Project Description
In this project, we will be classifying images of flowers into “roses” and “daisies”. This is a classification problem, where we will be dealing with two classes, but the complete dataset contains 5 classes.

## 2. Data Description
You can download the dataset from here: https://www.kaggle.com/alxmamaev/flowers-recognition
  * This dataset contains 4242 images of flowers. 
  * The data collection is based on the data flicr, google images, yandex images.
  * The pictures are divided into five classes: chamomile, tulip, rose, sunflower, dandelion. 
  * For each class there are about 800 photos. Photos are not high resolution, about 320x240 pixels. Photos are not reduced to a single size, they have different proportions!

## 3. Process
1. Data Preparation: 
  * Made sure all our images are of the same resolution
  * Place the images in two different folders - 'daisy' and 'rose'. This method will work for any application where you're trying to train using images.
2. Data Pre-Processing: Morphological Operations
  * Perform thresholding on the image - converted it from a grey image to a binary image.
  * Look at Erosion, Dilation, Opening, Closing.
3. Data Pre-Processing: Normalisation
  * Perform normalisation.
  * Try different methods of normalisation.
4. Data Pre-Processing: Augmentation
  * Perform data augmentation.
  * Perform different ways to augment - translation, rotation, scaling, etc.
5. Model Building
  * Run ablation experiments
  * Overfitting on a smaller version of the training set
  * Hyperparameter tuning
  * Mode training and evaluation
## 4. Running the notebook
The notebook can be downloaded along with the dataset and change the path according to yours and run it. You can change the parameters to try other models.
