## Project Overview

In this project, you'll define and train a DCGAN on a dataset of faces. Your goal is to get a generator network to generate new images of faces that look as realistic as possible!

The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, you'll be able to visualize the results of your trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.

### Get the Data
You'll be using the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train your adversarial networks.

This dataset is more complex than the number datasets (like MNIST or SVHN) you've been working with, and so, you should prepare to define deeper networks and train them for a longer time to get good results. It is suggested that you utilize a GPU for training.

# Goal
Generate new faces using Generative Adversarial Networks (GANs).  
The model is trained on the CelebFaces Attributes Dataset (CelebA):
![Image of Training Set](https://github.com/tfesenko/Face-Generation/blob/master/assets/processed_face_data.png)

It generates new human faces that look like this:  
![Image of Generated Faces](https://github.com/tfesenko/Face-Generation/blob/master/assets/Generated_faces2.png)

## Recommended next steps
* Create a deeper model and use it to generate larger (say 128x128) images of faces.
* Read existing literature to see if you can use padding and normalization techniques to generate higher-resolution images.
* Implement a learning rate that evolves over time as they did in this [CycleGAN Github repo](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix).
* See if you can extend this model and use a CycleGAN to learn to swap different kinds of faces. For example, learn a mapping between faces that have and do not have eye/lip makeup, as they did in [this paper](https://gfx.cs.princeton.edu/pubs/Chang_2018_PAS/Chang-CVPR-2018.pdf).
