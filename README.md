# Image Classification Project with TensorFlow

This project, implemented in the `Classification_d_image.ipynb` file, uses TensorFlow to create a Convolutional Neural Network (CNN) model for classifying images from the MNIST dataset. The model is then evaluated and saved for subsequent predictions on new images.

# Usage Guide

1. **Virtual Environment**: It is recommended to create a virtual environment before running the project. You can do so using the following command:

   ```bash
   python -m venv venv
   ```
## Install Dependencies
Ensure that you install the dependencies using the following command:

   ```bash
   pip install tensorflow matplotlib pillow
   ```
## Run the Notebook
Open the **`Classification_d_image.ipynb`** file in a Jupyter Notebook environment and execute the cells sequentially.

## Predictions on New Images
To make predictions on new images, follow the instructions in the "Prediction of a New Image" section of the notebook by adjusting the image path.

## Model Saving
If you want to save the model in a format other than HDF5, you can use the native Keras format by modifying the save command in the last cell of the notebook.

# Project Structure

The project structure is as follows:

**`Classification_d_image.ipynb`**: The main project file containing code, comments, and results.   
**`Images_to_predict/`**: Folder containing images for which the model will make predictions.
