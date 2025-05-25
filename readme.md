# 🩺 Cardiovascular Disease Detection using TabNet

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.9+-orange.svg)](https://pytorch.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

This project presents a deep learning pipeline for detecting Cardiovascular Disease (CVDs )using TabNet (Tabular-Network, developed by Google Research), data balancing methods (SMOTE/ADASYN), and correlation-based feature selection.



## 📁 Folder Structure/

- 📁 BRFSS2015_dataset/
   -  heart_disease_health_indicators_BRFSS2015.csv - contains the BRFSS2015 dataset used in this study.
- 📓 Correlation_FS.ipynb
- 📓 EDA.ipynb
- 📄 LICENSE
- 📄 README.md


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
git clone https://github.com/avi12299/CVDs_Detection_using_TabNet.git
cd CVDs_Detection_using_TabNet

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

The notebook interface will open in your default web browser. 
Open EDA.ipynb or Correlation_FS.ipynb to get started

📚 Citation
If you use this project in your research, please cite:
```
bibtex@article{,
  title={Cardiovascular Disease Detection using TabNet:
Attentive Interpretable Tabular Learning
},
  author={Avinash kumar, Sangeeta sharma, Ram Prakash Sharma},
  journal={CVR2025},
  year={2025}
}
```


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **Avinash kumar** - *Initial work* - [@avi12299](https://github.com/avi12299)

## 🙏 Acknowledgments

- PyTorch Lightning team for the excellent framework
- Contributors to the BRFSS datasets
- Open-source community for tool development


## 📞 Support

For support and questions:
- 📧 **Email**: avinashkr1302@gmail.com
- 🐛 **Issues**: [GitHub Issues](https://github.com/avi12299/CVDs_Detection_using_TabNet/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/avi12299/CVDs_Detection_using_TabNet/discussions)

---

<div align="center">

**⭐ Star this repository if it helped you! ⭐**

Made with ❤️ for advancing cardiovascular health through AI

</div>
