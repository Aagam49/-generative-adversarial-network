# 🌳 Tree Image Generator using GANs

## 📌 Project Description
This project demonstrates the use of **Generative Adversarial Networks (GANs)** to synthesize **realistic tree images**. The GAN was trained on the **CIFAR-10** dataset, specifically focusing on the `'tree'` class, to generate new, visually plausible images.

Training was done over **2500 epochs**, allowing the generator and discriminator networks to converge stably and produce high-quality results. The project showcases practical implementation of GANs in the field of **generative deep learning**.

---

##  Problem Statement
Generating natural images like **trees** from scratch using AI is a challenging task, as it involves understanding textures, structures, and natural variations. This project aims to:

- Extract tree images from CIFAR-10.
- Train a GAN model to generate new tree images.
- Evaluate the realism of synthetic images using visual inspection and loss curves.

---

## 🛠️ Technologies & Tools Used

-  Python  
-  TensorFlow / Keras  
-  NumPy, Matplotlib  
-  CIFAR-10 Dataset (via Keras)  
-  Google Colab / Jupyter Notebook  
-  Git & GitHub

---

##  How It Works

1. **Data Preparation**  
   - Load CIFAR-10 dataset.
   - Filter only the **'tree' class** images (class label `4` in CIFAR-10).
   
2. **Model Architecture**  
   - Define a **Generator** and **Discriminator** using convolutional layers.
   - Use **LeakyReLU**, **BatchNorm**, and **Tanh/Sigmoid** activations.

3. **Training Loop**  
   - The **Discriminator** learns to distinguish real tree images from fake ones.
   - The **Generator** learns to create tree-like images that fool the Discriminator.
   - Save generated images and model weights at regular intervals.

4. **Evaluation**  
   - Visualize generator outputs every 100 epochs.
   - Track generator and discriminator losses.

---

## 📈 Training Summary

| Parameter        | Value          |
|------------------|----------------|
| Dataset Used     | CIFAR-10       |
| Class Used       | Tree           |
| Training Epochs  | 2500           |
| Batch Size       | 128            |
| Optimizer        | Adam           |
| Loss Function    | Binary Cross-Entropy (BCE) |

