# Explainable Deep Learning for Agricultural Crop Classification

This project explores model explainability in computer vision using GradCAM,  AblationCAM , and  ScoreCAM  to analyze a deep learning model's predictions for agricultural crops. The objective is to visualize which areas of an image the model uses to make its classification.

## Technical Details

### Dataset
The analysis uses the "Agricultural Crops Image Classification" dataset from Kaggle.
**Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/mdwaquarazam/agricultural-crops-image-classification/data)

### Pretrained Model
A  pretrained ResNet-50  model was utilized for the image classification task.

### Explainability Methods
**Techniques Used:** GradCAM, AblationCAM, and ScoreCAM.

---

## Key Findings

Visualizations (heatmaps) highlight the features the model attends to:

* **Fruit Focus:** In most cases, the model primarily attended to the fruits themselves, indicating that the presence and visual characteristics of the fruit are the primary features driving classification.
* **Vegetative Importance:** A significant observation was made with the sugarcane image, where the **stem** was highlighted as a critical feature, suggesting that vegetative parts can also be decisive for classification in certain crops.
* **Feature Exclusion:** Fruits located in the background or those that were partially obscured were generally **not attended to** by the model. they were of the same class.

*The above readme was generated using Gemini 2.5Flash on 6:01 on 10/05/2025, it was fed the assignment requirements and what I did in the jupyter notebook*
