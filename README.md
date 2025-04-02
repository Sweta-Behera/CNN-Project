# MNIST Handwritten Digit Recognizer using CNN

## Overview
This project implements a **Convolutional Neural Network (CNN)** to classify handwritten digits from the **MNIST dataset**. It automates digit recognition for applications like banking, postal services, and document processing.

## Features
- **Deep CNN Model** for high accuracy
- **Data Augmentation** for improved generalization
- **Automated Feature Extraction** via convolutional layers
- **Performance Analysis** using learning curves and confusion matrices

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/MNIST-Handwritten-Digit-Recognizer.git
   cd MNIST-Handwritten-Digit-Recognizer
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Training & Evaluation
Train the model:
```sh
python train.py
```
Evaluate performance:
```sh
python test.py
```

## Usage
Predict a digit from an image:
```python
from src.model import predict_digit
result = predict_digit("path/to/image.png")
print(f"Predicted Digit: {result}")
```

## Results
- High classification accuracy
- Robust against handwriting variations
- Effective for real-world applications

## Future Enhancements
- Expand to other handwritten character datasets
- Optimize with transfer learning
- Deploy as a web-based API
