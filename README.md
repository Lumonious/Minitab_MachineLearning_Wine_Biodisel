# Minitab_MachineLearning_Wine_Biodisel

# Chemometrics Final Exam Projects

This repository contains the projects for the "Introduction to Chemometrics" final exam (CHEM 353), completed by Nurefşan Nazlı Yüzükırmızı. The repository includes two distinct data analysis projects applying key chemometric techniques to chemical datasets.



## 🍷 Project 1: Phenolic Composition Analysis of Wine Samples using PCA

This project explores the classification of wine samples from three distinct geographical regions based on their chemical makeup.

### Objective

The primary goal was to use **Principal Component Analysis (PCA)** to reduce the dimensionality of the dataset and classify wine samples based on their phenolic profiles[cite: 25]. [cite\_start]The study aimed to identify key compounds that differentiate the regions and evaluate the effectiveness of PCA for wine profiling[cite: 25].

### Dataset

  * The dataset contains measurements of **13 phenolic compounds** for **178 wine samples**[cite: 11, 12].
  * The samples originate from three distinct geographical areas: Region A (59 samples), Region B (71 samples), and Region C (48 samples)[cite: 34, 35, 36].
  * A balanced subset of 30 samples from each region was randomly selected for the analysis[cite: 13, 37].

### Methodology

1.  **Data Sub-sampling**: 30 samples from each of the three regions were randomly selected using Excel's "Random Number Generator"[cite: 39].
2.  **PCA Implementation**: Principal Component Analysis was performed in Minitab using the 13 phenolic compounds as variables[cite: 1167, 1168].
3.  **Analysis**: The resulting score plots and loading plots were analyzed to identify sample groupings and determine which phenolic compounds contributed most to the variation between regions[cite: 1171].

### Results

  * **Score Plot**: The analysis revealed distinct clusters for the different regions. [cite\_start]Region A samples were well-separated, while regions B and C showed some overlap, suggesting similar viticultural or environmental conditions[cite: 1174, 1175].
  * **Loading Plot**: Phenolic compounds **X3, X5, and X9** were identified as the primary drivers of regional separation due to their high loadings[cite: 1181].
  * **Conclusion**: PCA proved to be a powerful tool for classifying wines and identifying the chemical markers responsible for regional differences[cite: 1227, 1229].

-----

## ⛽ Project 2: Multivariate Calibration of Biodiesel Mixtures using PLS

This project focuses on predicting the concentration of components in biodiesel mixtures using spectroscopic data.

### Objective

The main goal was to develop and evaluate a **Partial Least Squares (PLS) regression model** to predict the concentrations of sunflower oil, biodiesel, and petroleum diesel in ternary mixtures from their Fourier Transform Infrared (FTIR) absorbance spectra[cite: 1237]. The performance of the PLS model was benchmarked against simple linear regression[cite: 1238].

### Dataset

  * The dataset comprises **FTIR absorbance spectra** for 47 ternary mixtures and 3 pure components (sunflower oil, biodiesel, and petroleum diesel)[cite: 1254].
  * The data was randomly split into a **calibration set** (32 mixtures) and a **validation set** (15 mixtures) to build and test the model[cite: 1255].

### Methodology

1.  **Data Splitting**: The dataset was randomly divided into calibration and validation sets in Excel[cite: 1258].
2.  **PLS Regression**: A PLS model was built in Minitab with the FTIR spectra as predictors and the component concentrations as responses[cite: 1262]. [cite\_start]The optimal number of components was determined using cross-validation[cite: 1263].
3.  **Model Evaluation**: The model's performance was assessed using the Standard Error of Cross-Validation (SECV), Standard Error of Prediction (SEP), and analysis of residual plots[cite: 1240, 1264].

### Results

  * **PLS Model Performance**: The PLS model demonstrated high accuracy in predicting the concentrations of all three components, yielding low error rates[cite: 1239].
      * **Sunflower Oil**: SECV = 2.40, SEP = 1.86 [cite: 1266]
      * **Biodiesel**: SECV = 1.86, SEP = 0.73 [cite: 1266]
      * **Petroleum Diesel**: SECV = 2.86, SEP = 2.13 [cite: 1266]
  * **Comparison**: The PLS model significantly outperformed simple linear regression, which failed to capture the complex multivariate relationships in the spectral data[cite: 1275, 1282].
  * **Conclusion**: PLS regression is a highly effective and reliable method for analyzing FTIR spectra in fuel quality control, showcasing the importance of advanced chemometric techniques[cite: 1281, 1284].
