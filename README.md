# Face_recognition
Building a Streamlit App for Face_recognition of famous personal's 

## **Introduction**
This code is designed to load facial images from a dataset, and apply facial recognition to classify the images by person. Specifically, the code uses a VGG Face model to extract facial features and then uses these features to create embeddings of the faces for classification. This README will explain the code structure and provide instructions for use.

## **Dependencies**
This code requires the following packages to be installed:

- h5py
- numpy
- matplotlib
- sklearn
- opencv
- tensorflow
- Code Structure

The code is divided into two parts: loading the facial images and running the VGG Face model on them.

## **Loading Facial Images**
The load_metadata function loads facial images from a given directory, and returns an array of IdentityMetadata objects, which represent the person's identity, image name, and file path. The load_image function takes a file path and returns the image as a numpy array.

## **VGG Face Model**
The vgg_face function defines the VGG Face model, which is a convolutional neural network that takes an image as input and returns an embedding, which is a numerical representation of the image. The VGG Face model is used to create embeddings of each facial image loaded from the dataset, and these embeddings are then used for facial recognition.

## **How to Use**
### **To use this code, follow these steps:**

- Ensure all dependencies are installed.
- Download the facial image dataset and update the source_dir variable with the directory path of the dataset.
- Run the load_metadata function to load facial images from the dataset.
- Run the vgg_face function to create embeddings of the facial images.
- Use the embeddings to perform facial recognition or classification tasks.
- Train the model
- Load the the model 
- The app uses a trained Keras model to make predictions and displays the predicted class name on the app
- Run the commend ```streamlit run app.py```


## **Enjoy using the Face Recognition App!**

