# 🧬 Protein-Protein Interaction (PPI) Link Prediction Project

## 🔍 **Overview**
This project focuses on **predicting missing links in Protein-Protein Interaction (PPI) graphs** to explore potential applications in RNA therapeutic development. PPIs are fundamental to biological processes, as proteins interact to perform various functions. 

### 🧬 **Key Biological Examples**
- **Enzyme Reactions**: Enzymes interact with specific proteins to catalyze or inhibit reactions.
- **Signal Transduction**: Protein interactions enable intracellular communication.

### 🎯 **Project Goals**
- 🧩 **Uncover Missing Links**: Predict unknown interactions in PPI networks.
- 💡 **Understand Protein Functions**: Gain insights into how proteins operate within networks.
- 🧪 **Enable RNA Therapeutics Development**: Explore new therapeutic targets.

---

## ⚙️ **Features**
- **Data Preprocessing**: Tools to clean and structure PPI datasets.
- **AutoEncoder Modeling**: Use AutoEncoders to predict missing interactions.
- **Graph Neural Networks (GNNs)**: Exploit graph structures for link prediction.
- **Result Analysis**: Evaluate models and visualize predictions.

---

## 📂 **Folder Structure**
```plaintext
/project-root
├── Preprocessing.ipynb            # Data preprocessing notebook
├── link_prediction-AE-Chen final.ipynb  # AutoEncoder-based link prediction
├── link_prediction_gnn_final.ipynb     # GNN-based link prediction
├── mr.py                        # Data preprocessing and utility functions
├── mr_gnn.py                    # GNN model training and evaluation script
├── requirements.txt
```
---

## 🚀 **Installation**
1. Clone thie Repository
```
git clone https://github.com/Hannah1011/SMU_Protien_LinkPrediction.git
```

2. Navigate to the project directory

3. Install Dependencies
```
pip install -r requirements.txt
```

---

## 🛠️ Usage
1. Data Preprocessing
```
python mr.py
```
2. Train AutoEncoder Model
```
jupyter notebook link_prediction-AE-Chen\ final.ipynb
```
3. Train GNN Model (Run the GNN-based model)
```
jupyter notebook link_prediction_gnn_final.ipynb
```
4. Result Analysis (Visualize and evaluate predictions)
```
python mr_gnn.py
```
