# Wine-Alcohol-Prediction-ML

Abstract: 
This project focuses on the application of machine learning regression techniques to predict the alcohol content (% vol) of red wines using the UCI Wine Quality dataset. Unlike standard approaches that predict subjective wine quality, this study inverts the problem to estimate a specific chemical attribute, alcohol concentration, based on other physicochemical properties (such as acidity, density, and pH) and the quality (sensory) score. Leveraging the PyCaret AutoML framework, the study compared over 20 regression models, including linear, tree-based, and ensemble algorithms. The experimental results demonstrated that Support Vector Machine (SVM) regression yielded the best performance, achieving a Test R2 of 0.7684 and a Root Mean Squared Error (RMSE) of 0.5025%. Feature importance analysis revealed that ‘quality’ and ‘density’ were the most significant predictors, suggesting a strong correlation between these attributes and alcohol levels. 

------

Youtube Video Link of Term Project Code:
https://youtu.be/RAway-zgRfw

-------


**Pre-Requisite to run the Term Project locally with a older Python Version and PyCaret recent version:**

[README - Term Project PreReq's.md](https://github.com/user-attachments/files/23741594/README.-.Term.Project.PreReq.s.md)

---
# Wine Alcohol Content Prediction

## Environment Setup

### Prerequisites
- Anaconda or Miniconda installed
- Python 3.10.x required (PyCaret 3.3.2 compatibility)

### Installation Steps

**1. Create conda environment with Python 3.10:**
```bash
conda create -n pycaret_env python=3.10
```
(Press Enter, type 'y' when asked)

**2. Activate the environment:**
```bash
conda activate pycaret_env
```

**3. Install PyCaret from conda-forge:**
```bash
conda install -c conda-forge pycaret
```
(Press Enter, type 'y' when asked)

**4. Install Jupyter and kernel:**
```bash
conda install jupyter ipykernel
```
(Press Enter, type 'y' when asked)

**5. Register the kernel:**
```bash
python -m ipykernel install --user --name=pycaret_env
```

**6. Launch Jupyter:**
```bash
jupyter notebook
```

**7. Open the notebook and select the `pycaret_env` kernel**

## Running the Notebook
- Open `Wine_alcohol_prediction_pycaret.ipynb`
- Kernel → Change Kernel → `pycaret_env`
- Run all cells

## Notes
PyCaret 3.3.2 requires Python 3.10.x. Using `conda install` instead of `pip install` avoids C++ compiler issues on Windows.

Reference: [PyCaret Tutorial](https://github.com/pycaret/pycaret/blob/master/tutorials/Tutorial%20-%20Regression.ipynb)


