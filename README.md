# How to execute this project

1. First download the code file from the repository
2. Open the file into Google Colab Notebook
3. Download the dataset and place it in Google Drive for path in code
4. Execute the code

Thank you for checking out my code!


# Image-Colorization-Using-GANs
Deep Learning Project

# Introduction of Project

A Deep Learning project for image colorization using generative adversarial networks.

Image colorization is an emerging topic and a fascinating area of research in recent years. 
I implemented deep learning algorithms to colorize black and white images. 
Generative adversarial network (GAN) has been implemented on black and white images.
The project aim to convert the black and white images to their respective color format.
The color format used for the implementation of the networks is RGB color space.
The performance of the implemented generative adversarial network is measured using mean absolute error. 
The colorization performance of the generative adversarial network is better then the other models.

# Understanding Generative Adversarial Networks
![image](https://github.com/AdilAhmedunar/Image-Colorization-Using-GANs/assets/38765754/a82a3946-ef3e-45e9-97d6-6333d428e4f9)

# Dataset Used
I downloaded the Dataset (201 Mb) from  https://www.kaggle.com/theblackmamba31/landscape-image-colorization. This dataset consists of streets, buildings, mountains, glaciers, trees, etc. Their corresponding grayscale image is in two different folders. 

           1. Color – 7128 images – Used only 2200
           2. Grey – 7128 images  - Used only 2200
           
It is used for the implementation of networks consisting of 7000 images in the RGB color space.   Original size 150*150 but resized to 256*256 in the project. The main objective of creating this dataset is to create an autoencoder network that can colorize grayscale landscape images.

# Tools Utilized in Project

         1. Python 3.12.0 
         2. Google Colab
         
 # Challenges
1. Finding suitable Dataset 
2. Resource limitation on Google Colab
3. Coding Complexity
