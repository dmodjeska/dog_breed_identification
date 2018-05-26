## Introduction

During the period September 2017 - February 2018, Kaggle held a competition called Dog Breed Identification. The goal was to categorize the breed of a dog from an image, with data from ImageNet courtesy of the Stanford Dogs Dataset. A full description of this competition is below. 

We took two approaches to this challenge: a feed-forward neural network (FFNN) using TensorFlow, and a Convolutional Neural Network (CNN) using Keras based on the VGG16 pre-trained model. For both approaches we used image augmentation, such as sharpening, rotation, and warping. 

## Description of Competition (from Kaggle Site)

Who's a good dog? Who likes ear scratches? Well, it seems those fancy deep neural networks don't have all the answers. However, maybe they can answer that ubiquitous question we all ask when meeting a four-legged stranger: what kind of good pup is that?

In this playground competition, you are provided a strictly canine subset of ImageNet in order to practice fine-grained image categorization. How well you can tell your Norfolk Terriers from your Norwich Terriers? With 120 breeds of dogs and a limited number training images per class, you might find the problem more, err, ruff than you anticipated.

## Code

* [Feed Forward Neural Network (FFNN)](https://github.com/dmodjeska/dog_breed_identification/blob/master/HW4_AML71_Modjeska_Murphy_FFNN.ipynb)
* [Convolutional Neural Network (CCNN)](https://github.com/dmodjeska/dog_breed_identification/blob/master/HW4_AML71_Modjeska_Murphy_CNN.ipynb)
