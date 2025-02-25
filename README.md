# Calculation of Learning Assessment Metrics

## **About the Project**
The **Calculation of Learning Assessment Metrics** project aims to evaluate the performance of machine learning models using various classification metrics. It calculates Sensitivity (Recall), Accuracy, Precision, F1-Score, and generates a **Confusion Matrix** and **ROC Curve** to analyze the model's performance.

This project is implemented in **Google Colab** and follows the standard evaluation metrics used in supervised learning algorithms.

## **Model and Dataset**
- **Dataset**: Confusion Matrix simulation based on model predictions.
- **Model**: Pre-trained classification model (e.g., Cats vs. Dogs).
- **Framework**: TensorFlow / Keras.
- **Objective**: Calculate key classification metrics and analyze the model's performance.
- **Environment**: Google Colab.

## **Project Structure**

📁 data/               # Contains sample data and test images
📁 notebooks/          # Jupyter Notebooks with the metric calculations
📁 models/             # Trained models and saved weights.
📄 README.md           # Project documentation (this file)


## Download the Pre-trained Model

Due to GitHub's file size limits, the trained model is hosted on Google Drive. You can download it from the link below:

**[Download modelo_treinado.keras](https://drive.google.com/file/d/1dJ1l0xfFzXnR-7zjWKbD71WM8tGxVQQ6/view?usp=sharing)**

After downloading, place the file in the `./models/` folder.

## **Installation**
To set up the project, follow these steps:

```bash
git clone https://github.com/your-repository/Calculation-of-Learning-Assessment-Metrics.git
cd Calculation-of-Learning-Assessment-Metrics
```

## **Implemented Metrics**
The project calculates the following evaluation metrics:

### **Sensitivity (Recall)**  

![image](https://github.com/user-attachments/assets/c1b9344b-9465-43ea-8ae4-a63d307868b9)


- Measures the ability to correctly classify positive samples.

### **Accuracy**  

![image](https://github.com/user-attachments/assets/82977eb1-92b4-4f50-9838-b70c2bb132ea)

- Measures overall correctness of the model.

### **Precision**  

![image](https://github.com/user-attachments/assets/cbb028e4-2d46-494b-919e-ea97ed8e0271)

- Measures how many predicted positives are actually correct.

### **F1-Score**  

![image](https://github.com/user-attachments/assets/72bd6994-c381-48ce-a75b-948f23cf636d)

- Harmonic mean of Precision and Recall.

### **Confusion Matrix**
- A table used to evaluate the performance of the classification model.

<img src="https://github.com/user-attachments/assets/9476a377-c298-45cd-a715-a198f0b5eafd" width="600"/>

### **ROC Curve**
- Graphically represents the trade-off between sensitivity and specificity.
- 
<img src="https://github.com/user-attachments/assets/e54d12f0-3b64-4d49-a764-ce544f0e5ea7" width="600"/>

## **Problems Faced and Solutions**
 **Data Imbalance**  
- Balanced the dataset by ensuring equal representation of classes.  

 **Misclassification of Certain Classes**  
- Fine-tuned the model and adjusted the decision threshold.

 **Threshold Selection in Binarization**  
- Experimented with different thresholds to optimize performance.

 **Variations in Accuracy Across Datasets**  
- Conducted multiple tests with different datasets to assess generalization.

## **Technologies Used**
- **TensorFlow/Keras**: For model evaluation and metric calculations.
- **Matplotlib**: For visualizing training metrics and ROC curves.
- **NumPy**: For handling array computations.
- **Scikit-learn**: For generating the confusion matrix and ROC curve.
- **Google Colab**: Cloud-based environment for execution with GPU support.

## **Contributions**
If you want to contribute, follow these steps:

**Fork** the repository.  
**Create a new branch**:
```bash
git checkout -b feature-new-metric
```
**Commit your changes**:
```bash
git commit -m "Added a new evaluation metric"
```
**Push your changes**:
```bash
git push origin feature-new-metric
```
**Open a Pull Request**.

## **📜 License**
This project is licensed under the **MIT License**.
