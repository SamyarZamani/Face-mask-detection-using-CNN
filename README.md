# 😷 Face Mask Detection using CNN

This is a deep learning project using a Convolutional Neural Network (CNN) to detect whether a person is wearing a face mask or not based on image input.

## 📸 Sample Results

<p align="center">
  <img src="plots/accuracy.png" width="400" alt="Accuracy Curve">
  <img src="plots/loss.png" width="400" alt="Loss Curve">
</p>

## 🚀 Features
- Built with TensorFlow/Keras
- Real-time image augmentation using ImageDataGenerator
- Precision, Recall, and F1-score evaluation
- Confusion Matrix visualization
- Supports testing with custom uploaded images

## 🧠 Model Architecture
- 3 Conv2D + ReLU + MaxPooling layers
- Flatten → Dense(128) + Dropout(0.5)
- Output: Dense(1) with Sigmoid activation
- Optimizer: Adam | Loss: Binary Crossentropy



markdown
Copy
Edit

## ⚙️ How to Use
1. Mount Google Drive in Colab
2. Upload dataset (with two folders: `with_mask` and `without_mask`)
3. Run the notebook: `FaceMask_Detection.ipynb`
4. Train the model and test it on new images

## 📊 Evaluation
- Final validation accuracy: ~80%
- Detailed classification report included
- Confusion matrix visualized



## 🧾 License
MIT License

---





## 🎯 ویژگی‌ها
- استفاده از TensorFlow و Keras
- افزایشی‌سازی تصاویر با ImageDataGenerator
- محاسبه‌ی precision، recall و F1-score
- نمایش confusion matrix
- تست مدل با تصاویر دلخواه

## 🧠 معماری مدل
- سه لایه Conv2D + MaxPooling
- Flatten → Dense(128) + Dropout(0.5)
- لایه خروجی با Sigmoid


## 📊 نتایج
- دقت نهایی مدل: حدود 80٪
- گزارش متریک‌های ارزیابی + Confusion Matrix موجود است

---

> توسعه داده شده توسط سامیار زمانی  
> Created by [Samyar Zamani](https://github.com/SamyarZamani)
