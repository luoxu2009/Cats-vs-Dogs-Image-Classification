# Cats-vs-Dogs-Image-Classification

### This notebook solves the image classifcation challenge of dogs vs cats with deep learning. I look at applying Convolutional NN and transfer learning (VGG16) to solve a binary image classifcation problem of dogs and cats images.

### The notebook is organized into the following sections:
 1. Build a smaller dataset from original dataset (downloaded from Kaggle)
 2. Data Preparations
 3. Basic CNN model and performance evaluation
 4. Basic CNN model with Regularization (dropout)
 5. Basic CNN model with Image Augmentation
 6. VGG transfer learning (out of box, used as feature extractor)
 7. Fine-tuned VGG transfer CNN model
   -   use augmented image data
   -   freeze first 3 Conv blocks of VGG16, while allowing 4th and 5th Conv blocks to update.
