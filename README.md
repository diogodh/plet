## Pulse Oximetry Plethysmographic Curve Detector

This repository contains two Google Colab Notebook files designed for use with a GPU instance on Google Colab (https://colab.research.google.com/):

- **Diogo_plet_object_detector.ipynb:** This notebook was utilized to create and test the model for detecting pulse oximetry plethysmographic curves.
- **Diogo_plet_detect.ipynb:** Specifically for testing the trained model.

### Project Overview

The primary objective of this project was to leverage artificial intelligence to identify pulse oximetry plethysmographic curves (commonly known as saturation curves) from images displayed on a monitor. A dataset comprising approximately 110 images was employed, with 80% used for training and 20% for testing. The dataset was manually labeled using LabelImg in Pascal XML notation. Subsequently, Roboflow (https://roboflow.com/) was employed to convert the annotations to COCO json format.

### Usage

To get started, open the provided Colab Notebook files in Google Colab with GPU support. Follow the instructions within each notebook for training the model and testing its performance on pulse oximetry plethysmographic curve images.

Feel free to explore and contribute to the development of this pulse oximetry detection project. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.

Happy coding!
