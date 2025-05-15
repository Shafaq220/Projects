# Projects

This repository contains different projects.

---

## Table of Contents

1. [Bioinformatics](#bioinformatics)  
2. [Machine Learning](#machine-learning)  
3. [Deep Learning](#deep-learning)     
4. [Contact](#contact)

---

## Bioinformatics

This bioinformatics project, explores the evolutionary lineage of chickens through phylogenetic analysis. The key objective is to determine whether the egg came before the chicken based on genetic and evolutionary data.
**Key Objectives**:
- Protein Sequence Analysis: Retrieve and analyze protein sequence of egg protein of chicken.
- Multiple Sequence Alignment (MSA): Perform multiple sequence alignments to study evolutionary relationships.
- Phylogenetic Tree Construction and Visualization: Construct and visualize phylogenetic trees to understand ancestral lineages.
- Gene Expression Analysis: Analyze gene expression data for insights into evolutionary biology, particularly focusing on neural development.

**Methodology**:
Step 1: Retrieving Protein Sequence
The initial step involves fetching the protein sequence from NCBI using the Entrez tool. For this purpose, the project uses the UniProt ID for chicken ovalbumin
Step 2: Multiple Sequence Alignment (MSA)
Sequences are read from a FASTA file and aligned using the ClustalW method to facilitate evolutionary analysis
Step 3: Phylogenetic Tree Construction
Based on MSA results, a distance matrix is calculated, and a phylogenetic tree is constructed using the neighbor-joining method
Step 4: Phylogenetic Tree Visualization
The phylogenetic tree visualization is enhanced using the ggtree package
Step 5: Gene Expression Analysis
Analyzing gene expression data aids in identifying differentially expressed genes related to neural development. This involves using tools like GEOquery and limma to retrieve and analyze data


---

## Machine Learning
The goal was to use the gene expression data of several Pancreatic ductal adenocarcinoma (PDAC) samples and predict their subtype classification.
• Dataset GSE71729 downloadable from the GEO website

**Key Tasks**:
1. Predict Cancer Subtypes Based on Gene Signatures: the gene expression data from the PDAC primary samples was used to predict cancer subtypes.
Objective: Build a machine learning model that can classify PDAC samples into their respective subtypes based on gene expression patterns.

2. Identify Top N Most Important Genes: identify the most important genes that help distinguish between the different PDAC subtypes. Feature selection techniques like Random Forest feature importance was used to identify the most relevant genes.
Objective: Select the top N genes (e.g., top 10, top 20) based on their importance scores.

3. Build Models Using Only Important Features
Objective: To simplify the model by reducing the number of features and to evaluate how well it performs with a smaller, more focused set of features.

4. Compare the Performance and Stability of Two Prediction Models: compare the performance and stability of two machine learning algorithms

---

## Deep Learning
This project is designed to demonstrate a comprehensive approach to analyzing colorectal cancer data using deep learning techniques. The goal was to distinguish between tumor and normal tissue based on proteomic data, highlighting critical steps in data preprocessing, model selection, hyperparameter tuning, and evaluation.

**Objectives**:
- Developing robust pipeline for processing proteomic data
- Developing neural network models tailored to classify tumor and normal tissues in colorectal cancer research
- Emphasize on careful data preparation, feature engineering, model optimization, and validation to achieve reliable predictive performance
- Use of normalization, structured hyperparameter tuning, and visualization for understanding and enhancing model insights

---

## Contact


