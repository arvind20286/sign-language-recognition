# Sign Language Recognition

This project detects sign language gestures using Python, OpenCV, and MediaPipe. It collects hand gesture images, creates datasets, trains a classifier, and runs real-time gesture detection.

## 🧠 Features

- 📸 Collect hand gesture images
- 🗂️ Create labeled datasets
- 🏋️ Train a custom classifier
- 🔍 Real-time gesture prediction

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

### 1. Collect Images

Run the script to collect gesture images:

```bash
python collect_imgs.py
```

### 2. Create Dataset

Convert images to training-ready data:

```bash
python create_dataset.py
```

### 3. Train Model

Train your gesture recognition model:

```bash
python train_classifier.py
```

### 4. Run Inference

Start real-time gesture detection:

```bash
python inference_classifier.py
```

## 🗃️ Folder Structure

```
├── collect_imgs.py
├── create_dataset.py
├── train_classifier.py
├── inference_classifier.py
├── dataset/
├── images/
├── model/
└── requirements.txt
```
