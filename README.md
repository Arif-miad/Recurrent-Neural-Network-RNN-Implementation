# **Recurrent Neural Network (RNN) Implementation**

## **Dataset Overview**
This project utilizes a dataset containing retinal images categorized into four classes:

- **Normal**
- **Diabetic Retinopathy**
- **Cataract**
- **Glaucoma**

Each class contains approximately 1,000 images collected from various sources, including **IDRiD**, **Ocular Recognition**, and **HRF** datasets.

### **Key Dataset Features**:
- High-quality retinal images.
- Balanced data distribution across the four categories.
- Ideal for exploring classification tasks in medical imaging.

---

## **Project Objective**
The goal of this project is to implement a **Recurrent Neural Network (RNN)** to classify retinal images into their respective categories, leveraging the temporal nature of data (if any) or experimenting with how RNNs adapt to image-based tasks.

---

## **Code Implementation**

### **1. Preprocessing**
- Resizing images to a uniform dimension.
- Normalizing pixel values for faster convergence.
- Splitting data into training, validation, and testing sets.

### **2. Model Architecture**
This implementation uses an RNN-based architecture with enhancements:

- **Input Layer**: Accepts preprocessed image data.
- **Hidden Layers**: Incorporates LSTM/GRU cells to handle sequential features (if utilized).
- **Output Layer**: A fully connected layer with softmax activation for multi-class classification.

### **3. Training and Evaluation**
- **Loss Function**: Categorical Crossentropy.
- **Optimizer**: Adam optimizer for efficient gradient descent.
- **Metrics**: Accuracy and loss over epochs.

---

## **Setup Instructions**

### **Dependencies**
To run this project, ensure you have the following installed:

- Python 3.7+
- TensorFlow/Keras
- NumPy
- Matplotlib
- Pandas
- OpenCV (optional for image preprocessing)

Install the required packages using:
```bash
pip install -r requirements.txt
```

### **Steps to Run**
1. Clone this repository:
   ```bash
   git clone https://github.com/Arif-miad/RNN-Retinal-Classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd RNN-Retinal-Classification
   ```
3. Run the training script:
   ```bash
   python train_model.py
   ```

### **Output**
- Training and validation accuracy/loss curves.
- Model predictions on test data.

---

## **Results**
- Achieved an accuracy of **X%** on the test set.
- Confusion matrix and classification report to evaluate performance.
- Example predictions visualized for each category.

---

## **Project Files**

- `train_model.py`: Main script for training the RNN model.
- `data_preprocessing.py`: Script for data cleaning and preprocessing.
- `model_architecture.py`: Defines the RNN architecture.
- `requirements.txt`: List of dependencies.
- `README.md`: Documentation for the project.

---

## **Contributions**
Contributions are welcome! Please feel free to fork this repository and submit pull requests.

---

## **Connect with Me**
- **GitHub**: [github.com/Arif-miad](https://github.com/Arif-miad)
- **Kaggle**: [kaggle.com/Arif-miad](https://kaggle.com/Arif-miad)
- **LinkedIn**: [linkedin.com/in/arif-adi-8751bb217](https://www.linkedin.com/in/arif-adi-8751bb217)

---

## **License**
This project is licensed under the MIT License - see the `LICENSE` file for details.
