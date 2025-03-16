# Handwritten Digits Recognizer

## 📌 Project Overview
This project aims to **recognize handwritten digits from 0 to 9** using a **Convolutional Neural Network (CNN)** trained on the **MNIST dataset**. The model can predict custom digit images provided by the user.

---

## 🛠️ Tech Stack
- Python
- TensorFlow/Keras
- OpenCV
- Numpy
- Matplotlib

---

## 📂 Dataset Description
The **MNIST dataset** contains 70,000 grayscale images of handwritten digits (28x28 pixels):
- 60,000 training images
- 10,000 testing images

---

## 🏁 Project Workflow

### 1. Data Preprocessing
- Normalization of pixel values (scaling between 0 and 1)
- Reshaping the data for input compatibility

### 2. Model Building
- Flatten input layer for pixel data
- Two dense hidden layers with **ReLU activation function**
- Output layer with **softmax activation** for 10 digit classes

### 3. Model Training
- **Optimizer:** Adam
- **Loss Function:** Sparse Categorical Crossentropy
- **Metrics:** Accuracy

### 4. Model Evaluation
- Validate using test data
- Display validation loss and accuracy

### 5. Predict Custom Images
- Load custom handwritten digit images
- Preprocess and invert images
- Predict the digit using the trained model

---

## 🔥 Results
| Model             | Accuracy |
|----------------|------------------|
| Neural Network | 97% |

---

## 📖 How to Run the Project
1. Clone the repository:
```bash
https://github.com/your-repo/handwritten-digit-recognizer.git
```
2. Install the required libraries:
```bash
pip install tensorflow opencv-python matplotlib numpy
```
3. Run the script to train the model:
```bash
python handwritten_digits_recognition.py
```
4. To predict custom images, place them in the `digits` folder and run the script again.

---

## 📈 Visualizations
- Loss vs. Epoch Plot
- Accuracy vs. Epoch Plot
- Predicted Digit Display

---

## 🧐 Future Improvements
- Hyperparameter tuning
- Data augmentation
- Deploying the model using Flask/FastAPI

---

## 🎯 Conclusion
The **Neural Network** achieves **97% accuracy** on the MNIST dataset and successfully predicts custom handwritten digits.

---

## 👨‍💻 Author
**Nanda Kishore Reddy Gajjala Venkata**

GitHub: [Nanda Kishore Reddy Gajjala](https://github.com/NandaKishoreReddyGajjala)

LinkedIn: [Nanda Kishore Reddy G](https://www.linkedin.com/in/nanda-kishore-reddy-g/)

---

