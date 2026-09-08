# NVIDIA Deep Learning Fundamentals-Workshop & ITI

A comprehensive repository containing practical code implementations, custom neural network architectures built from scratch, and hands-on notebooks completed as part of the **NVIDIA Deep Learning Institute (DLI)** and **Information Technology Institute (ITI)** Summer Training program.

---

## 🚀 About the Repository
This repository showcases foundational and applied deep learning implementations using **Python** and **PyTorch**, focusing on GPU-accelerated environments, computer vision pipelines, natural language processing, and transfer learning workflows.

---

## 📂 Project Structure

* **`01_mnist.ipynb`**: Introduction to image classification using the classic MNIST dataset and fully connected neural networks.
* **`02_asl.ipynb`**: Image classification pipeline applied to the American Sign Language (ASL) dataset.
* **`03_asl_cnn.ipynb`**: Implementation of Convolutional Neural Networks (CNNs) featuring custom blocks, Batch Normalization, and Max Pooling to combat overfitting.
* **`04a_asl_augmentation.ipynb`**: Data augmentation workflows utilizing TorchVision transforms (Random Resized Crops, Flips, Color Jitter) to boost model generalization[cite: 4].
* **`05a_doggy_door.ipynb`**: Utilizing pre-trained ImageNet models (VGG16) out-of-the-box for animal classification[cite: 3].
* **`05b_presidential_doggy_door.ipynb`**: End-to-end transfer learning and model fine-tuning implementation for specialized binary classification tasks.
* **`06_nlp.ipynb`**: Natural Language Processing tutorials covering subword tokenization (WordPiece), BERT embeddings, text masking, and question-answering architectures[cite: 1].
* **`07_assessment.ipynb`**: Final practical assessment featuring a complete multi-class image classification pipeline for fresh and rotten fruit recognition.
* **`utils.py`**: Reusable modular components including custom convolutional blocks (`MyConvBlock`) and evaluation metrics.

---

## 🛠️ Technical Stack & Toolkit

* **Languages:** Python
* **Frameworks & Libraries:** PyTorch, TorchVision, Pandas, NumPy, Matplotlib, Scikit-Learn, Hugging Face Transformers
* **Hardware Acceleration:** CUDA-enabled GPU environments

---

## 📌 Acknowledgments
Completed as a core technical milestone within the **ITI Summer Training 2026** program, utilizing foundational coursework and accelerated computing assets provided by the **NVIDIA**.
