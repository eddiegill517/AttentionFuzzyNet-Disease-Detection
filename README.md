# AttentionFuzzyNet  
### Novel Disease Detection for Pandemic Prevention using Attention & Fuzzy Neural Networks

AttentionFuzzyNet is a **hybrid deep learning framework** designed for **novel disease detection** from chest X-ray images.  
The model integrates **attention-enhanced CNN feature extraction** with a **Fuzzy Min-Max Neural Network classifier**, enabling robust detection of **previously unseen diseases without requiring prior training samples**.

This project extends the **Deep-Precognitive Diagnosis framework (IEEE Access, 2022)** by incorporating:
- CBAM attention mechanisms
- Center loss for discriminative feature learning
- Mahalanobis distance-based novelty scoring
- Multi-score fuzzy decision fusion

---

## 📌 Key Highlights
- 🔬 Novel disease detection (open-set recognition)
- 🧠 Attention-driven pathology-focused feature learning
- 🌫️ Fuzzy logic for uncertainty-aware classification
- 🏥 Medical imaging (Chest X-rays)
- 🚨 Designed for pandemic preparedness & early outbreak detection

---


## ⚙️ Model Components

### 1. CNN Feature Extractor
- Backbone: VGG-16
- Fine-tuned on known pathology classes
- Extracts high-level semantic features from chest X-rays

### 2. CBAM Attention Module
- Channel Attention: *what features matter*
- Spatial Attention: *where pathology is located*
- Enhances disease-relevant regions

### 3. Center Loss
- Reduces intra-class variance
- Improves feature compactness
- Strengthens separation between known classes

### 4. Fuzzy Min-Max Neural Network
- Represents classes as hyperboxes
- Handles uncertainty and overlapping distributions
- Well-suited for open-set classification

### 5. Novelty Detection Logic
- Mahalanobis distance-based scoring
- Multi-threshold fusion strategy:
  - θ = 0.30
  - γ = 4.0

---

## 📊 Performance

| Metric | Result |
|------|--------|
| Novel Disease Detection Rate (COVID-19) | **86.67%** |
| Published Benchmark | 82.50% |
| Improvement | **+4.17%** |
| Known Class Accuracy | 85.42% |
| AUROC | 0.68 |

> COVID-19 is successfully detected as a **novel disease without prior training samples**

---

## 🛠️ Tech Stack

- Python
- PyTorch
- VGG-16
- CBAM Attention
- Fuzzy Min-Max Neural Networks
- Medical Image Processing
- Mahalanobis Distance Metrics

---

## 🧪 Dataset
- Chest X-ray medical imaging dataset  
- Includes known pathology classes and unseen disease samples  
- Dataset not included due to licensing and privacy constraints  

---

## 📖 Research Context
This project was completed as a **mentored research project** and extends:

**Deep-Precognitive Diagnosis Framework**  
*IEEE Access, 2022*

The proposed architecture improves **generalization, robustness, and early detection capability** for unseen diseases.

---

## 🌍 Applications
- Pandemic early warning systems  
- Hospital triage automation  
- Clinical decision support systems  
- Open-set medical diagnosis pipelines  

---

## 👨‍💻 Author
**Yuvraj Gill**  
AI & ML Engineer  
📧 eddiegill517@gmail.com  
📍 India  

---

## ⭐ Acknowledgement
If you find this project useful for research or learning, please consider giving it a ⭐ on GitHub.
