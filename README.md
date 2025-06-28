# Speech Emotion Recognition: Efficiency and Ensemble Learning Approaches 🎭

[![Status](https://img.shields.io/badge/Status-Under%20Development-orange.svg)]()
[![Published](https://img.shields.io/badge/LAQ--MLP-Published%20NeurIPS%202024-green.svg)]()
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.9+-red.svg)](https://pytorch.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.8+-orange.svg)](https://tensorflow.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-yellow.svg)](https://scikit-learn.org/)
[![Librosa](https://img.shields.io/badge/Librosa-0.8+-purple.svg)](https://librosa.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## 🚧 Repository Status

This repository contains the implementation of our Speech Emotion Recognition (SER) research at **IIT Madras Zanzibar**. Our work includes published contributions on adaptive quantization and ongoing thesis research on multi-branch ensemble architectures.

> **🔔 Stay Updated**: Star this repository to receive notifications when we release the complete implementation!

---

## 🛠️ **Technology Stack**

### **Core Frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

### **Data Processing & ML**
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Librosa](https://img.shields.io/badge/Librosa-8A2BE2?style=for-the-badge&logo=python&logoColor=white)

### **Visualization & Analysis**
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### **Development Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white)

---

## 🔬 Research Overview

Our research addresses two fundamental challenges in Speech Emotion Recognition:

### 1. **LAQ+MLP: Efficient SER for Edge Devices** ✅ **Published at NeurIPS 2024**
- **Layer-wise Adaptive Quantization** with Multi-Layer Perceptron architecture
- Achieved **99.29% accuracy** on TESS dataset with only **169K parameters**
- Model compression to **25KB** while maintaining high performance
- Cross-dataset validation on EMODB, SAVEE, and TESS
- **Publication**: NeurIPS Efficient Natural Language and Speech Processing Workshop 2024

### 2. **Multi-Branch Ensemble Architecture** 🚧 **Master's Thesis Research**
- Comprehensive **15-experiment ablation study** investigating all meaningful branch combinations
- **Four processing branches**: Temporal, Prototype-based, Global, and Refinement
- **Learnable fusion strategies** for optimal ensemble integration
- **Cross-dataset validation** on EMODB, RAVDESS, SAVEE, and TESS

---

## 📊 Performance Highlights

| Method | TESS | EMODB | SAVEE | RAVDESS |
|--------|------|-------|-------|---------|
| **LAQ+MLP** ✅ | **99.29%** (169K) | 75.93% (169K) | 81.25% (169K) | - |
| **Multi-Branch Ensemble** 🚧 | 100.0% | **86.4%** | **77.7%** | **83.3%** |

*Numbers in parentheses indicate model parameters*

---

## 🎯 Key Contributions

### **Published Work: LAQ+MLP**
- Novel adaptive quantization strategy reducing model size by **>95%** while maintaining accuracy
- Layer importance computation based on statistical measures
- Cross-dataset robustness demonstration
- **Peer-reviewed validation** at NeurIPS ENLSP Workshop 2024

### **Ongoing Research: Multi-Branch Ensemble**
- First systematic ablation study of multi-branch SER architectures
- Strategic integration achieving **0.3-2.5%** improvements over individual components
- Discovery of complexity ceiling principle: **2-3 branch combinations optimal**
- Cross-dataset validation establishing universal architectural principles

---

## 📚 Publications

### **Published**
**Shinde, T., Jain, R., and Sharma, A.K.** (2024). "Lightweight Neural Networks for Speech Emotion Recognition using Layer-wise Adaptive Quantization." *NeurIPS Efficient Natural Language and Speech Processing Workshop*, pp. 584-595, PMLR.

### **In Progress**
- Multi-Branch Ensemble approach (Master's thesis research)
- Cross-dataset validation study
- Comprehensive ablation analysis

---

## 📈 Dataset Coverage

Our research validates across four benchmark datasets:

- **EMODB**: German emotional speech (cross-linguistic validation)
- **RAVDESS**: North American English professional actors
- **SAVEE**: British English male speakers (challenging expressions)
- **TESS**: Canadian English female speakers (controlled conditions)

---

## 🔄 Repository Updates

### **Phase 1: Published Work Implementation**
- [ ] LAQ+MLP complete source code
- [ ] Layer importance computation algorithms
- [ ] Adaptive quantization framework
- [ ] Cross-dataset evaluation scripts

### **Phase 2: Ensemble Research Framework**
- [ ] Multi-branch ensemble implementation
- [ ] 15-experiment ablation study framework
- [ ] Component visualization tools
- [ ] Statistical analysis notebooks

### **Phase 3: Documentation & Resources**
- [ ] Comprehensive documentation
- [ ] Pre-trained model checkpoints
- [ ] Reproducibility guidelines
- [ ] Performance analysis tools

---

## 📝 Research Timeline

- **✅ NeurIPS 2024**: LAQ+MLP published and presented
- **🚧 Current**: Multi-branch ensemble thesis research
- **📅 Upcoming**: Thesis defense and final publication
- **🔮 Future**: Extended ensemble methodologies

---

## 🏆 Research Impact

### **Technical Innovation**
- First published work on adaptive quantization for SER
- Systematic multi-branch architectural analysis
- Evidence-based deployment recommendations

### **Practical Applications**
- Edge device deployment with minimal accuracy loss
- Cross-linguistic emotion recognition capabilities
- Scalable architecture for diverse deployment scenarios

---

## 📧 Contact

- **Researcher**: Avinash Kumar Sharma
- **Institution**: Indian Institute of Technology Madras Zanzibar
- **Email**: zda23m011@iitmz.ac.in
- **Program**: Master's Thesis Research

---

## ⭐ Connect & Collaborate

- **Star this repository** for updates on research progress
- **Follow** for related research and publications
- **Contact** for collaboration opportunities or technical discussions

---

**Disclaimer**: This repository is under active development as part of Master's thesis research at IIT Madras Zanzibar. Complete implementation will be available following thesis submission and institutional approval.

**Last Updated**: July 2025
