# Medical Deepfake Detection  

## Overview  
This repository provides a solution for detecting medical deepfake images using a YOLOv8-based detection model. The code is implemented in Python and is designed to run in **Google Colab** or any compatible environment, such as Jupyter Notebook.  

---

## Requirements and Installation  
The project is implemented in the Google Colab environment with **Python**. Ensure you have the following dependencies installed:  

- Python 3.8 or higher  
- OpenCV  
- Ultralytics (YOLOv8)  
- NumPy  
- Pandas  
- Roboflow Integration  

To install the necessary libraries, use the following command:  
```bash
pip install ultralytics roboflow opencv-python-headless

## Dataset
The dataset used in this project was created using Roboflow and can be accessed here:
Medical Deepfake Dataset

The dataset includes labeled medical images in categories such as:

Kidney CT images
Lung CT images
Brain MRI images
Breast Ultrasound images

## Inspiration
This project is inspired by the following implementations:

YOLOv8 Implementation by Ultralytics
Roboflow Example Notebooks

Run the Code
To run the code and perform medical deepfake detection, follow these steps:

Clone the Repository:
Download or clone this repository to your local environment:

git clone https://github.com/yourusername/Medical_Deepfake_Detection.git
cd Medical_Deepfake_Detection

Open the Notebook:
Open the Medical_Deepfake_Detection.ipynb file using Jupyter Notebook, Google Colab, or any compatible Python environment.

Prepare and Load Dataset:

Use the provided Roboflow link to access and download the dataset.
Ensure your dataset follows the input format with labeled images for accurate detection results.
Execute the Notebook:
Run the notebook step by step:

Preprocess the data.
Load the pre-trained YOLOv8 model.
Perform medical deepfake detection.
Analyze Results:

The model analyzes the input images and classifies them as real or fake.
Detected regions will be displayed with bounding boxes, and the results will be shown in real time.
Customization:

You can fine-tune parameters or integrate additional datasets to enhance the model's performance.

License
This project is licensed under the MIT License.

Support
For any questions or feedback, feel free to contact:
mert.cecen23@gmail.com

