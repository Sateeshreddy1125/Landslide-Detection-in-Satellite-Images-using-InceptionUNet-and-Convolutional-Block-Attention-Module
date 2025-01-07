# Landslide-Detection-in-Satellite-Images-using-InceptionUNet-and-Convolutional-Block-Attention-Module
<br>
In the contemporary world, Landslides pose huge risks to communities and infrastructure globally. One of the 
reasons it occurs is due to slope movement caused by urbanization and climate change in recent years. Landslide 
Detection Systems (LDS) are an evolving technology that is very crucial for handling the impacts of these natural 
disasters. It is essential for detecting and monitoring landslide occurrences across diverse terrains. This paper aims 
to propose one such automated Landslide Detection System based on the novel idea of integrating InceptionU-Net 
and Convolutional Block attention module that can efficiently detect landslides in satellite imagery using a 
benchmark dataset called LandSlide4Sense.  The motive is to determine the most effective methods by training them 
on huge amounts of data which enhances accuracy and ensure quick detection and response. Deep Learning 
techniques like U-Net, ResUNet, U-Net++, InceptionU-Net, Inception, DenseUNet, and U2Net are utilized and an 
additional contribution is made using attention mechanisms on these models. After testing these models on the test 
data and comparing the models using metrices such as Loss, Accuracy, F-score, IOU, Precision, and Recall. With a 
particular emphasis on F-score and IOU, it was found that the Inception-UNet model integrated with attention 
mechanisms proves to perform the best with the highest Fscore of 72.8% and IOU of around 60%. Through this 
research, the advancements in DL-based semantic segmentation for satellite imagery analysis are highlighted. 

# Abstract

In the contemporary world, landslides pose huge risks to communities and infrastructure globally. One of the reasons it occurs is due to slope movement caused by urbanization and climate change in recent years. Landslide Detection Systems (LDS) are an evolving technology crucial for handling the impacts of these natural disasters. It is essential for detecting and monitoring landslide occurrences across diverse terrains.

This project proposes an automated Landslide Detection System based on the novel idea of integrating InceptionU-Net and a Convolutional Block Attention Module (CBAM) that can efficiently detect landslides in satellite imagery using a benchmark dataset called LandSlide4Sense. The objective is to determine the most effective methods by training models on large datasets to enhance accuracy and ensure quick detection and response.

Deep Learning techniques like U-Net, ResUNet, U-Net++, InceptionU-Net, DenseUNet, and U2Net are utilized, with additional contributions made using attention mechanisms on these models. After testing and comparing these models using metrics such as Loss, Accuracy, F-score, IOU, Precision, and Recall, it was found that the Inception-UNet model integrated with attention mechanisms performed the best, achieving an F-score of 72.8% and an IOU of approximately 60%.

# Project Title

Landslide Detection System (LDS) Using Deep Learning Models with Attention Mechanisms

# Description

The Landslide Detection System (LDS) is a deep learning-based solution designed to detect and monitor landslide occurrences from satellite imagery. This project focuses on semantic segmentation of landslide-prone regions using various state-of-the-art deep learning models. By integrating attention mechanisms with Inception U-Net, the system effectively enhances the model's capability to focus on the most relevant features in the imagery, leading to improved detection performance.

# Features

Multiple Deep Learning Models: Implements U-Net, ResUNet, U-Net++, Inception U-Net, DenseUNet, and U2Net architectures.

Attention Mechanisms: Incorporates Convolutional Block Attention Module (CBAM) to improve feature extraction.

Benchmark Dataset: Uses the LandSlide4Sense dataset for training and testing.

Comprehensive Evaluation: Evaluates models using various metrics, including Loss, Accuracy, F-score, IOU, Precision, and Recall.

Best Model Identification: Identifies Inception U-Net with attention mechanisms as the best performing model.

# Technologies Used

Programming Language: Python

Deep Learning Frameworks: TensorFlow, Keras, PyTorch

Libraries: NumPy, Pandas, Matplotlib, OpenCV, Scikit-Learn

Dataset: LandSlide4Sense (satellite imagery dataset)
