### IDH1 Mutation and 1p19q co-deletion prediction from MRI for brain cancer.
#### by Sourav Singh, Rasika Mahadeshwar, Manali Bhavsar and Sumeet Rathod 

+++

@snap[midpoint]
under guidance from Prof. (Ms.) Disha S. Wankhede
in collaboration with Tata Memorial Centre, Mumbai

---

### Introduction

The presentation talks about brain cancer and how deep learning can help in the diagnosis of brain cancer. There are terms which may/may not be understood, so they are included at the end as a Glossary.  
---
### Motivation

- Patients with brain cancer aren't so lucky.
- Mean and median survival for a patient with brain cancer is 15 and 16 months upon getting treatment.
- India is third largest in number of incident cases of brain cancer. [Reference](https://tinyurl.com/rohotp4)
- Timely diagnosis and treatment is important to combat brain cancer.
- Machine learning can help in quick diagnosis of brain cancer and has been used before.

---

- Knowing genetic mutations and co-deletions of chromosomes can help guide the treatment.
- Checking genetic mutations and co-deletions require complicated tests(immunoassays, sequencing, FISH).
- Cost money and time.

---

### Existing Systems and their limitations

- Current systems use 2D CNNs or ML methods to classify genetic mutation type for IDH1- wildtype vs mutant.
- 1p19q co-deletions- Normal or deleted.
- Current systems do not take into account the volumetric space of brain tumor.
- ML methods are limited by the features obtained from MRI.
- Current systems have only been trained on brain images which are taken from patient trials at America/Europe.

--- 

### Proposed system

- System will make use of brain MRI scans of various modalities as input.
- The input will be checked for file format type, parity and stuff.
- 3D ConvNet will obtain volumetric features and use it to classify tumor type and co-deletion status.

---

### Purpose

- Help diagnosticians in knowing mutation and co-deletion status.
- Drive treatment protocol in a useful manner.
- Alleviates need for complicated lab tests.

---

### Scope

- Make use of MRI scans of brain to predict mutation and co-deletion status.
- Improve accuracy by tuning and experimenting model, obtaining more data or generating data.
- Make the system easy to use for doctors.

---

### Techniques and APIs for mutation and co-deletion status prediction

- Tensorflow, PyTorch
- 3D Convolutions
- DenseNets to obtain features
- Classification

---

### Literature Survey

#### Imaging patterns predict patient survival and molecular subtype in glioblastoma via machine learning techniques

Summary- Uses SVM classifier with T1, T1-Gd, T2, T2-FLAIR and DTI MRI images on 120 features
consisting of location of tumor, intensities of tumor in each -of the imaging scans
which gave Accuracy for retrospective study= 77.14 % SVM Accuracy for
prospective study=79.17%

Advantages:
- Is easy to implement
- Uses features which can be easily extracted

Disadvantages:
- Can be prone to outliers
- Gives less accuracy compared to other methods.

+++

#### Deep Learning based Radiomics (DLR) and its usage in noninvasive IDH1 prediction for low grade glioma

Summary- Uses 2D Convolutional Neural Networks (CNN) and SVM classifier
with the modalities T1-contrast and T2-FLAIR MRI on training(60) + test(59)
features which resulted into AUC score for CNN= 0.92 AUC score for SVM=
0.86

Advantages-
- Uses CNNs for feature extraction

Disadvantages-
- Can be difficult to implement
- Uses Fisher vectors, which can lead to storage as well as I/O issues. 

+++

#### Radiogenomics of Glioblastoma: Machine Learning–based Classification of Molecular Characteristics by Using Multiparametric and Multiregional MR Imaging Features

Summary- Uses Random Forest, Gradient Boosting and Oversampling techniques to obtain information about IDH1 mutation. Uses features such as total tumor volume, necrotic tumor volume, contrast-enhancing tumor volume etc. Accuracy of 88% on random forest, 87% on gradient boosting.

Advantages-
- Uses features which can be calculated easily
- Uses ML techniques

Disadvantages-
- Require computational resources if data is large

---

### Flow of project

Add image here

---

### Requirements

#### Hardware

- PC with Intel processor(minimum 2Ghz clock)
- Atleast 500GB HDD
- Nvidia GPU for deep learning(2GB bare minimum, more would be better)
- 16 GB RAM

+++

#### Software

- Python, R for programming, data analysis and statistical computing.
- Tensorflow, PyTorch for making deep learning models
- VTK and ITK for reading MRI scans and analysing them.
- Anaconda package manager for managing packages
- Linux OS 

---

### References

- [1] Macyszyn, Luke, et al. "Imaging patterns predict patient survival and molecular
subtype in glioblastoma via machine learning techniques." Neuro-oncology 18.3
(2015): 417-425.

- [2]Li, Zeju, et al. "Deep Learning based Radiomics (DLR) and its usage in
noninvasive IDH1 prediction for low grade glioma." Scientific reports 7.1 (2017):
5467.

- [3] Zhang, Xi, et al. "Radiomics strategy for molecular subtype stratification of lowergrade glioma: detecting IDH and TP53 mutations based on multimodal MRI." Journal
of Magnetic Resonance Imaging 48.4 (2018): 916-926.

+++

- [4] Kickingereder, Philipp, et al. "Radiogenomics of glioblastoma: machine learning–
based classification of molecular characteristics by using multiparametric and
multiregional MR imaging features." Radiology 281.3 (2016): 907-918.

- [5] (IJITEE) ISSN: 2278-3075, Volume-8 Issue-6, April 2019:- Predicting Survival of
Brain Tumor Patients using Deep Learning.

- [6] 2017 IEEE 17th International Conference on Bioinformatics and Bioengineering:-
Machine Learning and Deep Learning Techniques to Predict Overall Survival of
Brain Tumor Patients using MRI ImagesMachine Learning and Deep Learning
Techniques to Predict Overall Survival of Brain Tumor Patients using MRI Images

+++

- [7] (ICCTCEEC-2017):- An Automated Approach for Brain Tumor Identification using
ANN Classifier

- [8] Journal of Cancer Research and Experimental Oncology Vol. 2(1) pp. 006-014,
March, 2010:- An improved implementation of brain tumor detection using
segmentation based on soft computing.

----

### Glossary of terms

IDH1- A gene which controls info for creating isocitrate dehydrogenase enzyme, which helps produce
NADPH(Nicotinamide adenine dinucleotide phosphate) for breakdown of fat and protect body from free radicals in an indirect manner.
Mutation of this gene can be a cause increase in methylation process in brain tumor cells.

+++

1p19q co-deletion- Gene Deletion of the short arm or chromosome 1 and long arm of chromosome 19 refers to 1p19q co-deletion.
This is a signature of specialized brain tumor type called oligodendroglioma. Are predominantly present in adult tumors and tend to resent with seizures

+++

Modalities- MRI modalities uses various modes for diagnosing the disease
- T1-Contrast Enhanced: Uses Gadolinium to highlight fat tissues with contrast.
- T2-fluid-attenuated inversion recovery: Supresses signals from CSF and show contrast between white and gray matter.

----

Thank you!

---
