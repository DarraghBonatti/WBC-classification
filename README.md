# WBC-classification
Inceptionv3_Neutrophil.ipynb

This script is designed to train on white blood cell (WBC) cutouts to classify **neutrophils** versus **non-neutrophils** using a deep learning model.

## 📁 Directory Structure

Before running the script, please organize your data as follows:

- Place all **neutrophil cutouts** inside the `Neutrophil` directory.
- Place all **non-neutrophil cutouts** inside the `NonNeutrophil` directory.
- Both folders must be inside a parent directory named `dataset`.

## 🚀 How to Run

Navigate to the directory containing both your script and the `dataset/` folder:

Run the jupyter notebook file. 


# WBC-detection
YOLO_wbc_detection.ipynb

# Using the YOLO Object Detection Model

This guide explains how to use a YOLO (You Only Look Once) object detection model to detect and locate objects in images.

## Requirements

Before using the model, ensure you have the following:

- **YOLO model weights** (`.pt` file for YOLOv8) 
- **dataset for training**
- **Annotation files** in YOLO format (`.txt` files with bounding box coordinates per image)

### 🔗 Download Annotations

To train or test the model on new images, you'll need the annotated dataset in YOLO format. You can download the annotation files here:

**[📥 Download Annotations](https://example.com/annotations-download)**  
*(Replace this with your actual link)*

Each `.txt` file should have the same name as the corresponding image file and contain one line per object with the format:


