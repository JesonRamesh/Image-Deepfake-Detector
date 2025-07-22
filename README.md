# 🧠 Image Deepfake Detector
A simple model to check if an image is *Real* or *Fake (AI Generated)* 

This project uses a CNN to detect whether an input image is real or AI-generated.

🖼️ **Try the App**: 
---
[![Gradio App](https://img.shields.io/badge/Gradio-App-blue?logo=gradio)](https://huggingface.co/spaces/jeeeeeeeson/fake_image_detector)

Upload an image and get a "Real" or "Fake" prediction.

---


## 🚀 Demo
Upload any picture and the model will classify it as either:
- **Real**
- **Fake**

<img width="2223" height="601" alt="image" src="https://github.com/user-attachments/assets/65e9c7ec-cadb-42ff-b675-7dec1165031a" />

## 🧾 How It Works
1. **Model** - A simple CNN model trained using Kaggle's '140k Real and Fake Faces' [Click Here](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces) to view the dataset
2. **Input** - Image of a face (AI generated or Real)
3. **Output** - Binary label (*Real* or *Fake*)

The image is resized, normalized, and passed through the model. The prediction is returned instantly via the Gradio interface.

## 🧰 Tech Stack

- Python
- PyTorch
- Gradio
- PIL / torchvision

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
