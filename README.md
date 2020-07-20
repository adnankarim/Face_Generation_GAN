## Project Overview

In this project, I defined and train a DCGAN on a dataset of faces. Goal was to get a generator network to generate new images of faces that look as realistic as possible!

### Getting the Data
Here is link to the Data [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train adversarial networks.

This dataset is more complex than the number datasets (like MNIST or SVHN), and so, I  prepared to define deeper networks and train them for a longer time to get good results.I utilized a GPU for training.

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
