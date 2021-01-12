# Cassava Leaf Disease image Classification using EfficientNet

### Overview:
In this Task, the dataset consists of 21,367 labeled images collected during a regular survey in Uganda. 
Most images were crowdsourced from farmers taking photos of their gardens, and annotated by experts at the National Crops Resources Research Institute (NaCRRI) in collaboration with the AI lab at Makerere University, Kampala.
This is in a format that most realistically represents what farmers would need to diagnose in real life.

My Task is to classify each cassava image into four disease categories or a fifth category indicating a healthy leaf. 
With your help, farmers may be able to quickly identify diseased plants, potentially saving their crops before they inflict irreparable damage.

I used EfficientNet as my Image classification model
EfficientNet:Google recently published both a very exciting paper and source code for a newly designed CNN (convolutional neural network) called EfficientNet, is a convolutional neural network architecture and scaling method that uniformly scales all dimensions of depth/width/resolution using a compound coefficient.

### Data Description:
Dataset:
To download the dataset follow this link
https://www.kaggle.com/c/cassava-leaf-disease-classification/data   

Data Files
.[train/test]_images the image files. The full set of test images will only be available to your notebook when it is submitted for scoring. Expect to see roughly 15,000 images in the test set.
.train.csv
.image_id the image file name.
.label the ID code for the disease.
.sample_submission.csv A properly formatted sample submission, given the disclosed test set content.
.image_id the image file name.
.label the predicted ID code for the disease.
.[train/test]_tfrecords the image files in tfrecord format.
.label_num_to_disease_map.json The mapping between each disease code and the real disease name.
