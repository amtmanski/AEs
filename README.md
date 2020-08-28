# AEs

## Simple_AE.ipynb
The file consist of two models - one made with convolutional layers and the other one is linear with ReLU activations.

Linear:
![Linear AE results](imgs/Linear_AE.png)
Conv:
![Conv AE results](imgs/Conv_AE.png)

## Denoising_AE.ipynb
It works the same as linear but noisy inputs are compared to images without noise
![original image](imgs/DAEOriginal.png)
![noise added](imgs/DAENoised.png)
![reconstructed](imgs/DAEReconstructed.png)

## VAE.ipynb
Variational Autoencoder 
Encoder and decoder layers are linear. Generated images by this VAE are shown below
![generated images](imgs/generated_imgs.png)
