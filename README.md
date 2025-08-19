# Handwritten Digit Locker 🔐

## Project Overview
A machine learning system that recognizes handwritten digits and characters (including **"K"**) to simulate a secure PIN-based locker unlocking mechanism. The model is **fine-tuned** with additional data to handle diverse handwriting styles.

---
## 🔗 Colab Notebook  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1iC4p_QXqcAfoIdU_O_BUnxF4Kwka2DBO?usp=sharing)  

---

## Workflow
1. **Training** → Train model on handwritten dataset (0–9 + K)  
2. **Fine-Tuning** → Improve performance on imbalanced/new data (especially “K”)  
3. **Exporting** → Save trained model as `best_model_with_K.h5`  
4. **Testing** → Upload handwritten images for prediction  
5. **Unlock Simulation** → Correct PIN prediction grants access

---

## Challenges
- Diverse handwriting styles  
- Class imbalance and need for fine-tuning “K”  
- Avoiding overfitting with limited additional data

---

## Outcome
- Reliable handwritten digit/character recognition  
- Working **train → fine-tune → export → test → unlock** cycle  
- Improved prediction robustness after fine-tuning with added data

---

## Future Scope
- Real-time UI using **Streamlit** or **Flask**  
- Multi-character PINs and additional symbols  
- Biometric/hybrid authentication for stronger security

---

## Tech Stack
- **Languages & Libraries:** Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib  
- **Environment:** Jupyter Notebook / Google Colab

---

## Getting Started
1)Clone the repo:
git clone https://github.com/your-username/Handwritten-Digit-Locker.git
cd Handwritten-Digit-Locker

2)Open in Colab / Jupyter and run the notebook step by step.

3)Upload handwritten images to test PIN unlocking.

---
## Model and Data  

You can download the trained model and dataset from Google Drive:  
[Download Here](https://drive.google.com/drive/u/0/folders/1E8Do5S_gme-uEME-cTsgpmj2skn3zx7S)

### Setup Instructions  
1. Download the model file (e.g., `best_model.h5`) from the link above.  
2. Place it in the project root folder (or update the code with the correct path).  
3. If a dataset is provided, put it inside a folder named `data/` in the project directory.  
4. Run the notebook or script to start using the model.  

