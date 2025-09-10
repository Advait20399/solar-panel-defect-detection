# 🌞 Solar Panel Defect Detection

This project focuses on **automated defect detection in solar panels** using **deep learning** and **computer vision** techniques. It provides workflows for dataset preprocessing, model training, evaluation, and visualization to identify defects in solar panel images.

---

## 📂 Repository Structure

```
solar-panel-defect-detection/
│── README.md                # Project overview and documentation
│── requirements.txt         # Dependencies for running the project
│
├── notebooks/
│   └── solar_defect_detection.ipynb   # Jupyter Notebook with complete workflow
│
├── src/
│   ├── data_preprocessing.py          # Dataset loading & preprocessing scripts
│   ├── model_training.py              # Model creation and training pipeline
│   ├── evaluation.py                  # Model evaluation & performance metrics
│   ├── visualization.py               # Visualization of results & predictions
│   └── utils.py                       # Helper functions
│
└── dataset/
    └── Group D - Solar Panel Defect Detection/   # Extracted dataset files
```

---

## 🚀 Features
- **Data Preprocessing**: Handles dataset extraction, cleaning, and augmentation.  
- **Model Training**: Deep learning models for image classification and defect detection.  
- **Evaluation**: Includes accuracy, confusion matrix, and classification reports.  
- **Visualization**: Training curves, sample predictions, and result plots.  
- **Reusable Scripts**: Modular Python files for easier experimentation.

---

## 📊 Dataset
The dataset is provided in the repository under:  
```
dataset/Group D - Solar Panel Defect Detection/
```
It contains labeled images of **defective** and **non-defective** solar panels for supervised learning tasks.

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/solar-panel-defect-detection.git
   cd solar-panel-defect-detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/solar_defect_detection.ipynb
   ```

---

## 🖥️ Usage

- Run the Jupyter notebook for an end-to-end workflow.  
- Use scripts in the `src/` folder for modular experimentation:
  ```bash
  python src/data_preprocessing.py
  python src/model_training.py
  python src/evaluation.py
  python src/visualization.py
  ```

---

## 📈 Results
- Achieved classification accuracy on solar panel defect dataset (fill with your result after training).  
- Visualization includes defect detection plots and training/validation accuracy graphs.  

---

## 📚 Future Work
- Extend dataset with more defect types.  
- Deploy model via a web app or API.  
- Experiment with transfer learning (ResNet, EfficientNet, etc.).  

---

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue to discuss what you’d like to change.

---

## 📜 License
This project is licensed under the **MIT License** – feel free to use and modify with attribution.
