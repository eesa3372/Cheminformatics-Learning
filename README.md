# Cheminformatics & Chemical Data Science Portfolio

This repository serves as a structured log of my journey into digital chemistry, machine learning for molecular property prediction, and computational pipeline development. 

## 🛠️ Core Stack & Tooling
- **Chemistry Toolkits:** RDKit (Molecular manipulation, sanitization, structural rendering)
- **Machine Learning & Deep Learning:** DeepChem, Scikit-Learn
- **Data Management:** Pandas (with RDKit PandasTools), NumPy

## 📂 Repository Roadmap & Key Concepts Covered

### 1. Molecular Representation & Featurization
- Converting structural notations (**SMILES, InChI**) into computable digital objects.
- Generating **Extended-Connectivity Fingerprints (ECFP / Circular Fingerprints)** for traditional machine learning algorithms.
- Representing molecules as geometric graphs (**GraphConv**) for Graph Neural Networks (GNNs).

### 2. Specialized Data Engineering for Chemistry
- **Data Sanitization:** Cleaning raw chemical datasets, validating valence rules, and managing implicit vs. explicit Hydrogens to avoid runtime failures.
- **Advanced Data Splitting:** Utilizing **Scaffold Splits (Bemis-Murcko scaffolding)** instead of traditional random splits to test model generalization on entirely novel chemical structures.

### 3. Predictive Modeling (QSAR / QSPR)
- Building quantitative structure-property relationship pipelines.
- Predictive workflows modeled on benchmark datasets (e.g., Delaney Aqueous Solubility, toxicity screening).
