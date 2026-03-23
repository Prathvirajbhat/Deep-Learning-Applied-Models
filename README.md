# 🚀 Deep Learning Applied Models

This project presents a comprehensive implementation of fundamental and advanced deep learning models across multiple domains, including computer vision, sequence learning, and generative modeling.

The objective of this project is to understand how different neural network architectures behave, compare their performance, and analyze their strengths and limitations through practical experimentation.

---

## 📌 Project Overview

This repository includes:

- 🧠 Convolutional Neural Networks (CNN) for image classification  
- 🔁 Recurrent Neural Networks (RNN, LSTM, GRU) for sequence modeling  
- 🎨 Generative Adversarial Networks (GAN) for image generation  
- ⚡ Transfer Learning (ResNet18 - conceptual implementation)  

All models were implemented and tested using real-world datasets.

---

## 📂 Repository Structure

---

## 🧠 Models Implemented

### 🔹 1. CNN (Image Classification)

- Dataset: Fashion-MNIST  
- Architecture: Conv → ReLU → Pool → FC  
- Improved with: Batch Normalization + Dropout  

📊 **Results:**
- CNN Accuracy: **92.18%**
- BatchNorm CNN Accuracy: **92.36%**

---

### 🔹 2. RNN, LSTM, GRU (Text Classification)

- Dataset: IMDB Reviews  
- Task: Sentiment Classification  

📊 **Results:**

| Model | Accuracy |
|------|--------|
| RNN | 79.96% |
| LSTM | **86.84%** |
| GRU | 85.92% |

📌 **Observation:**
- LSTM performs best due to better handling of long-term dependencies  
- GRU provides similar performance with fewer parameters  
- RNN struggles with vanishing gradient problem  

---

### 🔹 3. GAN (Image Generation)

- Dataset: Fashion-MNIST  
- Architecture:
  - Generator → Noise → Image  
  - Discriminator → Real/Fake classification  

📊 **Results:**
- Initial outputs: Random noise  
- Final outputs (Epoch 50): Recognizable clothing patterns  

📌 **Observations:**
- Gradual improvement in image quality  
- Mild mode collapse observed  
- Training instability handled with tuning  

---

### 🔹 4. Transfer Learning (ResNet18)

- Pretrained model adapted for Fashion-MNIST  
- Final layer modified for classification  

📊 **Expected Performance:**
- Accuracy: ~93% – 95%  
- Faster convergence than custom CNN  

---

## 📊 Key Insights

- Batch Normalization improves training stability  
- LSTM significantly outperforms standard RNN  
- GAN training is highly unstable but improves over time  
- Transfer learning reduces training effort and improves accuracy  

---

## 🛠️ Technologies Used

- Python 🐍  
- PyTorch 🔥  
- TensorFlow / Keras ⚙️  
- NumPy  
- Matplotlib  

---

## 💻 Hardware

- Google Colab (GPU enabled)

---

## 📈 Results Visualization

- Training Loss & Accuracy Curves (CNN)  
- Model Comparison Graph (RNN vs LSTM vs GRU)  
- GAN Generated Images across epochs  

---

## ⚠️ Limitations

- ResNet18 training not fully completed due to computational limits  
- GAN outputs still slightly blurry  
- Limited hyperparameter tuning  

---

## 🚀 Future Improvements

- Implement Conditional GAN (cGAN)  
- Use deeper CNN architectures  
- Fine-tune ResNet with more epochs  
- Explore advanced optimizers  

---

## 👨‍💻 Author

**Prathviraj Bhat**  
Information Science & Engineering  
NMAM Institute of Technology  

---

## 📜 License

This project is for academic and educational purposes only.

---

## ⭐ Final Note

This project was built with a focus on understanding deep learning concepts from a practical perspective, comparing multiple architectures, and analyzing real-world model behavior.

If you found this useful, consider ⭐ starring the repository!
