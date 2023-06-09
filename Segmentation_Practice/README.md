# Semantic Segmentation Practice

### Project description
Binary semantic segmentation (classification of image pixels as background or foreground) based on the [Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/). The Kaggle version of this project [is here](https://www.kaggle.com/code/dkudryavtsev/segmentation-practice).

### The case    

* semantic segmentation with the MobileNetV3-based LRASPP model
* fine-tuning of the model
* batch IOU computation
* visualisation of the images with masks
* training with PyTorch Ligtning

**Skillfactory requirements:**  
* IOU > 0.7 between the ground truth and predicted masks

### The data
The [Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/) (also available [on Kaggle](https://www.kaggle.com/datasets/julinmaloof/the-oxfordiiit-pet-dataset)).
  
### Results
The model is fine-tuned to IOU ~ 0.9.