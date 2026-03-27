# autoencoder-tutorial
# Understanding Autoencoders: Compression, Reconstruction, and Denoising

---

## 📖 Project Overview

This project demonstrates how **autoencoders**, a type of neural network, can be used for:

* Dimensionality reduction
* Image reconstruction
* Noise removal (denoising)

The tutorial explores how the size of the latent space affects reconstruction quality and how autoencoders can learn meaningful representations of data.

---

## 🧠 Key Concepts

* Encoder–Decoder architecture
* Latent space (bottleneck)
* Reconstruction loss (Mean Squared Error)
* Undercomplete autoencoders
* Denoising autoencoders

---

## 📊 Experiments

### 1. Latent Space Comparison

* **Latent dimension = 2** → strong compression, blurry outputs
* **Latent dimension = 32** → better reconstruction quality

### 2. Denoising Autoencoder

* Input images are corrupted with noise
* Model learns to reconstruct clean images

---

## 📈 Results

### 🔹 Reconstruction

The model demonstrates a trade-off between compression and reconstruction accuracy.

### 🔹 Denoising

The denoising autoencoder successfully removes noise while preserving important features.

### 🔹 Latent Space

The 2D latent representation shows clustering of similar digits, indicating meaningful feature learning.

---

## 🖼 Example Outputs

The notebook generates the following figures:

* Training vs Validation Loss curves
* Reconstruction comparison (Original vs Latent=2 vs Latent=32)
* Denoising results (Noisy → Reconstructed → Original)
* Latent space visualisation

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/[your-username]/autoencoder-tutorial.git
cd autoencoder-tutorial
```

### 2. Install dependencies

```bash
pip install -r requirements.txt


### 3. Run the notebook

```bash
jupyter notebook


Open:

notebook/autoencoder_tutorial.ipynb


## 📁 Project Structure

autoencoder-tutorial/
│
├── notebook/
│   └── autoencoder_tutorial.ipynb
│
├── report.pdf
│
├── requirements.txt
├── README.md
└── LICENSE

## 📚 References

* Hinton, G. E., & Salakhutdinov, R. R. (2006)
* Chollet, F. (2017)
* Goodfellow, I., Bengio, Y., & Courville, A. (2016)
* TensorFlow Keras Documentation
* MNIST Dataset

---

## ♿ Accessibility

All figures include clear labels and do not rely solely on colour.
The notebook is structured with readable Markdown and explanations for accessibility.

---

## 📜 License

This project is licensed under the MIT License.
