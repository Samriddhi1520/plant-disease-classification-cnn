# 🌿 Plant Disease Classification using Transfer Learning (CNN)

## 📌 Overview

This project uses a **Transfer Learning-based CNN (MobileNetV2)** to classify plant diseases from leaf images using the PlantVillage dataset.

---

## 🎯 Objective

* Classify plant diseases from images
* Apply transfer learning using a pre-trained CNN
* Improve performance using fine-tuning

---

## 📚 Research Paper

**Title:** Using transfer learning-based plant disease classification and detection for sustainable agriculture

### Key Idea:

* Use pre-trained CNN models
* Apply fine-tuning for better accuracy

---

## 🔄 Comparison

| Feature  | Research Paper    | Our Work                        |
| -------- | ----------------- | ------------------------------- |
| Model    | Pre-trained CNN   | MobileNetV2                     |
| Approach | Transfer Learning | Transfer Learning + Fine-Tuning |
| Accuracy | ~90–95%           | **~93%**                        |

---

## 📂 Dataset

* PlantVillage Dataset (Kaggle)
* 15 classes used
* Crops: Tomato, Potato, Pepper

---

## 🧠 Model

* MobileNetV2 (pre-trained)
* Global Average Pooling
* Dense + Dropout
* Softmax Output

---

## 🚀 Training

* Phase 1: Train top layers
* Phase 2: Fine-tuning with low learning rate

---

## 📊 Results

* Accuracy: **~93%**
* Good performance across most classes

---

## 📈 Visualizations

* Accuracy & Loss Graphs
* Confusion Matrix
* Per-Class Accuracy

---

## 📦 Model Saving

```python id="1p6s9i"
model.save("/kaggle/working/final_model.keras")
```

---

## 🏁 Conclusion

Transfer learning significantly improves plant disease classification and achieves high accuracy with efficient models.
