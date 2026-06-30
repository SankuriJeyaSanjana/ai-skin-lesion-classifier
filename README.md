# 🩺 AI Skin Lesion Classifier

An AI-powered web application that classifies skin lesion images into **seven different skin disease categories** using a **Convolutional Neural Network (CNN)**. The application allows users to upload a skin lesion image and predicts the disease along with a confidence score through an interactive Flask-based web interface.

---

# 📌 Project Overview

Skin diseases are among the most common health concerns worldwide, and early detection plays a crucial role in effective treatment. This project utilizes **Artificial Intelligence**, **Deep Learning**, and **Computer Vision** techniques to automatically classify skin lesion images into different disease categories.

A Convolutional Neural Network (CNN) is trained using the **HAM10000 dataset**, and the trained model is integrated with a Flask web application to provide real-time predictions.

---

# 🎯 Objectives

- Develop a Deep Learning model for skin lesion classification.
- Predict different types of skin diseases from dermoscopic images.
- Build a user-friendly web application for image upload and prediction.
- Display the predicted disease with confidence score.
- Demonstrate the practical application of AI in the healthcare domain.

---

# ✨ Features

- Upload skin lesion images (JPG, JPEG, PNG)
- Image preprocessing before prediction
- CNN-based disease classification
- Predicts **7 different skin lesion categories**
- Displays disease name and confidence score
- Lightweight and easy-to-use web interface

---

# 🛠️ Technologies Used

### Programming Languages
- Python
- HTML
- CSS

### Frameworks & Libraries
- Flask
- TensorFlow
- Keras
- OpenCV
- NumPy

### Development Tools
- VS Code
- Jupyter Notebook
- Git
- GitHub

---

# 🧠 Deep Learning Model

The classification model is built using a **Convolutional Neural Network (CNN)**.

### CNN Architecture

- Convolution Layers
- ReLU Activation
- Max Pooling Layers
- Flatten Layer
- Fully Connected Dense Layers
- Softmax Output Layer

The trained model predicts one among **7 different skin lesion classes**.

---

# 📂 Dataset

The model is trained using the **HAM10000 (Human Against Machine with 10000 Training Images)** dataset.

### Disease Categories

| Code | Disease |
|------|--------------------------------------------|
| AKIEC | Actinic Keratoses |
| BCC | Basal Cell Carcinoma |
| BKL | Benign Keratosis-like Lesions |
| DF | Dermatofibroma |
| MEL | Melanoma |
| NV | Melanocytic Nevi |
| VASC | Vascular Lesions |

---

# ⚙️ Project Workflow

```
          User Uploads Image
                  │
                  ▼
       Image Preprocessing
                  │
                  ▼
      CNN Model Prediction
                  │
                  ▼
 Disease Classification Result
                  │
                  ▼
 Displays Prediction & Confidence
```

---

# 📁 Project Structure

```
AI-SKIN-LESION-CLASSIFIER
│
├── Data_Sets/
├── Static/
├── Templates/
├── app.py
├── model.py
├── predict.py
├── beast_model.h5
├── ham10000-skin-disease-classification.ipynb
├── Melanoma_Classification_EDA_+_Model.ipynb
├── README.md
└── .gitignore
```

---

# 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/SankuriJeyaSanjana/ai-skin-lesion-classifier.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd ai-skin-lesion-classifier
```

### 3️⃣ Install Dependencies

```bash
pip install flask tensorflow keras numpy opencv-python
```

### 4️⃣ Run the Application

```bash
python app.py
```

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000
```

---

# 📊 Output

The application displays:

- Predicted Disease Name
- Disease Code
- Prediction Confidence Score

---

# 📸 Screenshots

### Home Page

> <img width="1920" height="1080" alt="Screenshot (200)" src="https://github.com/user-attachments/assets/6118556e-a0ab-4bdd-8eca-ee55a82b1bcc" />


### Upload Image

> <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/560683be-0139-462f-bba6-96241d71bc80" />


### Prediction Result

> <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f497af29-6fcd-4f34-9510-b3e79c98eebe" />

---

# 🚀 Future Enhancements

- Improve prediction accuracy using Transfer Learning models such as EfficientNet or ResNet.
- Increase image resolution for improved performance.
- Store prediction history using a database.
- Add patient login and authentication.
- Deploy the application using AWS, Azure, or Render.
- Provide detailed disease information and medical recommendations.
- Develop a mobile-responsive interface.

---

# 💡 Learning Outcomes

Through this project, we gained practical experience in:

- Artificial Intelligence
- Deep Learning
- Convolutional Neural Networks (CNN)
- Image Processing
- TensorFlow & Keras
- Flask Web Development
- Model Deployment
- Git & GitHub
- Team Collaboration

---

# 👨‍💻 Project Information

- **Project Type:** B.Tech Final Year Team Project
- **Role:** Team Leader
- **Domain:** Artificial Intelligence | Deep Learning | Computer Vision

### Responsibilities

- Led the project planning and development.
- Coordinated tasks among team members.
- Integrated the trained CNN model with the Flask web application.
- Participated in model training, testing, and debugging.
- Managed GitHub repository and project documentation.

---

# 👩‍💻 Repository Maintained By

**Sankuri Jeya Sanjana**

- **GitHub:** https://github.com/SankuriJeyaSanjana
- **LinkedIn:** https://www.linkedin.com/in/sankuri-jeya-sanjana-88023b279

---

# ⚠️ Disclaimer

This project is developed for **educational and research purposes only**. The predictions generated by this application are intended to support learning and experimentation and should **not** be considered a substitute for professional medical diagnosis or treatment. Always consult a qualified healthcare professional for medical advice.

---

# ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.

Thank you for visiting this repository!
