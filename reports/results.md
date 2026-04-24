# Handwritten Digit Recognition Report

## Experimental Setup
- Dataset: MNIST
- Libraries: scikit-learn, TensorFlow/Keras
- Train/Test split: 60,000 / 10,000
- Hardware: CPU-based training

---

## Models Description

### Logistic Regression
- Linear model used as baseline
- Fast but limited for complex patterns

### k-NN
- Distance-based model
- High accuracy but slow for large datasets

### SVM
- Uses kernel trick (RBF/linear)
- Effective in high-dimensional space

### CNN
- Captures spatial features
- Best performance for image data

---

## Hyperparameter Tuning
- k-NN: tested k = 3,5,7
- SVM: tuned C and kernel
- Random Forest: number of trees
- CNN: epochs, batch size

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Training time
- Prediction time

---

## PCA Analysis
- Reduced 784 → lower dimensions
- Improved computation speed
- Slight trade-off with accuracy

---

## Discussion
- CNN performs best due to spatial feature learning
- k-NN is accurate but computationally expensive
- PCA improves efficiency for classical models
- Trade-off between speed and accuracy observed

---

## Limitations
- Limited hyperparameter tuning
- MNIST is simple dataset
- No GPU acceleration
- Limited real-world testing

---

## Future Work
- Use CIFAR-10 dataset
- Apply data augmentation
- Optimize CNN architecture
- Deploy model as application
