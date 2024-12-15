# Medical_deepfake_detection
# Requirements and Installation
The repository was written in Google Colab environment using Python

Dataset:

The dataset created in Roboflow, located at https://universe.roboflow.com/medical-ltrhr/medical-1h7wy, was used.

Inspired from :

YOLOv8 implementation : https://github.com/ultralytics/ultralytics
                      : https://github.com/roboflow/notebooks

# Run Code
To run the code and perform medical deepfake detection, follow these steps:

Open the Medical_Deepfake_Detection.ipynb file using Jupyter Notebook or any compatible environment.
Prepare and load your own dataset following the required input format. Ensure the dataset includes labeled images for accurate detection results.
Execute the notebook step by step to preprocess the data, load the pre-trained YOLOv8 model, and perform the detection process.
The model will analyze the input images and classify them as real or fake, displaying the detection results along with bounding boxes for identified regions.
You can further customize the parameters or integrate additional datasets to enhance performance.

