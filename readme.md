# 🩺 Cardiovascular Disease Detection using TabNet

This project presents a deep learning pipeline for detecting Cardiovascular Disease (CVDs )using TabNet (Tabular-Network, developed by Google Research), data balancing methods (SMOTE/ADASYN), and correlation-based feature selection.


## 📁 Folder Structure

CVDs_Detection_TabNet/
├── BRFSS2015_dataset/
│ └──heart_disease_health_indicators_BRFSS2015.csv
├── Correlation_FS.ipynb
├── EDA.ipynb
└── README.md


## 🎯 Objective

To predict cardiovascular diseases using TabNet with EDA, data preprocessing, feature selection, and class balancing techniques for improved accuracy and explainability.


## 📊 Dataset

- Source: https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset
- Size: 253,680 samples
- Features: 22
- Target: `HeartDiseaseorAttack` (0 or 1)


## 📒 Notebooks Overview


### Correlation_FS.ipynb
- Correlation-based feature selection
- Balancing using SMOTE/ADASYN 
- TabNet training
- Evaluation 



### EDA.ipynb
- Data cleaning
- Visualizations
- SMOTE / ADASYN balancing
- TabNet training and 
- Evaluation


## 🛠️ Technologies Used

- Python 3.8+
- PyTorch + TabNet
- scikit-learn
- imbalanced-learn
- pandas, numpy, matplotlib, seaborn


## ⚙️ Installation & Usage

```bash
git clone https://github.com/yourusername/CVDs_Detection_TabNet.git
cd CVDs_Detection_TabNet

# Create and Activate Virtual Environment
# For windows:
python -m venv venv
venv\Scripts\activate


# For Linux/MacOS
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Run the Jupyter Notebook
# If Jupyter is not installed, add it with:
pip install notebook

# Then launch:
jupyter notebook
```

# The notebook interface will open in your default web browser. Open EDA.ipynb or Correlation_FS.ipynb to get started

