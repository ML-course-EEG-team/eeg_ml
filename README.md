# EEG Image Classification with Convolutional Neural Network

This project involves preprocessing EEG data and training a Convolutional Neural Network (CNN) for image classification. The project aims to classify EEG data into different categories by converting the EEG data into grayscale images and training a CNN on these images.

## Project Structure

The project consists of the following main components:

- **EEG Data Preprocessing**: Converts EEG data from EDF files into grayscale images.
- **CNN Model Training**: Trains a Convolutional Neural Network on the preprocessed images for binary classification.

## File Structure

- **`export_pictures.py`**: Contains code for loading, preprocessing EEG data, and exporting images.
- **`model_binary.py`**: Contains code for defining, compiling, and training the CNN model.

## Training Data Source

https://www.physionet.org/content/eegmmidb/1.0.0/

## Prerequisites

Make sure you have Python installed, along with the necessary packages. You can install the required packages using:

```bash
pip install tensorflow mne pandas numpy matplotlib seaborn

## Presentation Link

https://github.com/ML-course-EEG-team/eeg_ml/blob/main/4_presentation/opencampus_presentation.pptx

## Members

Joshua El-Samalouti
Abidur Rahman
Puliyampatta Anil Sasikumar Menon
