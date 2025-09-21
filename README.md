# Missing-Child-Identification
Overview

This project implements a Missing Child Identification System using deep learning and face recognition techniques to assist in locating missing children in India. The system leverages a Convolutional Neural Network (CNN) based on the VGG-Face architecture for feature extraction and a K-Nearest Neighbors (KNN) classifier for matching facial images. The public can upload photos of suspected missing children to a portal, which are then compared against a database of missing children's images to identify potential matches. This system aims to support authorities and parents in tracing missing children efficiently.


Features

Face Recognition: Utilizes VGG-Face CNN model for extracting facial features and KNN for classification.

National Portal: A centralized platform where police officers can upload missing children's details and photos, and the public can submit photos of suspected children.

Automated Matching: Automatically compares uploaded images with the missing children database and alerts authorities upon finding a match.

Robustness: Handles variations in lighting, noise, image pose, occlusion, and age differences for reliable identification.
User Interface: Includes login, registration, data addition, and data viewing functionalities.
Security: Ensures secure access for system administrators to prevent misuse.


System Architecture

The system consists of:

Database: Stores details and photos of missing children reported by police officers.

Public Upload Portal: Allows the public to upload photos of suspected children with details like location, time, and remarks.

Preprocessing Module: Standardizes and crops face regions from images for compatibility with the CNN model.

Feature Extraction: Uses VGG-Face CNN to extract high-level facial features.

Classification: Employs a KNN classifier to match uploaded images with the database.

Notification System: Sends alerts to concerned officers via email or portal messages when a match is found.


Requirements

Hardware Requirements

Processor: Any modern processor

RAM: Minimum 4 GB

Hard Disk: Minimum 100 GB

Software Requirements

Operating System: Windows family

Technology: Python 3.6

IDE: PyCharm

Libraries:

TensorFlow or PyTorch (for CNN implementation)

MatConvNet (optional, for VGG-Face model)

OpenCV (for image preprocessing)

Scikit-learn (for KNN classifier)
