# 🐶🐾 dog-breed-identification 
Dog Breed Identification using MobileNetV2 and Transfer Learning on the Kaggle dataset.



## 📌 Overview

This project aims to classify dog breeds from images using MobileNetV2 and Transfer Learning.
The model is trained on the Kaggle Dog Breed Identification dataset, which contains 120 dog breeds and over 10,000 labeled training images.

The project includes:
* Data preprocessing
* Transfer learning with MobileNetV2
* Model training and evaluation
* Visualization of predictions
* Single image prediction

## 🚀 Model Features

- *Base Model:* MobileNetV2 (pretrained on ImageNet)  
- *Image Size:* 224 × 224  
- *Optimizer:* Adam  
- *Loss:* Categorical Crossentropy  
- *Final Activation:* Softmax (120 classes)  
- *Metrics:* Accuracy, Log Loss  
- *Callbacks:* EarlyStopping, TensorBoard  
 


## 📊 Results


| *Category*            | *Metric*            | *Value*   |
|-------------------------|------------------------|-------------|
| Overall Training    | Training Accuracy      | 99.86%  |
|                         | Training Loss          | 0.0132  |
| Validation (1000 img) | Validation Accuracy    | 73.00%  |
|                         | Validation Loss        | 1.125  |
                     
Kaggle Log Loss: 0.62883                                    


## 📂 Project Structure

```
.
├── notebooks/
│   └── dog_breed_identification.ipynb
│
├── saved_models/
│   └── 1000-images-mobilenetv2.keras
│   └── full-image-set-mobilenetv2.keras
│
├── examples/
│   ├── sample1.jpg
│
├── requirements.txt
└── README.md
```


## 📥 Dataset

Kaggle Competition:
🔗 https://www.kaggle.com/competitions/dog-breed-identification
