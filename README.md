# SCT_ML_03

# SVM Image Classifier: Cats vs Dogs

This project implements a Support Vector Machine (SVM) to classify images of cats and dogs. It processes a dataset of images, trains an SVM model, and provides a user-interactive interface to predict the category (cat or dog) of a given image.

Extracts and preprocesses images from a dataset.

Uses a linear kernel SVM for binary classification.

Interactive functionality to upload and classify new images.

Evaluates the model on a test set with metrics like accuracy.

# **Dataset**

Input: A folder containing images of cats and dogs.

For demonstration, the project uses randomly assigned labels to simulate a classification task.

Images are resized to a fixed dimension (64x64 pixels) and converted to grayscale.


# **Preprocessing**

Resizes all images to 64x64 pixels.

Converts images to grayscale.

Flattens image data into feature vectors for training.

# **Model Training**

Splits the dataset into training (80%) and testing (20%) subsets.

Trains an SVM model using a linear kernel.

Evaluates the model using accuracy and classification reports.

# **Interactive Prediction**

Users can upload an image to the model for prediction. The image will be processed and classified as either a "Cat" or "Dog."

**How to Use**

Prerequisites

Ensure you have Python 3.8+ and the following libraries installed:

numpy

scikit-learn

Pillow

matplotlib


# **License**

This project is licensed under the MIT License. See the LICENSE file for details.

