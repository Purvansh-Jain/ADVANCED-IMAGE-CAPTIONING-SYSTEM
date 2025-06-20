# Show and Tell v23

## Introduction
"Show and Tell v23" leverages cutting-edge machine learning techniques to bridge the gap between visual content and natural language, creating a system capable of generating descriptive captions for images. This project integrates advanced CNNs for image processing and RNNs or Transformer-based models for text generation, tested and validated on the comprehensive MSCOCO dataset. Our findings demonstrate significant advancements in automated image captioning, offering promising applications in enhancing accessibility, search functionality, and user interaction.

## Team Members
- Purvansh Jain
- Santnam Bakshi
- Rishi Ghia

## Dataset
The MSCOCO dataset, utilized for this project, is a large-scale dataset for object detection, segmentation, and captioning. Approximately 25GB in size, it is pre-split into training, validation, and test sets, making it ideal for developing and testing machine learning models focused on image captioning. The dataset includes images with multiple captions provided by human annotators, offering rich data for training our models.

Train Data (118k images): http://images.cocodataset.org/zips/train2017.zip

Val Data (5k images):     http://images.cocodataset.org/zips/val2017.zip

Test Data (41k images):   http://images.cocodataset.org/zips/val2017.zip

## Technologies Used
The project was developed using Python, with TensorFlow/Keras and PyTorch as the main libraries for implementing the machine learning models. Attention mechanisms and image augmentation techniques were pivotal in enhancing the model's performance.

## Features
- Implementation of CNN for image feature extraction.
- Use of RNN and Transformer-based models for generating captions.
- Integration of attention mechanisms to focus on relevant parts of images.
- Exploration of image augmentation to improve model robustness.

## Setup and Installation
Instructions for setting up the project, including dependencies and prerequisites, are detailed in the project's documentation. This includes steps for installing necessary libraries, downloading the MSCOCO dataset, and preparing the environment for running the models.

## Usage
The project documentation provides comprehensive guidance on using the system to generate captions for new images. This includes examples and command line instructions for running the model inference scripts.

## Results
Our improvements in BLEU scores and other metrics highlight the model's effectiveness in generating contextually relevant and accurate image captions. The detailed results section discusses these findings and compares the model's performance across different configurations and training setups.

## Contributions
This project is a collaborative effort between Purvansh Jain, Santnam Bakshi, Kavish Shah and Rishi Ghia. Contributions from the wider community are welcome, and we thank all those who have provided feedback, data, and support.

