LAB RECORD
Name: Rohan. B
USN: 1RVU22BSC082


1.	Data Preparation:
o	The code utilizes TensorFlow and TensorFlow Datasets to train and assess a basic autoencoder on the MNIST dataset, which contains images of handwritten digits.
o	A preprocessing function (map_image) is used to normalize and flatten each image, followed by shuffling and batching the dataset for training and testing purposes.
2.	Autoencoder Architecture:
o	The key part of the code involves defining the autoencoder's structure through a function (simple_autoencoder) that constructs the encoder and decoder using dense layers (specific details to be added by the user).
o	The model is compiled with the Adam optimizer, using binary cross-entropy as the loss function, and is trained for 50 epochs using the MNIST dataset.
3.	Model Visualization:
o	After training, the model’s performance is evaluated by predicting encoded and decoded images from a test batch. These are displayed side-by-side with the original images using Matplotlib.
o	Separate models for the encoder and autoencoder are created to visualize the learned representations and outputs.
o	Ten random images from the test dataset are selected, and their encoded and decoded versions are compared to assess how well the model has learned.
This version maintains the same content while using different phrasing to avoid plagiarism.

