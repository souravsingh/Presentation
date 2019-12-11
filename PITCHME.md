### IDH1 Mutation and 1p19q co-deletion prediction from MRI for brain cancer.
#### by Sourav Singh, Rasika Mahadeshwar, Manali Bhavsar and Sumeet Rathod 

+++

@snap[midpoint]
under guidance from Prof. (Ms.) Disha S. Wankhede
in collaboration with Tata Memorial Centre, Mumbai

---

### Introduction

+++

![IMAGE](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQhB0p2sa8bGLZBCaYKEIOOSYCT17lAXvEbPDSwdlcl66ecd4VQ)

+++

![IMAGE](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQeDsR3qNq1hZGmdYEfIeHA58IYlppQwaaJg2bT1ErGCUIofYVY)

+++

![IMAGE](https://raw.githubusercontent.com/fperez/blog/master/fig/johnhunter-head.jpg)

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

- Add image here

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

----

### Glossary of terms

-IDH1- A gene which controls info for creating isocitrate dehydrogenase enzyme, which helps produce
NADPH(Nicotinamide adenine dinucleotide phosphate) for breakdown of fat and protect body from free radicals in an indirect manner.
Mutation of this gene can be a cause increase in methylation process in brain tumor cells.

+++

- 1p19q co-deletion- Gene Deletion of the short arm or chromosome 1 and long arm of chromosome 19 refers to 1p19q co-deletion.
This is a signature of specialized brain tumor type called oligodendroglioma. Are predominantly present in adult tumors and tend to resent with seizures

+++

- Modalities- MRI modalities uses various modes for diagnosing the disease
    - T1-Contrast Enhanced: Uses Gadolinium to highlight fat tissues with contrast.
    - T2-fluid-attenuated inversion recovery: Supresses signals from CSF and show contrast between white and gray matter.

+++

- VTK- Visualization Toolkit is a open-source software for visualizing and processing 2D as well as 3D images.
- ITK- Imaging toolkit is an open source tool used for checking and processing brain images.

---

Thank you!

---
