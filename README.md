# Neuro-Genomics Project
This project focuses on analyzing sequencing data to uncover molecular mechanisms in neurological diseases and evaluate immunotherapy potential in breast cancer.
It includes Python and R scripts for data processing, analysis, and visualization.

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [How to Run the Project](#how-to-run-the-project)
- [Results](#results)
- [License](#license)
- [Contributors](#contributors)

---

## Overview
### Part 1: Bulk Sequencing Analysis
- **Objective**: Analyze RNA-seq data to identify molecular deficiencies in a mouse knockout model.
- **Key Steps**:
  1. Preprocessing RNA-seq data using Python and `kallisto`.
  2. Importing and analyzing transcript-level data in R using `tximport`.
  3. Conducting differential gene expression analysis with `DESeq2`.

### Part 2: Single-Cell Sequencing Analysis
- **Objective**: Predict the effectiveness of immunotherapy for a breast cancer patient.
- **Key Steps**:
  1. Preprocessing single-cell RNA-seq data with `Seurat`.
  2. Clustering cells and identifying cell types based on marker genes.
  3. Visualizing spatial distributions and answering clinical questions.

---

## Technologies Used
- **Languages**: Python, R
- **Tools**: kallisto, tximport, DESeq2, Seurat
- **Visualization**: UMAP, PCA, ggplot2
- **Platforms**: GitHub for version control

---

## File Structure
```
.
├── finel_projet_part1.ipynb   # Python script for preprocessing RNA-seq data
├── genomics_project_Q1.R      # R script for Part 1 - analysis of bulk sequencing
├── genomics_project_Q2.R      # R script for Part 2 - analysis of single cell sequencing
├── Neuro Genomics Project.pdf # Detailed project report
├── neuro-genomics project instructions.pdf # Project instructions
├── README.md                  # Project documentation

```

---

## How to Run the Project
### Prerequisites
- Python 3.x
- R with the following packages installed: kallisto, tximport, DESeq2, Seurat

### Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/12danielLL/Neurogenomics_Project.git
   cd neuro-genomics-project
   ```
2. Install dependencies:
   - Python: `pip install -r requirements.txt`
   - R: Install the required packages manually or use the script `install_packages.R`.
3. Run the Python preprocessing script:
   ```bash
   python scripts/preprocess.py
   ```
4. Execute R scripts for analysis:
   - Bulk analysis: `Rscript scripts/bulk_analysis.R`
   - Single-cell analysis: `Rscript scripts/single_cell_analysis.R`

---

## Results
### Bulk Sequencing Analysis
- Key pathways identified: lipid metabolism, neurological function, and cell structure.
- Potential treatment strategies proposed: supporting myelin production.

### Single-Cell Analysis
- Immune cells comprise over 50% of the biopsy.
- Immune cells are spatially mixed with tumor cells, increasing the likelihood of immunotherapy success.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contributors
- **Daniel Broker**
- **Or Shachar**
