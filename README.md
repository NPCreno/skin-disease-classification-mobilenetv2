# Skin Disease Classification using MobileNetV2

## 📝 Project Overview
This project implements a deep learning model for skin disease classification using the MobileNetV2 architecture. The model is designed to classify various skin conditions from dermoscopic images, which can assist in early detection and diagnosis of skin-related conditions.

## 🚀 Features
- Utilizes transfer learning with pre-trained MobileNetV2 model
- Implements data augmentation for better model generalization
- Includes model evaluation metrics and visualization
- Support for both training and inference modes
- Anomaly detection for out-of-distribution samples

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/NPCreno/skin-disease-classification-mobilenetv2.git
cd skin-disease-classification-mobilenetv2
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## 🏃‍♂️ Usage

### Training the Model
1. Organize your dataset in the following structure:
```
data/
  train/
    class1/
    class2/
    ...
  validation/
    class1/
    class2/
    ...
  test/
    class1/
    class2/
    ...
```

2. Run the training notebook:
```bash
jupyter notebook MobilenetV2_skinDisease_Final.ipynb
```

### Making Predictions
Load the trained model and use the provided functions to make predictions on new images.

## 📊 Results
(Include performance metrics, accuracy, and example predictions here)

## 📚 Dataset
(Specify the dataset used and provide a link if it's publicly available)

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
MIT License

## 📧 Contact
NPCreno - laurence.divinagracia25@gmail.com
