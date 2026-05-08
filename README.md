# CancerUBM: Analysis & Prediction of Oncological Status from Urine Proteomics

**CancerUBM** (Urine-based BioMarkers for Oncological disorders) is a web-based platform designed to discriminate between patients with oncological disorders (primarily related to the urinary tract) and healthy controls using proteomics data from urine samples.
This resource utilizes mass spectrometry-derived intensity values to identify potential biomarkers and provides predictive modeling services for cancer diagnostics.

**Web Server:** [http://webs.iiitd.edu.in/raghava/cancerubm/](http://webs.iiitd.edu.in/raghava/cancerubm/) 

## Citation
Bhalla, S., Chaudhary, K., Gautam, A., Sharma, S., & Raghava, G. P. S. (2018).
A web bench for analysis and prediction of oncological status from proteomics data of urine samples. bioRxiv.

https://doi.org/10.1101/315564

This dataset is also available on Zenodo at

## About the Platform

Urine-based biomarkers offer a non-invasive and easily accessible alternative for cancer management. CancerUBM is built upon a large-scale analysis of the **Human Urinary Peptide Database**, utilizing data from 1,525 oncological samples and 1,503 healthy controls.

* 
**Sample Diversity:** The dataset includes patients with prostate cancer, bladder cancer, renal cancer, Kaposi sarcoma, benign prostatic hyperplasia, and more.


* **Technological Basis:** The platform focuses on **CE/MS** (Capillary Electrophoresis/Mass Spectrometry) data, which is highly suitable for analyzing naturally occurring human urinary peptides.


## Key Features

### 1. Multi-Level Prediction Modules

Users can predict the oncological status of a sample through three distinct interfaces:

* **Mass-CE Spectra:** Predicts status based on spectral details including calibrated molecular mass, normalized CE migration time, and intensity.

* **Peptide Sequence:** Utilizes known amino acid sequences along with spectral intensities.

* **Protein Expression:** Detects status by computing the expression (mean, median, or maximum) of a protein based on the spectral intensities of its constituent peptides.



### 2. Powerful Analysis Tools

The platform facilitates mining of proteomics data at both protein and peptide levels:

* **Protein Level Analysis:** Computes and graphically displays various expression metrics for proteins.

* **Peptide Level Analysis:** Provides a comparison of the user's spectral intensities against the Human Urinary Peptide Database, identifying the individual propensity of specific peptides to act as oncological biomarkers.


### 3. High Performance Machine Learning

The underlying models achieve high accuracy in discriminating oncological samples from healthy ones:

* **Spectra-based Models:** Achieved a maximum accuracy of **91.94%** using a 173-peptide feature set.


* **Peptide-based Models:** Achieved **87.75%** accuracy based on 61 well-annotated peptides.


* **Protein-based Models:** Achieved **85.27%** accuracy by analyzing the average expression of 69 proteins.


## Significant Biomarkers

The study identified nine key proteins whose fragments serve as potent biomarkers for oncological disorders:

* **Collagen Fragments:** Fragments of proteins such as **CO1A1_HUMAN** are more abundant in oncological samples and are strongly linked to tumor growth and angiogenesis.


* **Other Key Proteins:** AIAT_HUMAN, CO1A2_HUMAN, CO3A1_HUMAN, FIBA_HUMAN, HBB_HUMAN, and UROM_HUMAN.


## Applications

* **Early Detection:** Assisting in the discovery of novel biomarkers for early cancer diagnosis.


* **Non-Invasive Diagnostics:** Providing a platform for clinical researchers to analyze urine samples without surgical intervention.


* **Biomarker Validation:** Serving as a definition and validation bench for new urinary biomarkers.




## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.


## Support

The development of CancerUBM was supported by the **Council of Scientific and Industrial Research (CSIR)** and the **Indian Council of Medical Research (ICMR)**, Government of India.
