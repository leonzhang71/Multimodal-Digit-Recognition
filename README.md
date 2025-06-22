# 🧠 Multimodal Digit Recognition

A multimodal machine learning project that classifies handwritten digits using both **image** and **spoken audio** inputs. Combines visual and acoustic features with a custom **feature fusion strategy** to improve classification accuracy.

---

## 🔧 Tech Stack

- **Languages:** Python  
- **Libraries:** PyTorch, NumPy, Matplotlib, scikit-learn  
- **Techniques:** CNN (image encoder), Fully Connected NN (audio encoder), feature fusion, t-SNE visualization

---

## 📊 Results

- Achieved **0.992 macro F1 score** on the **Multimodal MNIST dataset**
- Outperformed benchmark models from previous published research
- Conducted ablation studies to analyze contribution of each modality

---

## 📁 Project Structure

```
├── data/                 # Image & audio inputs
├── models/               # CNN & FC model definitions
├── train.py              # Training script
├── evaluate.py           # Metrics and visualization
├── utils/                # Feature extraction, fusion
└── README.md             # You're here!
```

---

## 🧪 How to Run

1. Clone this repo  
2. Install dependencies:  
   `pip install -r requirements.txt`  
3. Run training:  
   `python train.py`  
4. Evaluate:  
   `python evaluate.py`

---
