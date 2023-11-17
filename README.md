# Lung-Segmentation 🫁

## Introduction
This project focuses on the application of U-Net, a convolutional neural network, for segmenting lung masks in chest X-rays. Utilizing the "Chest Xray Masks and Labels" dataset from Kaggle, this project aims to enhance the accuracy and efficiency of lung mask segmentation, which is crucial in medical image analysis.

## Dataset Description
The "Chest Xray Masks and Labels" dataset from Kaggle comprises 7047 high-resolution chest X-ray images (1024x1024 pixels) and corresponding expert-annotated lung masks. The images are in DICOM format, a standard for medical imaging, with mask annotations in PNG format. The dataset is pre-divided into training, validation, and test sets, facilitating the development and evaluation of segmentation models. Sourced from the "Shenzhen Hospital X-ray set" and the "Montgomery County X-ray set," this dataset is an excellent resource for deep learning applications in medical imaging, particularly for lung segmentation tasks. The dataset is available under a CC0: Public Domain license, allowing unrestricted use.

## Environment and Dependencies
To run this project, the following environment and dependencies are required:
- Python 3.x
- Libraries: NumPy, Pandas, Matplotlib, TensorFlow, Keras
- Jupyter Notebook

## Installation Guide
1. Clone the project repository (if hosted on a platform like GitHub).
2. Install the required dependencies using `pip install -r requirements.txt` (assuming a requirements file is provided).

## File Structure
- `gather_dataset.ipynb`: Notebook for gathering and preprocessing the dataset.
- `LungSeg_Final.ipynb`: Main notebook containing the U-Net model implementation and training process.

## Usage Instructions
To use this project:
1. Run `gather_dataset.ipynb` to preprocess the dataset.
2. Execute `LungSeg_Final.ipynb` to train the U-Net model and perform lung segmentation on the X-ray images.

## Acknowledgments
Special thanks to the creators of the "Chest Xray Masks and Labels" dataset on Kaggle, particularly Nikhil Pandey, and all those who contributed to the development of the U-Net architecture.
