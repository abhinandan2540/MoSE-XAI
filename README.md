# **MoSE-XAI**

This project implements a modified **MobileNetV2 architecture** enhanced with a **Squeeze-and-Excitation (SE) block** to improve feature recalibration and model performance in crop disease detection for **soybean** and **sugarcane**.
To ensure transparency and interpretability, the model integrates **Explainable AI (XAI)** techniques using **Grad-CAM** for visual explanation of predictions.

---

## **Features**

* **MobileNetV2 Architecture**
  Lightweight and efficient convolutional neural network designed for mobile and embedded vision applications.

* **Squeeze-and-Excitation (SE) Block**
  Enhances channel-wise attention by adaptively recalibrating feature responses.

* **Explainable AI (Grad-CAM)**
  Generates heatmaps to visualize which regions of the input image influence the model’s decision.

---

## **Model Architecture Overview**

* Backbone model: **MobileNetV2**
* Added module: **Squeeze-and-Excitation (SE) block**
* XAI method: **Grad-CAM**
* Goal: Crop disease detection with **visual explainability**

---

## **Dataset**

To train MoSE model, the author used 3 different datasets
* sugarcane leaf image dataset
* sugarcane leaf disease dataset
* soynet: indian soybean image dataset

All datas are collected from [Mendeley Data](https://data.mendeley.com/).

---

## **Author**

Abhinadan Mandal

[Linkedin](https://www.linkedin.com/in/abhinandan-mandal-9252a0211/)

[Medium](https://medium.com/@writewithabhi)

