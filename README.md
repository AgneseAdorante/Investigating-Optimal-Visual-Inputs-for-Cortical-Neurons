# Investigating Optimal Visual Inputs for Cortical Neurons

This project explores the predictability of neuronal activity in the mouse visual cortex. By utilizing Convolutional Neural Networks (CNNs), the study models how specific visual stimuli drive neuronal responses and validates these models through the generation of Most Exciting Images (MEIs).

## 📌 Project Overview
The goal of this research is to bridge the gap between deep learning and biological vision. The project focuses on:
* **Response Prediction**: Training a CNN to accurately predict the firing rates of VISam neurons based on visual input.
* **MEI Generation**: Using gradient ascent to synthesize "Most Exciting Images" that represent the optimal stimulus for specific neurons.
* **Functional Validation**: Comparing the synthesized MEIs against known physiological properties of the visual cortex to verify the model's biological relevance.
<img width="833" height="434" alt="Screenshot 2026-04-01 125210" src="https://github.com/user-attachments/assets/1abf515e-5935-420f-8775-61a06cc9b158" />

## 🛠 Methodology
* **Data Source**: Neural recordings (calcium imaging) from the VISam region of the mouse brain during exposure to diverse visual stimuli.
* **Modeling**: A Deep Neural Network (CNN) architecture designed for spatial feature extraction.
* **Validation**: Implementation of gradient ascent techniques to visualize the features the model identifies as most influential for individual neurons.

## 🚀 Key Features
- [x] **Deep Learning Pipeline**: End-to-end training script for neuronal response modeling.
- [x] **Visualization**: Generation of MEIs to interpret model "preferences."
- [x] **Comparative Analysis**: Discussion on how predictive accuracy changes across different cortical regions.

## 📂 File Structure
* `Notebook_Group9_NeuroScience.html`: The full analysis, code, and visualizations for the project.
* `data/`: (If applicable) Directory for the neuroscience datasets.
* `src/`: Source code for the CNN architecture and MEI generation.

---

### Bibliography
Group 9. (2024). *Predicting Visual Cortex Responses with Deep Learning*. [Notebook_Group9_NeuroScience.html].
