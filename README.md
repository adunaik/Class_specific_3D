# Class_specific_3D - Single View Image to 3D Point Cloud Reconstruction

# Introduction
This project focuses on reconstructing 3D point clouds from single-view RGB images, specifically within the chair class of the ShapeNet rendered dataset. The objective was to generate accurate 3D point clouds from 2D images using two different architectures, each with its own strengths in terms of latent space manipulation and control over the output.

PCA + AutoEncoder: Used to manipulate the parameters of learned latent vector towards generating 3D point clouds, but did not allow conditoned generation.
Conditional Variational Auto Encoder : Used to obtain conditoned 3D point clouds by conditoning one hot encoded vector in the latent space.
