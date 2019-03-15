# Flower_classification

AI algorithms will be incorporated into more and more everyday applications. For example, you might want to include an image classifier in a smart phone app. To do this, you'd use a deep learning model trained on hundreds of thousands of images as part of the overall application architecture. A large part of software development in the future will be using these types of models as common parts of applications.

In this project, i trained an image classifier to recognize different species of flowers. You can imagine using something like this in a phone app that tells you the name of the flower your camera is looking at. In practice you'd train this classifier, then export it for use in your application. We'll be using this dataset of 102 flower categories, you can see a few examples below.

<img src='pytorch_challenge-image-classification/assets/Flowers.png' width=500px>

# Getting Started
 ### Data
  The data set contains images of flowers from 102 different species. The provided images were split into a training set and a   validation set. You can [download the images from here](https://s3.amazonaws.com/content.udacity-data.com/courses/nd188/flower_data.zip). Just uncompress it and you should be good to go.

### Prerequisites

* Python 3.
* Numpy 
* Pandas
* MatPlotLib
* OpenCv
* Pytorch. 

## Project Instruction

### Instructions
1. Clone the repository and navigate to the downloaded folder.
	```	
	git clone https://github.com/shyamStarwalt/Flower_classification.git
	
	```
2. Download and Install Anaconda [from here](https://www.anaconda.com/)

3. Install the above packages mentioned in the Prerequisites (Anaconda Prompt)

4. Open the cloned repository and navigate to

	```
	cd pytorch_challenge-image-classification
	```
5. Open the Image_Classifier_Project.ipynb
	```
	jupyter notebook Image_Classifier_Project.ipynb	
	```
6. Read and follow the instructions! This repository doesn't include any dataset you need. You can check out the getting started to download them.

## Project Information

### Contents

- Intro
- Step 0: Import Datasets
- Step 1: Detect Flower Species
- Step 2: Detect others
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Write Your Algorithm
- Step 6: Test Your Algorithm

## Losses

### Model scratch:
Training loss: 3.508 ... Validation loss: 0.127

### Transfer model:
Training loss: 1.141 ... Validation loss: 0.021 

### Accuracy:

### Model scratch:
Accuracy : 14%

### Transfer model:
Accuracy : 76%
