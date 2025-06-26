
# 👗 CNN Fashion Classifier

A Convolutional Neural Network (CNN) built using TensorFlow to classify images of fashion items from the Fashion-MNIST dataset into 10 categories such as shirts, sneakers, bags, and more.

---

## 🚀 Features

- Built using **TensorFlow** and **Keras**
- Image **data augmentation** for better generalization
- **Dropout layers** to reduce overfitting
- Custom image prediction support
- Performance visualization with **Matplotlib**

---

## 📦 Dataset

- **Fashion-MNIST** from Zalando Research
- 70,000 grayscale images (28x28) in 10 classes
- Automatically loaded from Keras datasets

---

## 🧠 Model Architecture

```plaintext
Input Layer (28x28x1)
→ Conv2D (32 filters) + ReLU
→ MaxPooling2D
→ Conv2D (64 filters) + ReLU
→ MaxPooling2D
→ Flatten
→ Dropout (rate = 0.5)
→ Dense (128 units) + ReLU
→ Output (10 units, Softmax)
````

---

## 🏃‍♂️ How to Run

### ➤ Predict a custom image

```python

# Provide path to a 28x28 grayscale image
predict_custom_image("path_to_image.png")
```

---

## 📈 Training Results

| Metric   | Value (Example) |
| -------- | --------------- |
| Accuracy | 88.67%           |
| Loss     | 0.30            |
| Epochs   | 10              |

---

## 🛠️ Tech Stack

* **Python**
* **TensorFlow/Keras**
* **Matplotlib**
* **OpenCV (for custom image input)**

---

## 📄 License

MIT License. Feel free to use, modify, and share.

---

## 💬 Contact

Made with ❤️ by Hardik450(https://github.com/hardik450)
Have questions? Open an issue or reach out on GitHub.

---


