# comp_phys_2023

# Using Machine Learning to Tag Particles From Collider Experiments 
Project Members: Bryan Dinh, Lauren Larson, Bryce, Josie Wright

## Project Scope

High-energy experiments have allowed physicists to probe matter to find its constituent parts. Much progress has been made over the years thanks to the advancements in particle accelerator technology, which has progressed to allow particles to accelerate to TeV energies. The data from these experiments is large and messy, making it difficult to work with. A single collision can generate many "events," which are occurrences where the accelerator's detectors are able to measure a particle resulting from the collision. These events typically occur in a chain of events, known as a jet. You can imagine a tree branch originating from the trunk, splitting off into smaller branches, and eventually terminating into leaves. The branching is a jet, and the leaves are the resulting particles from the collision. The identification and classification of these particles are important results that physicists around the world work to accomplish. The processing of this data is the primary objective of our project.

<img src=RESOURCES/Collision_Jet.png  width="100%"/>

*An example particle jet: A particle collision will generate particles that decay, creating a cone of particles which eventually runs into a detector, creating a grid of data points.*

Many of the particles discovered over the years have been a result of meticulous analysis of the data. With the advancement of machine learning (ML) algorithms, the detection and classification of particles have improved the data processing pipeline drastically. Our project utilizes two different ML algorithms: the basic gradient descent and a tree decision model. These algorithms have been commonly employed successfully in image recognition problems, so how will they work for our problem? The answer is simple; the accelerator data is its own kind of image! A standard color image has an nxmx3 shape, representing the pixels (events) and the RGB color (recorded event values). By pushing our data through this processing pipeline, we'll compare its predictions with a ground truth decided through more sophisticated methods used in the actual experiments.

## Machine Learning Model

The pipeline for ML involves sending your data through a series of matrices, also known as layers, which transform your input space to an output space. This output space can me a vector or a single scalar value. In the case of classification problems, it would be the former, and in the case of prediction problems such as ours, we would have the latter. The task of our training models is to find the value of the matricies. We use two different approaches: 
1. Gradient Descent - finds a way to minimize a loss function which describes how far off you are from the correct answer provided by the training data. We use the keras and sci-kit learn packages to implement this technique
2. Decision Tree - make decisions similar to a human thought process. It takes a dataset and looks at the information avaliable and narrows down the possible values until it comes to a conclusion. 

## Requirements
This code was developed with python 3.11

### Packages
The following packages are required. Each package is linked to installations instructions.
+ [numpy](https://numpy.org/install/)
+ [pandas](https://pandas.pydata.org/docs/getting_started/install.html)
+ [keras](https://pypi.org/project/keras/)
+ [scikit-learn](https://scikit-learn.org/stable/install.html)
+ [jupyter notebook](https://jupyter.org/install)

