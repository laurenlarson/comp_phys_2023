# comp_phys_2023
# Machine Learning Project in fulfillment of PHYS 396K final project
Project Members: Bryan Dinh, Lauren Larson, Bryce, Josie Wright

## Project Scope
High energy experiments have allowed physicist to probe matter to find its constituent parts. Much progress has been made over the years thanks to the advancements that have been made in particle acclerator technology which has progressed to allow particles to accelerate to TeV energies. The data from these experiments are large and messy, making them difficult to work with. A sigle collission can generate many "events" which are occurances where the accelerator's detectors are able to measure a particle which results from the collision. These events typically occur from a chain of events, typically known as a jet. You can imagine a tree branch which originates from the trunck and splits off into smaller branches and eventually terminates into leaves. The branching is a jet and the leaves are the resulting particles from the collision. The identification and classification of these particles are important results which phycisist around the world work to accomplish. The processing of this data is the primary objective of our project. 

<img src=RESOURCES/Collision_Jet.png  width="100%"/>

*An example particle jet. A particle collision will generate particles which decay, making a cone of particles which eventually run into a detector that creates a grid of data proints*

Many of the particles discovered over the years have been a result of meticulous analysis of the data. With the advancement of machine learning algorithms, the detection and classification of particles has improved the data proccessing pipeline darastically. Our project uses two different machine learning algorithms, the basic gradient decent and a tree decision model. These algorithms are commonly employed successfully in image recognition problems so how will they work for our problem? The answer is simple, the accelerator data is its own kind of image! A standard color image has an NxMx3 shape, representing the pixels (events) and the RGB color (recorded event values).




