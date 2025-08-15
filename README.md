# ⚙️ Preprocessing Impact Analysis

## 📝 Description

This repository contains the **Python implementation** used to analyze the impact of different preprocessing strategies on the **predictive performance** and **computational efficiency** of Machine Learning classification models.

The code reproduces the methodology described in the manuscript *Impact of Preprocessing on the Performance and Computational Efficiency of Classification Models: An Analysis of Raw Data, Principal Components, and Factor Analysis*.  
It systematically compares three distinct data construction approaches:

1. **Original Data** — raw dataset without dimensionality reduction.  
2. **Principal Component Analysis (PCA)** — dimensionality reduction using PCA.  
3. **Principal Component Factor Analysis (PCFA)** — PCA combined with Factor Analysis, applying Varimax rotation.

Additionally, the code incorporates **Design of Experiments (DOE)** with factorial design to test different combinations of attributes. Ten datasets from various domains are processed, and ten Machine Learning algorithms are evaluated. All models undergo cross-validation and hyperparameter tuning using two different optimization strategies.

**Note:** This code focuses on the preprocessing and evaluation stages; it does not include extensive visualization routines.

---

## 🛠️ How to Use

1. **Clone or download** this repository or the [`script_preprocessing.ipynb`](script_preprocessing.ipynb) notebook.
2. **Open** the notebook in Jupyter.
3. **Install** the required Python libraries (listed at the beginning of the notebook).
4. **Load** your own datasets or use the provided `.csv` datasets in this repository.
5. **Run** the notebook cells sequentially to reproduce the preprocessing, model training, and evaluation pipeline.
6. The code is modular and organized into logical blocks with detailed comments for clarity.

---

## 📂 Datasets

The repository contains the following datasets in `.csv` format:

- [**breast_cancer_wisconsin.csv**](breast_cancer_wisconsin.csv)  
- [**burst_header_packet.csv**](burst_header_packet.csv)  
- [**image_segmentation.csv**](image_segmentation.csv)  
- [**iranian_churn.csv**](iranian_churn.csv)  
- [**qsar_biodegradation.csv**](qsar_biodegradation.csv)  
- [**seismic_bumps.csv**](seismic_bumps.csv)  
- [**statlog_australian_credit_approval.csv**](statlog_australian_credit_approval.csv)  
- [**steel_plates_faults.csv**](steel_plates_faults.csv)  
- [**waveform_database_generator.csv**](waveform_database_generator.csv)  
- [**wine_quality_red.csv**](wine_quality_red.csv)

---

## 📚 Publications

The methodology implemented here is detailed in the following manuscript (currently under review):

- **Impact of Preprocessing on the Performance and Computational Efficiency of Classification Models: An Analysis of Raw Data, Principal Components, and Factor Analysis**  
  *(Manuscript under review)*

Related publications by the authors include:

- **Multi-objective optimization of CFD simulation costs and quality: Exploring the Pareto frontier** (*Otimização Multiobjetivo de Custos e Qualidade de Simulações de CFD: Explorando a Fronteira de Pareto*)  
  [Read here](https://proceedings.science/sbpo/sbpo-2024/trabalhos/otimizacao-multiobjetivo-de-custos-e-qualidade-de-simulacoes-de-cfd-explorando-a?lang=pt-br)

---

## 📬 Contact

<a href="mailto:matheusc_pereira@hotmail.com"><img src="https://img.shields.io/badge/E--mail-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="E-mail"/></a>
<a href="https://www.linkedin.com/in/matheuscostapereira/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://lattes.cnpq.br/7025666927284220"><img src="https://img.shields.io/badge/Lattes-4169E1?style=for-the-badge&logoColor=white" alt="Lattes"/></a>

---

> _Feel free to open issues or PRs, or reach out for collaboration or questions!_
