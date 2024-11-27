# **MNIST Model Optimization**  

This notebook explores optimization techniques for training a machine learning model on the MNIST dataset. It aims to improve model performance through fine-tuning, hyperparameter optimization, and efficient training practices.

### **Key Features**  

1. **Dataset Overview**:  
   - Uses the MNIST dataset (handwritten digits) for classification.  
   - Data preprocessing steps, including normalization and reshaping.  

2. **Baseline Model**:  
   - A simple neural network is trained as the baseline.  
   - Includes initial metrics and areas for improvement.  

3. **Optimization Techniques**:  
   - **Hyperparameter tuning**: Optimizing learning rates, batch sizes, and epochs.  
   - **Regularization**: Adding dropout layers and weight decay.  
   - **Advanced optimizers**: Comparison of optimizers like Adam, SGD, and RMSProp.  

4. **Model Evaluation**:  
   - Analyzes training/validation accuracy and loss curves.  
   - Confusion matrix and classification report for performance evaluation.  

5. **Results Comparison**:  
   - Compares the baseline and optimized models.  
   - Highlights the improvements achieved through optimization.

### **Outcomes**
   | Total params | Accuracy & Loss |
   | ------------ | --------------- |
   | 93,322       | accuracy: `0.9979` - loss: `0.0071`|
   | 72,842       | accuracy: `0.9976` - loss: `0.0071`|
   | 4,034       | accuracy: `0.9627` - loss: `0.1115`|

   ➡️ First 2 rows: The accuracy value is too close, but the distance between parameters is very high.
   
### **Objective**  
To demonstrate how thoughtful optimization techniques can significantly enhance the performance of a deep learning model on the MNIST dataset.

### **How to Use**  
1. Clone the repository or download the notebook.  
2. Ensure required libraries (e.g., TensorFlow, Keras, Matplotlib) are installed.  
3. Run the notebook step-by-step to:  
   - Train the baseline model.  
   - Apply optimization techniques.  
   - Evaluate and compare the results.  

### **Contributions**  
Feel free to contribute by suggesting or implementing additional optimization techniques or improvements to the model.
