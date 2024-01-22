# Cartridge Case Image Analysis Project

## Project Overview
This project focuses on the analysis of cartridge case images using advanced machine learning techniques. Our goal is to automate the identification and segmentation of forensic features in cartridge case images, which can significantly aid forensic investigations.

## Features
- Feature extraction using VGG16 model
- Image clustering and outlier detection for efficient annotation
- Manual annotation of images using Roboflow
- Data augmentation to enhance model training
- Model training with Detectron2 for feature detection and segmentation
- Model evaluation and analysis

## Dataset
The dataset comprises 2625 topographic scans of breech face impressions on fired cartridge case primers. It is used for training, testing, and validating the machine learning model. Due to the large size of the dataset, we employed data augmentation techniques and carefully split the dataset into training, testing, and validation sets.

[Dataset Link](https://iastate.figshare.com/articles/dataset/Topographic_Scans_of_Breech_Face_Impressions_on_Cartridge_Case_Primers/23837100?file=42400335)

Using the Roboflow tool the dataset has been annotated and augmented to enhance the training process of our machine learning model.

[Annotated and Augmented Dataset Link](https://github.com/jinoAlgon/Cartridge-Case-Image-Analysis-Project/blob/main/masking_catridge-2.zip)

## Installation and Usage
1. Clone the repository: git clone https://github.com/jinoAlgon/Cartridge-Case-Image-Analysis-Project.git
2. Run the Jupyter Notebook: Automatically_Masking_Cartridge_Case_Images.ipynb

## Tools and Technologies Used
- Python
- Roboflow
- Detectron2
- PyTorch
- OpenCV
- Google Colab

## Model Training and Evaluation
The project uses Detectron2 for model training. We trained a Mask R-CNN model to detect and segment the relevant features from the cartridge case images. The model's performance was evaluated using standard metrics like Average Precision (AP) and Average Recall (AR).

## References
- [Thermodynamics Analysis of A Novel Designation of Renewable Energy Systems](https://espace2.etsmtl.ca/id/eprint/27282/1/Duong-L-2023-27282.pdf)
- [How to Cluster Images Based on Visual Similarity](https://towardsdatascience.com/how-to-cluster-images-based-on-visual-similarity-cd6e7209fe34)
- [Detectron2 Documentation](https://detectron2.readthedocs.io/en/latest/tutorials/training.html)
