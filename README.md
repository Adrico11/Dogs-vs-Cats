## Image Classification : Dogs and Cats

### Goal :
The purpose of this laboratory is to build a first end to end reflex-based AI model to teach computers to understand images. The final objective of this laboratory is to be aware to the potential but also to the limitations of reflex-based AI approaches towards visual recognition tasks.

### Libraries used :
- OpenCV
- Imutils to fetch data
- Scikit Learn to train models

### Three approaches will be used to adress this problem :
  1. A basic ML model to serve as a baseline 
  2. A traditional pattern recognition model in which hand-crafted features are extracted from images and used to represent them and to train classifiers.
  3. A modern representation learning approach in which deep convolutional neural networks (CNN) are used to learn the image representations :
	- Building a CNN from scratch using Keras
	- Fine tuning the output layer of a pretrained VGG16 model
