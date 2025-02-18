# Baby Cry Identifier using CNN

## 📌 Overview
The **Baby Cry Identifier** is a deep learning-based project that classifies different types of baby cries using **Convolutional Neural Networks (CNN)**. The model takes **MFCC (Mel-Frequency Cepstral Coefficients)** extracted from audio clips as input and predicts the category of the cry.

## 🚀 Features
- **MFCC Feature Extraction**: Converts baby cry audio into spectrogram-like features.
- **Convolutional Neural Network (CNN)**: Deep learning model for classification.
- **Categorical Cross-Entropy Loss**: Used for multi-class classification.
- **Real-Time Detection**: Can process audio recordings to classify baby cries.

## 📂 Dataset
- The dataset consists of baby cry audio recordings categorized into different emotions such as:
  - **Hungry**
  - **Pain**
  - **Sleepy**
  - **Uncomfortable**
- Audio files are preprocessed into **MFCC features** before training.

## 🏗 Model Architecture
The CNN model consists of:
- **Input Layer**: MFCC features (2D array)
- **Convolutional Layers**: Extract spatial features
- **Batch Normalization**: Improves training stability
- **Dropout**: Reduces overfitting
- **Fully Connected Layers**: Classify cry types

## 🔧 Installation & Usage
### 1️⃣ Clone the Repository
```bash

https://github.com/SurajeeKumar22aib47/baby-cry-identifier.git
cd baby-cry-identifier
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Train the Model
```bash
python train.py
```
### 4️⃣ Test the Model
```bash
python predict.py --file example_audio.wav
```

## 📊 Performance
- Accuracy: **~90%** on validation set
- Loss: **Optimized using Adam optimizer**

## 📈 Future Improvements
- **Real-time classification using a mobile app**
- **Deploy as a web API with FastAPI**
- **Optimize model using TensorFlow Lite for edge devices**

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.

## 📜 License
This project is licensed under the MIT License.

## 🛠 Tech Stack
- **Python**
- **TensorFlow/Keras**
- **Librosa** (for audio processing)
- **NumPy & Pandas**
- **Matplotlib & Seaborn** (for visualization)

---
### 📩 Contact
For queries, reach out via:
📧 Email: sksurajee1245@gmail.com  
🌐 Website: [Surajee Kumar S](https://surajee-kumar-portfolio.netlify.app/)  
🔗 LinkedIn: [Surajee Kumar](https://www.linkedin.com/in/surajee-kumar-853909256)

