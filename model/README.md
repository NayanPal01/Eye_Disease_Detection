# 🧠 Eye Disease Detection using Deep Learning

An AI-based system for detecting common eye diseases from retinal images using CNN and MobileNet architectures.

This project focuses on automated classification of retinal images into four categories:
- **CNV** — Choroidal Neovascularization  
- **DME** — Diabetic Macular Edema  
- **DRUSEN** — Drusen deposits  
- **NORMAL** — Healthy retina  

---

## 📁 Project Structure

```text
Eye_Disease/
│
├── Dataset - train+val+test/
│   ├── train/
│   │   ├── CNV/
│   │   ├── DME/
│   │   ├── DRUSEN/
│   │   └── NORMAL/
│   ├── val/
│   └── test/
│
├── model/
│   └── README.md        # Instructions to download trained model
│
├── training_model.ipynb # Model training and evaluation notebook
├── .gitignore
└── README.md
```
## 🚀 How to Run the Project

### Step 1: Download the Trained Model

The trained model is stored externally due to GitHub file size limits.

```text
Open: model/README.md
Download the model from the provided link : https://drive.google.com/drive/u/0/folders/1Tu5JdIr8kUQgzjcNRi7hIXN_sg2EoLMW
Place the file inside the model folder as:
model/Trained_Eye_disease_model.h5
```