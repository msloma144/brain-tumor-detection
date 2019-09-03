# Brain MRI Images for Brain Tumor Detection
## Image Augmentation and Deep Learning (CNN)

The Brain MRI Images for Brain Tumor Detection dataset contains two types of data, tumorous and non-tumorous. 

First we perform image augmentation using keras's ImageDataGenerator function to increse the variance of our data and to increse the number of samples. We also attempt to correct for any class imbalances in the data by generating additonal tumorous samples. We then first crop the images by finding extreme points in the contours and then resize the data. Finally, we use a convolutional neural network to attempt to classify if an image is tumorous or non-tumorous.

## Author
Michael Sloma

## Data Sources
* [Kaggle](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)


**Note:** sometimes IPython notebooks on GitHub don't work as expected, but you can always view them using [nbviewer](https://nbviewer.jupyter.org/).


