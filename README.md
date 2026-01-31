# Computer Vision Practicals

This repository contains two comprehensive computer vision practicals using deep learning techniques with TensorFlow/Keras.

## 📚 Contents

### Practical 1: CNN from Scratch (CIFAR-10)
Build a Convolutional Neural Network from scratch to classify images from the CIFAR-10 dataset.

**File**: `Practical_1_CNN_from_Scratch_CIFAR10.ipynb`

**Topics Covered**:
- Loading and preprocessing CIFAR-10 dataset
- Building CNN architecture from scratch
- Convolutional layers, pooling, batch normalization, and dropout
- Training with callbacks (early stopping, learning rate reduction)
- Model evaluation and visualization
- Confusion matrix and classification report

**Dataset**: CIFAR-10 (60,000 32x32 color images in 10 classes)

### Practical 2: Transfer Learning (Cats vs Dogs - MobileNetV2)
Use transfer learning with pre-trained MobileNetV2 to classify images of cats and dogs.

**File**: `Practical_2_Transfer_Learning_Cats_vs_Dogs.ipynb`

**Topics Covered**:
- Transfer learning fundamentals
- Using pre-trained MobileNetV2 model
- Data augmentation techniques
- Two-stage training (frozen base + fine-tuning)
- Binary classification
- Model evaluation and performance metrics

**Dataset**: Cats vs Dogs (filtered dataset from Google)

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/vicky-ssingh/CNN.git
cd CNN
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open either notebook and run the cells sequentially.

## 📦 Requirements

All required packages are listed in `requirements.txt`:
- tensorflow>=2.10.0
- numpy>=1.21.0
- matplotlib>=3.5.0
- jupyter>=1.0.0
- notebook>=6.4.0
- pillow>=9.0.0
- scikit-learn>=1.0.0
- seaborn>=0.11.0

## 📊 Key Learning Outcomes

### After completing these practicals, you will understand:

1. **Deep Learning Fundamentals**:
   - Convolutional Neural Networks (CNNs)
   - Activation functions (ReLU, Softmax, Sigmoid)
   - Loss functions (Categorical/Binary Crossentropy)
   - Optimizers (Adam)

2. **CNN Architecture**:
   - Convolutional layers for feature extraction
   - Pooling layers for dimensionality reduction
   - Batch normalization for training stability
   - Dropout for regularization

3. **Transfer Learning**:
   - Using pre-trained models (MobileNetV2)
   - Feature extraction vs fine-tuning
   - Two-stage training strategy
   - Adapting models for new tasks

4. **Data Processing**:
   - Image normalization
   - One-hot encoding
   - Data augmentation (rotation, flip, zoom, etc.)
   - Train/validation split

5. **Model Evaluation**:
   - Accuracy metrics
   - Confusion matrix
   - Classification report (precision, recall, F1-score)
   - Training/validation curves

## 📝 Notes

- Both notebooks are **beginner-friendly** and **step-by-step**
- Each step includes detailed explanations
- Code is well-commented and **exam-ready**
- Visualizations help understand the results
- Models can be saved for future use (optional sections included)

## 🎯 Expected Performance

### Practical 1 (CNN from Scratch - CIFAR-10):
- Training typically achieves 70-80% accuracy
- Test accuracy around 70-75%
- Training time: 10-20 minutes (depends on hardware)

### Practical 2 (Transfer Learning - Cats vs Dogs):
- Training typically achieves 95-98% accuracy
- Validation accuracy around 95-97%
- Training time: 5-15 minutes (depends on hardware)
- Fine-tuning further improves performance

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements!

## 📄 License

This project is open source and available for educational purposes.

## 👤 Author

**Vicky S Singh**

---

**Note**: These notebooks are designed for educational purposes and are suitable for:
- Computer Vision courses
- Deep Learning assignments
- Exam preparation
- Self-study and practice
