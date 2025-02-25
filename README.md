# Seurat and Kodama Analysis of HER2+ Breast Cancer Samples

This repository contains an R Markdown file for analyzing **HER2-positive breast cancer (BC) samples** using **Seurat** for single-cell RNA sequencing (scRNA-seq) analysis and **Kodama** for nonlinear dimension reduction.

## **Overview**  
This project performs **quality control, normalization, clustering, differential expression analysis**, and visualization of HER2+ BC samples using **Seurat**, followed by **nonlinear feature extraction using Kodama**.

## **Features**  
- **Preprocessing:** Quality control, filtering, and normalization  
- **Clustering:** Cell-type clustering and annotation  
- **Differential Expression Analysis:** Identifying marker genes  
- **Visualization:** UMAP, t-SNE, violin plots, and Kodama feature extraction  
- **Integration:** Merging multiple datasets if applicable  

## **Getting Started**  

### **1. Install Required Packages**  
Before running the analysis, install the necessary R packages:  
```r
install.packages("Seurat")
install.packages("ggplot2")
install.packages("dplyr")
install.packages("patchwork")
install.packages("devtools")
devtools::install_github("mesteban/Kodama")
