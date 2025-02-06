# **🌄 Landscape Image Generation using DCGAN**  

This project trains a **Deep Convolutional GAN (DCGAN)** to generate **realistic landscapes** such as **mountains, beaches, islands, and cities** using the **Landscape Pictures Dataset** from Kaggle.  

## **📌 Project Overview**  
- Uses **DCGAN** (Deep Convolutional GAN) for **image generation**  
- Trained on **high-quality landscape images**  
- Generates **new, realistic landscapes from random noise**  

## **🛠️ Model Architecture**  
### **1️⃣ Generator (G)**
- Converts **random noise (100D latent vector)** into a **realistic landscape**  
- Uses **Transpose Convolutions + BatchNorm + LeakyReLU**  
- Outputs a **64x64 RGB image**  

### **2️⃣ Discriminator (D)**
- A **binary classifier** that differentiates **real vs. fake images**  
- Uses **Convolutions + LeakyReLU + Dropout**  
- Outputs a **probability score (real/fake)**  

## **🚀 Training the GAN**
- **Loss Function:** Binary Cross-Entropy  
- **Optimizers:** Adam (Learning Rate = 0.0002)  
- **Training Steps:**
  1. **Discriminator** learns to classify real vs. fake landscapes  
  2. **Generator** improves by trying to fool the discriminator  
  3. Training runs for **5000 epochs**  

## **📈 Results**  
- After training, the model generates **high-quality, diverse landscapes**  
- Can create **mountains, beaches, and other scenery from scratch**  

## **📌 Example Generated Landscapes**
After training, the model can generate stunning landscapes like these:  
🔹 **Snowy Mountains**  
🔹 **Tropical Beaches**  
🔹 **Desert Landscapes**  
🔹 **Lush Green Forests**  
