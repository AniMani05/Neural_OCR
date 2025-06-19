# Neural Network OCR & Image Classification from Scratch

This project demonstrates a complete from-scratch implementation of a simple neural network for Optical Character Recognition (OCR), along with extensions to image classification using PyTorch. It showcases both low-level learning and high-level adaptability across computer vision tasks.

## 📌 Project Highlights

- ✅ Built a one-hidden-layer neural network (“vanilla NN”) from scratch in NumPy
- ✅ Implemented Xavier initialization, softmax classifier, and backpropagation
- ✅ Validated gradients via numerical checking
- ✅ Trained on the NIST36 handwritten character dataset, achieving over **92% test accuracy**
- ✅ Visualized:
  - Learned weight filters
  - Loss and accuracy curves
  - Confusion matrices for detailed error analysis

## 🖼️ Real-World OCR Application

- Applied basic image processing (thresholding + connected components) to segment real-world text images
- Deployed the trained neural network to extract and reconstruct full multi-word text streams from raw images

## 🧠 PyTorch Extension

- Re-implemented the model using PyTorch for modular experimentation
- Fine-tuned the PyTorch version on:
  - **CIFAR-10** (object classification)
  - **Oxford Flowers** dataset (fine-grained image classification)
- Demonstrated the model’s flexibility across both OCR and general image recognition tasks

## 🧪 Technologies Used

- Python, NumPy, Matplotlib
- PyTorch
- OpenCV (for basic image segmentation tasks)
- NIST36, CIFAR-10, Oxford Flowers datasets

## 📈 Results

- **92%+ test accuracy** on NIST36
- Successful segmentation and extraction of text from real-world images
- Adaptability to general classification tasks (CIFAR-10, Flowers) via PyTorch fine-tuning

## Acknowledgements

I would like to thank my Computer Vision professor at Carnegie Mellon, Srinivasa Narasimhan, for his guidance regarding this project. 
