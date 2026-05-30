# Cheminformatics & Chemical Data Science Portfolio

This repository documents my development of computational pipelines for drug discovery, leveraging data science to solve complex chemical problems.

## 🧪 Featured Project: Automated Lead-Likeness Profiling
*A high-impact virtual screening pipeline for Acetylcholinesterase inhibitors.*

- **Data Engineering:** Managed 743+ compounds from the ChEMBL database, performing sanitization and standardized $pIC_{50}$ calculations.
- **Drug-Likeness Validation:** Applied Lipinski’s Rule of Five; 93% of the library was validated as drug-like.
- **Potency-Complexity Insights:** Identified a critical potency trade-off—"1-violation" molecules exhibited higher average potency ($\text{pIC}_{50}$ 6.35) compared to "0-violation" molecules ($\text{pIC}_{50}$ 5.72), guiding a nuanced lead selection strategy.

---

## 🛠️ Core Stack & Tooling
- **Chemistry Toolkits:** RDKit (Molecular manipulation, sanitization, structural rendering)
- **Machine Learning & Deep Learning:** DeepChem, Scikit-Learn
- **Data Management:** Pandas (with RDKit PandasTools), NumPy

## 📂 Repository Roadmap & Key Concepts
### 1. Molecular Representation & Featurization
- Converting structural notations (SMILES, InChI) into computable digital objects.
- Generating ECFP (Circular Fingerprints) for traditional machine learning.
- Representing molecules as geometric graphs (GraphConv) for GNNs.

### 2. Specialized Data Engineering for Chemistry
- **Data Sanitization:** Managing implicit/explicit hydrogens and validating valence rules.
- **Advanced Data Splitting:** Utilizing **Bemis-Murcko Scaffold Splits** to test model generalization on novel chemical structures.

### 3. Predictive Modeling (QSAR / QSPR)
- Building quantitative structure-property relationship pipelines.
- Predictive workflows modeled on benchmark datasets (e.g., Delaney Aqueous Solubility, toxicity screening).
