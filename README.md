# ccPDB 2.0: an updated version of datasets created and compiled from Protein Data Bank

**ccPDB 2.0** is an updated and significantly enhanced version of the database of datasets created and compiled from the **Protein Data Bank (PDB)**.
This resource provides researchers with high-quality, non-redundant datasets of various protein properties (such as ligand binding, secondary structure, and metal interactions), serving as a gold standard for training and benchmarking machine learning models in structural biology.

**Web Server:** https://webs.iiitd.edu.in/raghava/ccpdb/

---

## Citation

Agrawal, P., Patiyal, S., Kumar, R., Kumar, V., Singh, H., Raghav, P. K., & Raghava, G. P. S. (2019).
**ccPDB 2.0: an updated version of datasets created and compiled from Protein Data Bank.** *Database*, 2019, bay142.
https://doi.org/10.1093/database/bay142

---

## About the Research

The exponential growth of the Protein Data Bank (PDB) makes it challenging for researchers to manually curate clean, non-redundant datasets for specific structural studies.
ccPDB 2.0 automates this process by systematically categorizing protein structures based on their interactions and structural features.

* **Expansion:** This version includes **41 different types of datasets**, nearly double the amount provided in the initial version.
* **Non-Redundancy:** All datasets are curated at multiple sequence identity thresholds (e.g., 25%, 30%, 40%, etc.) to avoid bias during model training.

---

## Key Features

### 1. Diverse Categories of Datasets

The database categorizes protein information into several major modules:

* **Protein-Ligand Interactions:** Datasets of proteins binding to small molecules, nucleotides (DNA/RNA), and peptides.
* **Metal-Binding Sites:** Specialized collections of proteins interacting with metal ions (e.g., Zinc, Calcium, Magnesium).
* **Structural Properties:** Datasets categorized by secondary structure (Alpha-helix, Beta-sheet) and tertiary folds.
* **Modified Residues:** Information on post-translational modifications and non-standard amino acids.

### 2. High-Quality Data Curation

* **Residue-Level Information:** Provides detailed information on interacting residues, including their distance from ligands and biological context.
* **Structure Validation:** Only high-resolution structures are included to ensure the reliability of the derived datasets.

### 3. Integrated Computational Tools

ccPDB 2.0 offers several web-based utilities for structural analysis:

* **Dataset Downloader:** Allows users to download customized, non-redundant datasets for specific research needs.
* **Structure Analysis:** Tools to analyze the geometry and physicochemical properties of binding sites.
* **Search & Browse:** Advanced query options to find proteins based on resolution, R-factor, and specific ligand types.

---

## Applications

* **Machine Learning:** Providing benchmark datasets for developing algorithms to predict protein-ligand binding and secondary structure.
* **Drug Discovery:** Analyzing conserved binding patterns across various protein families to design better inhibitors.
* **Structural Bioinformatics:** Studying the evolutionary conservation of specific structural motifs and metal-binding sites.

---

## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.

---

## Support

The development of ccPDB 2.0 was supported by the **Department of Biotechnology (DBT)** and the **Council of Scientific and Industrial Research (CSIR)**, Government of India. 
