Image Classification Project: Cats vs. Dogs using PyTorch
This repository contains the implementation of an image classification project focused on distinguishing between images of cats and dogs using PyTorch. The project employs a ResNet-18 model,
fine-tuned for binary classification, and uses PyTorch's torchvision library for loading and transforming image data. The dataset, Kaggle Cats vs. Dogs, includes labeled images organized into training_set and 
test_set directories, with subfolders for each class. The code is structured to handle data preprocessing (including resizing, normalization, and augmentation), model training, evaluation, and inference. 
To train the model, run train.py with an SGD optimizer and Cross Entropy Loss; test accuracy can be checked with test.py. Additionally, inference.py allows classification of new images.
The model checkpointing utility saves the best-performing model, which can be reloaded for inference. This project is ideal for those looking to explore transfer learning and deep learning model fine-tuning for 
image classification tasks.

link for dataset: https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification
