# Brain Tumor Classification

Classifies brain MRI images into four categories (glioma, meningioma, no tumor, pituitary) using:
- Simple CNN
- CNN + LSTM (patch-based, TimeDistributed)
- CNN + GRU (patch-based, TimeDistributed)

The notebook includes preprocessing, augmentation, hyperparameter tuning (Keras Tuner), training and evaluation.

## Dataset
Place the dataset in this structure:

Brain_Tumor/
├── Training/
│   ├── glioma/
│   ├── meningioma/
│   ├── notumor/
│   └── pituitary/
└── Testing/
    ├── glioma/
    ├── meningioma/
    ├── notumor/
    └── pituitary/

## Files
- Brain_tumor.ipynb — main notebook  
- requirements.txt — dependencies  
- .gitignore — ignored files  
- assets/ — training curves, tuner results, sample images.

## Notes
Uses TensorFlow/Keras, Keras Tuner, patch extraction, ImageDataGenerator and TimeDistributed models.
