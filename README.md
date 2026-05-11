# Passport-Verification-System-
Passport Verification  System 

# Passport Verification System 🛂

## Project Idea
An AI-based system that verifies passport images using OCR, image processing, and deep learning to detect whether a passport is real or fake.

---

# Features

- OCR text extraction from passport images
- Image analysis using CNN
- Forgery detection using ELA (Error Level Analysis)
- Classification result:
  - Real Passport
  - Fake Passport
- User-friendly interface (Gradio)
- Image upload and real-time prediction

---

# System Workflow

1. Upload passport image
2. Extract text using OCR (Tesseract)
3. Process image using CNN model
4. Apply ELA features for forgery detection
5. Combine results
6. Output final prediction (Real / Fake)

---

# Dataset Structure

```text id="dataset_structure"
passport_dataset/
│
├── train/
│   ├── real/
│   └── fake/
│
└── test/
    ├── real/
    └── fake/
```

---

# Tools & Technologies

## AI Model
- TensorFlow
- Keras
- CNN (Convolutional Neural Network)

## Image Processing
- PIL (Pillow)
- NumPy

## OCR
- Tesseract OCR

## UI
- Gradio

## Environment
- Google Colab
- Jupyter Notebook
- Google Drive

---

# Model Output

The system predicts:

- 🟢 Real Passport → High authenticity probability
- 🔴 Fake Passport → Suspicious manipulation detected

---

# Problems Faced & Solutions

## ❌ FileNotFoundError
**Cause:** Wrong file path or missing folder  
**Solution:** Use:
```python
os.path.exists("path")
```

---

## ❌ No images found
**Cause:** Empty or unorganized dataset  
**Solution:** Ensure structure:

```text id="fix_structure"
train/
  real/
  fake/
```

---

# Final Result

✔ Detects passport authenticity  
✔ Uses AI + OCR + Image Forensics  
✔ Fast prediction  
✔ Supports real-world security use cases  

---

# Summary
This project combines computer vision, deep learning, and OCR to build an intelligent passport verification system that helps detect fake documents efficiently and accurately.
