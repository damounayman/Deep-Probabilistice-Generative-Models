# Deep-Probabilistice-Generative-Models
In this lab we will discover the principles of a generative model and learn how to build suchmodels in neural networks.
![Taxonomy of Generative models](https://github.com/damounayman/Deep-Probabilistice-Generative-Models/images/taxonomy.png 255)
### Lab 1: Variational Auto-Encoders. 
Variational autoencoders (VAEs) are autoencoders that tackle the problem of the latent space irregularity by making the encoder return a distribution over the latent space instead of a single point and by adding in the loss function a regularisation term over that returned distribution in order to ensure a better organisation of the latent space and avoid overfitting.