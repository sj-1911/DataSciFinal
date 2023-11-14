# Automated Livestock Harvesting With AlexNet
### Spencer Jackson


<img src="Screenshot 2023-11-07 163750.png" width="750" height="250">

## Project Description

This research project employs the AlexNet image processing code to differentiate photos of empty chicken coops verses chicken coops with eggs or other miscellanious items. This program, when paired with a sensor or a "smart" coop or feeder can be used to completley automate the harvesting and processing of poultry.
## Key Objectives

-  In this project, we aim to leverage AlexNet for image differentiation, specifically to enhance its utility in conjunction with a sensor system. Our primary focus is to employ AlexNet's capabilities for distinguishing between various images, with the ultimate goal of optimizing its performance in sensor-related applications. Additionally, we are dedicated to gaining a comprehensive understanding of AlexNet's versatility and its potential as a highly beneficial tool. This research venture is driven by the mission to harness the power of deep learning and convolutional neural networks to contribute to the field of automated livestock harvesting.

## Methodology

We will employ the following methodologies to achieve our research goals:

- ### Colab and AlexNet
   * To achieve our goal of differentiating images effectively, we have adopted a methodology that involves leveraging the power of AlexNet, a deep convolutional neural network. In our workflow, we utilize Google Colab, a user-friendly platform that facilitates Python programming and allows us to run the necessary AlexNet program. Google Colab offers a convenient and efficient environment for implementing this machine learning model, ensuring the seamless execution of image differentiation tasks.
   * Our approach includes testing the AlexNet program on a dataset consisting of 25 images of an empty chicken coop and 25 images of a full chicken coop. This testing process is integral to enabling the program to learn and differentiate between the two types of images accurately. By training on this dataset, AlexNet will become adept at recognizing and distinguishing the visual distinctions that exist between these scenarios, contributing to our overall goal of enhanced image differentiation.
- ### Understanding AlexNet
   * AlexNet is a pioneering deep learning architecture renowned for its proficiency in image classification tasks. Comprising multiple convolutional layers, it operates by learning intricate features from input images and subsequently making accurate predictions. By utilizing a combination of convolutional layers, rectified linear unit (ReLU) activations, and max-pooling, AlexNet excels at recognizing patterns, edges, and textures in images, ultimately achieving superior accuracy in image classification. Its robust architecture has significantly advanced the field of computer vision and has applications across various domains, from image recognition to object detection.
  <img src="https://miro.medium.com/v2/resize:fit:1400/1*bD_DMBtKwveuzIkQTwjKQQ.png" width="750" height="250">

## Colab Notebooks
-[Data Slides Deck](https://colab.research.google.com/drive/1EhMEL-Xnl5bkMBiz3lgOLendAbR261Fd?usp=sharing)
  * The AlexNet program processes images from a Google Slides presentation. It resizes the images and utilizes a feature map to enhance our understanding of the distinguishing characteristics among these images.

-[Formulas for Data Science](https://colab.research.google.com/drive/1518fgS6H1n42yVluJURPwXE-oD7sU5Sr?usp=sharing)
  * This Colab snippet utilizes the Matplotlib and NumPy libraries to create and visualize sine wave signals. It demonstrates the generation of sine waves with varying parameters, such as frequency and duration, and includes audio playback functionality for the generated signals.


## Data Deck

- Here are a few examples from the input data:

  <img src="https://pastaonthefloor.com/wp-content/uploads/2018/08/Empty-bird-nest-on-white-background-499643337_730x482.jpeg" width="250" height="250"> <!-- Adjust image source accordingly -->
  <img src="https://previews.123rf.com/images/2002lubava1981/2002lubava19811603/2002lubava1981160300073/53467728-empty-birds-nest-isolated-on-white-background.jpg" width="250" height="250"> <!-- Adjust image source accordingly -->
  <img src="https://d2gg9evh47fn9z.cloudfront.net/800px_COLOURBOX2663984.jpg" width="250" height="250"> <!-- Adjust image source accordingly -->

  * **Versus**

  <img src="https://c8.alamy.com/comp/EJH2W0/chicken-eggs-in-nest-of-straw-EJH2W0.jpg" width="250" height="250"> <!-- Adjust image source accordingly -->
  <img src="https://c8.alamy.com/comp/RNGTKD/top-view-of-chicken-eggs-in-a-nest-on-a-white-background-RNGTKD.jpg" width="250" height="250"> <!-- Adjust image source accordingly -->
  <img src="https://static.vecteezy.com/system/resources/previews/003/406/386/large_2x/chicken-eggs-in-the-nest-isolated-on-a-white-background-free-photo.jpeg" width="250" height="250"> <!-- Adjust image source accordingly -->

## WANDB System run
  <img src="Screenshot 2023-11-14 160117.png" width="750" height="250">
  - Wanb (Weights & Biases) trial run involves leveraging the platform to log and visualize machine learning experiments. Researchers and data scientists use Wanb to track and compare model performance metrics, hyperparameters, and other experiment details in a collaborative and organized manner.
