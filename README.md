# DL-Multilabel-Classification-PDD
This is a repository for CS 598 DL4H that attempts to replicate recently published work in deep learning for healthcare with a focus on Multi-label classification for psychotic disorder diseases.

The main goal of this repository is to attempt to replicate some of the findings by implementing baseline and proposed models stated in the paper "*Application of deep and machine learning techniques for multi-label classification performance on psychotic disorder diseases*"[[1](https://www.sciencedirect.com/science/article/pii/S2352914821000356)]. All the work is done in the single Jupyter Notebook file.

## Data
The data that was used is provided as supplementary data. This dataset can be located [here](https://www.sciencedirect.com/science/article/pii/S2352340917303487) under Appendix A of the paper "*Quantitative exploration of factors influencing psychotic disorder ailments in Nigeria.*"[[2](https://www.sciencedirect.com/science/article/pii/S2352340917303487)].

## Steps
1. Converted multi-label classification problem into conventional multi-classification problem.
2. Perfomed One-hot-vector encoding of the categorical variables
3. Implemented SMOTE for generating Synthetic Samples
4. Model training, prediction and comparison

### References
[[1](https://www.sciencedirect.com/science/article/pii/S2352914821000356)] Israel Elujide, Stephen G. Fashoto, Bunmi Fashoto, Elliot Mbunge, Sakinat O. Folorunso, and Jeremiah O. Olamijuwon. 2021. Application of deep and machine learning techniques for multilabel classification performance on psychotic disorder diseases. Informatics in Medicine Unlocked, 23:100545

[[2](https://www.sciencedirect.com/science/article/pii/S2352340917303487)] O Adejumo Adebowale, Nehemiah A Ikoba, Suleiman Esivue A, Okagbue Hilary I, Oguntunde Pelumi E, Odetunmibi Oluwole A, Job Obalowu. Quantitative exploration of factors influencing psychotic disorder ailments in Nigeria. Data in Brief 2017;14:175–85. 
