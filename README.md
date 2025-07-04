# VisTumor: Explainable Cancer Detection in Histopathology Images
VisTumor is a deep learning project for detecting cancer in histopathology images, with a focus on model interpretability. It uses CNNs trained on high-resolution medical images, then applies Grad-CAM++ and saliency mapping to visualize regions that most influence model decision making. The project explores the viability of explainable AI in medical diagnosis and clinical settings.

# 📁 Contents
* Local_Training.ipynb: trains and evaluates several pre-trained CNN architectures on histopathology patches
* Pre_Processing.ipynb: takes gigapixel WSIs and extracts usable patches for training/validation
* VisTumor_Paper: a short paper describing the methodology, results, and significance

# 🧠 Main Techniques
* PyTorch for training and evaluation
* OpenCV for patch extraction and image preprocessing
* torchvision for data augmentation and normalization
* Grad-CAM++ and saliency mapping for interpretability
