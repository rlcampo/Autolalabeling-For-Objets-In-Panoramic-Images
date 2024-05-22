# Automatic-Object-Labeling-Method-in-Panoramic-Images
## Project Overview
Our method for automatically labeling objects in panoramic images leverages advanced computer vision techniques to classify objects in urban and road environments. By minimizing human intervention, we streamline the image analysis process, making it more efficient and scalable. This project is built using PyTorch, a powerful open-source machine learning library, enabling us to implement state-of-the-art models and achieve high accuracy in object detection and classification tasks.

![image](https://github.com/rlcampo/Autolalabeling-For-Objets-In-Panoramic-Images/assets/110200669/88c17a45-5388-4dd1-a801-55ac482b83dd)
![image](https://github.com/rlcampo/Autolalabeling-For-Objets-In-Panoramic-Images/assets/110200669/026c4614-bbd5-4992-a826-7645cce7a89b)

This photograph used in the readme of this project comes from SpyroSoft

## Main Features
**-Automated Labeling:** Significantly reduces the need for manual intervention by automating the labeling of objects in panoramic images, enhancing productivity and consistency.

**-State-of-the-Art Computer Vision:** Implements advanced techniques such as transfer learning and fine-tuning to achieve high accuracy in object classification.

**-High Efficiency and Precision:** Focuses on optimizing both efficiency and precision in detecting and identifying objects within urban and traffic settings, ensuring reliable performance.

**-Robust Training Framework:** Utilizes renowned models like YOLOv8 and Fast R-CNN, leveraging their strengths for comprehensive training and fine-tuning of the detection algorithms.

## Project Block Diagram
Certainly! Here is a project block diagram for an automated object labeling system using YOLOv8 and Fast R-CNN with PyTorch:

![image](https://github.com/rlcampo/Autolalabeling-For-Objets-In-Panoramic-Images/assets/110200669/40c49131-579b-4af1-a526-251018a7f740)

# Method Results with YOLOv8:

![image](https://github.com/rlcampo/Autolalabeling-For-Objets-In-Panoramic-Images/assets/110200669/91903c7b-3ec3-4b37-a3b7-32464115e193)
![image](https://github.com/rlcampo/Autolalabeling-For-Objets-In-Panoramic-Images/assets/110200669/f9638a95-36bb-48d7-ab1e-ce4886c581e5)


Here you can add a description of the results obtained using YOLOv8.

## Method Results with Fast R-CNN
![image](https://github.com/rlcampo/Autolalabeling-For-Objets-In-Panoramic-Images/assets/110200669/dcebb787-f0de-406c-9c79-7780dde52110)
![image](https://github.com/rlcampo/Autolalabeling-For-Objets-In-Panoramic-Images/assets/110200669/1d005b5d-8f5b-412e-9184-853982f2da63)

Once the automatic object labeling method is implemented and trained using Fast R-CNN, it is imperative to conduct extensive testing to evaluate its performance and accuracy. These tests are classified into unit tests and end-to-end tests, allowing evaluation at both component and system levels.

Unit testing involves shorter training cycles and small data sets, allowing for meticulous analysis of how the model interprets and processes the data. This scrutiny is essential to perfect the code and understand the results obtained. Instead, comprehensive tests are performed on larger data sets and across multiple training epochs. The goal is to subject the model to various scenarios, ranging from ideal conditions to challenging environments, to measure its proficiency in detecting and labeling various objects in urban and road environments.

Throughout these tests, it is common to find initial uncertainty in the inference process of the Fast R-CNN model. This uncertainty often arises from overfitting, where the model fits closely to the training data, hindering its ability to generalize effectively to new instances. To mitigate this, strategies such as model retraining, hyperparameter optimization, and improving the quality and quantity of training data are essential. These measures facilitate performance optimization and improve the model's ability to generalize.

Although experimental, the combination of Fast R-CNN with reinforcement learning techniques has shown remarkable effectiveness in quickly generating predictions and labeling objects. As data collection techniques and algorithmic advances advance, the performance of these models is expected to see significant improvements. Continued exploration of novel techniques and methodologies is imperative to drive even further advances in automatic labeling of objects in images. Let us not forget to emphasize that this is a complete design but in certain parts it is experimental and as technologies advance we will be able to improve the implementation of data for more adverse situations.

## Project Structure

The project is structured as follows:

**Dataset:** Contains a collection of pre-labeled images intended for retraining models. It also allows for the input of updated data, enabling continuous improvement and increased accuracy of the models over time.
**Data:** This folder is the designated location for adding the panoramic images to be used in the project.
**TrainModels:** Includes the implementation of two distinct machine learning methods for labeling panoramic images: YOLOv8 and Fast R-CNN.
**requirements_fast.txt:** Lists the dependencies required for running the Fast R-CNN code.
**requirements_yolo.txt:** Lists the dependencies required for running the YOLOv8 code.

## Installation and Use

1. Clone this repository: git clone https://github.com/Matt190209/Automatic-Object-Labeling-Method-in-Panoramic-Images.git

2. Install the project dependencies: pip install -r requirements_fast/yolo.txt

3. Run the code: python algo.py

4. Review the generated labels and if necessary, re-execute the code modifying the hyperparameters

## Contribution
If you want to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: git checkout -b new-feature.
3. Make your changes and commit: git commit -m "Add new functionality."
4. Push to the branch: git push origin new-feature.
5. Send a pull request.

## Image Credits ##
- Photos taken from: SpyroSoft
- Database taken from: Mappillary

**Credits**

**Project members:**

This project was developed by Robinson Luis Campo Charris, Matthieu Navarro Chamucero.

**Adviser:**

PhD. Juan Carlos Velez Diaz
