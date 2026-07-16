# 🌱 EcoGuardian

EcoGuardian is an AI-powered environmental monitoring system that classifies environmental conditions from images into three categories:

- 🟢 Healthy
- 🟡 Moderate
- 🔴 Poor

In addition to classification, the project introduces an **Environmental Recovery Potential (ERP)** indicator, which estimates how recoverable an area is based on its visual condition.

---

## Project Objective

The goal of EcoGuardian is to support environmental sustainability by providing a simple AI model capable of assessing environmental conditions from images. The system can assist decision-makers in prioritizing restoration efforts and identifying areas that require immediate attention.

---

## Features

- Image classification using Deep Learning
- Three environmental condition classes
- Environmental Recovery Potential (ERP) estimation
- Easy-to-use prediction workflow
- Lightweight implementation suitable for educational projects

---

## Dataset Structure

```
dataset/
│
├── train/
│   ├── Healthy/
│   ├── Moderate/
│   └── Poor/
│
├── validation/
│   ├── Healthy/
│   ├── Moderate/
│   └── Poor/
│
└── test/
    ├── Healthy/
    ├── Moderate/
    └── Poor/
```

---

## Technologies

- Python
- TensorFlow
- Keras
- Google Colab
- NumPy
- Matplotlib

---

## Environmental Recovery Potential (ERP)

After classifying an image, the model estimates the recovery potential:

| Environmental Class | ERP |
|---------------------|-----|
| Healthy | High |
| Moderate | Medium |
| Poor | Low |

This provides additional decision support rather than only predicting a class.

---

## Project Workflow

1. Collect environmental images
2. Organize dataset
3. Train CNN model
4. Validate performance
5. Test the model
6. Predict environmental condition
7. Estimate Environmental Recovery Potential (ERP)

---

## Future Improvements

- Real-time drone image analysis
- Satellite imagery integration
- GIS support
- Automatic environmental reporting
- Mobile application deployment

---

## Vision Alignment

This project supports environmental sustainability and smart technologies aligned with **Saudi Vision 2030**, contributing to environmental protection and digital transformation.

---

## Author

**Manar**
Computer Engineering Student
