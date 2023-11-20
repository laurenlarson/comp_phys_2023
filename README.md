# comp_phys_2023

# Using Machine Learning to Tag Particles From Collider Experiments 
Project Members: Bryan Dinh, Lauren Larson, Bryce, Josie Wright

## Project Scope

High-energy experiments have allowed physicists to probe matter to find its constituent parts. Much progress has been made over the years thanks to the advancements in particle accelerator technology, which has progressed to allow particles to accelerate to TeV energies. The data from these experiments is large and messy, making it difficult to work with. A single collision can generate many "events," which are occurrences where the accelerator's detectors are able to measure a particle resulting from the collision. These events typically occur in a chain of events, known as a jet. You can imagine a tree branch originating from the trunk, splitting off into smaller branches, and eventually terminating into leaves. The branching is a jet, and the leaves are the resulting particles from the collision. The identification and classification of these particles are important results that physicists around the world work to accomplish. The processing of this data is the primary objective of our project.

<img src=resources/collision_jet.png  width="100%"/>

*An example particle jet: A particle collision will generate particles that decay, creating a cone of particles which eventually runs into a detector, creating a grid of data points.*

Many of the particles discovered over the years have been a result of meticulous analysis of the data. With the advancement of machine learning algorithms, the detection and classification of particles have improved the data processing pipeline drastically. Our project utilizes two different machine learning algorithms: the basic gradient descent and a tree decision model. These algorithms have been commonly employed successfully in image recognition problems, so how will they work for our problem? The answer is simple; the accelerator data is its own kind of image! A standard color image has an nxmx3 shape, representing the pixels (events) and the RGB color (recorded event values). By pushing our data through this processing pipeline, we'll compare its predictions with a ground truth decided through more sophisticated methods used in the actual experiments.

## Requirements
This code was developed with python 3.11

## Packages
The following packages are required. Each package is linked to installations instructions.
+ numpy
+ matplotlib
+ tensorflow 2.13.1
+ scipy
+ scikit-learn
+ jupyter

