# Denoising

Deep Learning model for chest Xray image denoising using CycleGAN

The model uses a Pix2Pix model to train the CycleGAN. 

The model imports a set of images from the system. Then it adds random noise to it and use a descriminator and generator to denoise the images.

The images used are from this link: https://www.kaggle.com/datasets/tolgadincer/labeled-chest-xray-images
