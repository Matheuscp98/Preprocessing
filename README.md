# ⚙️ Impact of Preprocessing on the Performance and Computational Efficiency 

## 📝 Description

This repository contains the **Python implementation** used to analyze the impact of different **preprocessing strategies** on the **predictive performance** and **computational efficiency** of Machine Learning (ML) models.

The code systematically compares **three distinct approaches to data construction**:

1. **Original Data**: Raw dataset **without dimensionality reduction**.  
2. **Principal Component Analysis (PCA)**: **Dimensionality reduction** using PCA.  
3. **Principal Component Factor Analysis (PCFA)**: Method that combines *PCA* with *Factor Analysis*, resulting in *PCFA*, and applies Varimax rotation.

Additionally, the code incorporates **Design of Experiments (DOE)** with **factorial design** to test different combinations of attributes. **Ten datasets** from various domains (chemistry, health and medicine, computer science, geosciences, telecommunications, environmental sciences, and materials engineering, among others) are processed, and **ten Machine Learning (ML) algorithms** are evaluated. All models undergo **cross-validation** and **hyperparameter tuning** using two different optimization strategies (**Optuna** and **Grid Search**).

**Note:** This code focuses on the **preprocessing** and **evaluation** stages; it does **not** include extensive **visualization** routines.

---

## 📚 Publications

This repository is part of the research study:

-  *Manuscript currently under peer review*

---

## 🛠️ How to Use

1. **Clone or download** this repository or the [**Script Preprocessing**](script_preprocessing.ipynb) notebook.  
2. **Open** the notebook in **Jupyter**.  
3. **Install** the **required Python libraries** (listed at the beginning of the notebook).  
4. **Load** your own datasets or use the provided **`.csv` datasets** in this repository.  
5. **Run** the notebook cells **sequentially** to reproduce the **preprocessing**, **model training**, and **evaluation** pipeline.  
6. The code is **modular** and **organized into logical blocks** with **detailed comments** for clarity.

---

## 📂 Datasets

The repository contains the following datasets in `.csv` format:

- [**Breast Cancer Wisconsin**](breast_cancer_wisconsin.csv)  
- [**Burst Header Packet**](burst_header_packet.csv)  
- [**Image Segmentation**](image_segmentation.csv)  
- [**Iranian Churn**](iranian_churn.csv)  
- [**QSAR Biodegradation**](qsar_biodegradation.csv)  
- [**Seismic Bumps**](seismic_bumps.csv)  
- [**Statlog Australian Credit Approval**](statlog_australian_credit_approval.csv)  
- [**Steel Plates Faults**](steel_plates_faults.csv)  
- [**Waveform Database Generator**](waveform_database_generator.csv)  
- [**Wine Quality Red**](wine_quality_red.csv)

---

## 📬 Contact

<a href="mailto:matheusc_pereira@hotmail.com"><img src="https://img.shields.io/badge/E--mail-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="E-mail"/></a>
<a href="https://www.linkedin.com/in/matheuscostapereira/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://lattes.cnpq.br/7025666927284220"><img src="https://img.shields.io/badge/Lattes-4169E1?style=for-the-badge&logoColor=white" alt="Lattes"/></a>

---

> _Feel free to open issues or PRs, or reach out for collaboration or questions!_
