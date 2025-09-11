

# 🖥️🔧 PC Parts Classification – ResNet-18 Deep Learning Project

This project focuses on building an **image classification model** to identify different **PC hardware parts** such as CPU, GPU, RAM, and motherboard. A dataset of labeled images was used, and by applying **transfer learning with ResNet-18**, the model was able to achieve excellent performance with a **94% testing accuracy**.

ResNet-18, a pretrained convolutional neural network, was fine-tuned on this dataset to leverage its powerful feature extraction capabilities. This approach not only improved accuracy but also reduced training time compared to building a CNN from scratch.

The project demonstrates the potential of **computer vision in hardware recognition**, with real-world applications in **automated inventory management, e-commerce product categorization, and hardware identification systems**.

---

## 🔍 Project Workflow

* 🖼️ **Dataset Preparation**

  * Collected and organized labeled images of PC components
  * Applied preprocessing and data augmentation for better generalization

* 🧠 **Model Training (ResNet-18)**

  * Used **ResNet-18 pretrained model** with transfer learning
  * Fine-tuned the final layers to adapt to PC part classification
  * Achieved **94% test accuracy**

* 📊 **Evaluation & Visualization**

  * Accuracy and loss curves during training
  * Confusion matrix to analyze misclassifications
  * Sample predictions showcasing correct classifications

---

## 🛠️ Tools & Libraries

* Python 🐍
* PyTorch ⚡ (ResNet-18 from torchvision models)
* NumPy & pandas 📊
* Matplotlib & Seaborn 🎨
* Jupyter Notebook 📒

---

## 📈 Results

* ResNet-18 achieved **94% accuracy** on the test dataset
* Transfer learning allowed faster convergence and better performance
* Model successfully differentiated between visually similar PC parts

---

## 🧠 Outcome

This project was a valuable experience in applying **transfer learning for computer vision tasks**. It provided hands-on understanding of **ResNet architectures**, dataset preparation, and performance evaluation. The high accuracy achieved reflects the strength of pretrained models like ResNet-18 in solving **real-world classification problems**.

