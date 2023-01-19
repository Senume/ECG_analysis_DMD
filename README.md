# ECG_analysis_DMD

## **INTRODUCTION**

Welcome to the research paper implementation repository for ["Analysis of ECG Signals by Dynamic Mode Decomposition"](https://ieeexplore.ieee.org/abstract/document/9626454). This repository contains the code and resources to replicate the implementation of this research paper.

The goal of this project is to diagonis Heart-related diseases using ML models and investigate its overall performance. The approach utilized in the paper evaluate whether the stability of decomposed ECG subsystems can be analyzed in order to effectively investigate the overall performance of ECG signals[^1]. The repository is organized as follows:
1. src
    1. Beat_Frame_FeatureExtraction_Base
    2. ML Training
    3. Pan_Tompkins_Class
    4. Signal_Analysis_Class
    5. ECG_Preprocessing
2. Feature_Extraction
    1. Beats
    2. Frames

To run the code, please make sure you have the necessary dependencies installed, which are listed [here](#DEPENDENCIES)


## **DISCRIPTION**

Here is the file dicription for further future use it.

- You can find the codes implemented under "src" directory, "Miscellaneous" directory under it can be ignored.
    - <u>Beat_Frames_FeaturesExtraction_Base</u> - It contains the code implementation of the  methodology given in the paper. You can use this code to extract features from ECG dataset.
    - <u>ML Training</u> - It contains code of the ML model to train and test its performance.
    - <u>Pan_Tompkins_Class & Signal_Anlaysis_Class</u> - Algorithm need for preprocessing is implemented as a class. It needs to be imported for its use.
    - <u>ECG_Preprocessing</u> - To understand the preprocessing, A code guide is added.
- Extracted Features is also availablein the repository, you can find it under "Feature_Extraction"
    - As given in the paper, Beat-wise and Frame-wish is approach is explained. We can find both the features under "BEAT" and "FRAME" folder.
    
`NOTE: Frame-wise Features need to be excuted again. Frame-wise Features in the file is not promising`

## **THINGS TO BE ADDED**
1. Statistical test.
2. Analysis for Significant Feature 
## **DEPENDENCIES**

To run the code smooth, make sure to install these packages

#### **PYTHON DEPENDENCIES**


- [Python waveform-database (WFDB) package](https://wfdb.readthedocs.io/en/latest/)
- [PyWavelets package](https://pywavelets.readthedocs.io/en/latest/)
- [Python package that uses Dynamic Mode Decomposition](https://mathlab.github.io/PyDMD/)

#### **SUPORTING PYTHON PACKAGES**

- Numpy
- Scipy
- matplotlib
- os
- warnings

#### **LOCAL PYTHON CLASS IMPORT**

- Signal_Analysis_Class

## **Contact**

If you use any of resources from the paper in your own research, please cite the [paper](https://ieeexplore.ieee.org/abstract/document/9626454) using the following citation:

**<u>PLAIN TEXT</u>**
```
H. Niyigena Ingabire et al., "Analysis of ECG Signals by Dynamic Mode Decomposition," in IEEE Journal of Biomedical and Health Informatics, vol. 26, no. 5, pp. 2124-2135, May 2022, doi: 10.1109/JBHI.2021.3130275.
```

**<u>Bib TeX</u>**

```
@ARTICLE{9626454,
  author={Niyigena Ingabire, Honorine and Wu, Kangjia and Amos, Joan Toluwani and He, Sixuan and Peng, Xiaohang and Wang, Wenan and Li, Min and Chen, Jinying and Feng, Yukun and Rao, Nini and Ren, Peng},
  journal={IEEE Journal of Biomedical and Health Informatics}, 
  title={Analysis of ECG Signals by Dynamic Mode Decomposition}, 
  year={2022},
  volume={26},
  number={5},
  pages={2124-2135},
  doi={10.1109/JBHI.2021.3130275}}

```
    

If you use any of the code or resources from this repository in your own research, please also cite the GitHub repository.


If you have any questions or encounter any issues, please feel free to open an issue on this repository or contact the repository authors. We hope that this implementation will be useful for other researchers in the field.

[^1]: Analysis of ECG Signals by Dynamic Mode Decomposition, IEEE Journal of Biomedical and Health Informatics, vol. 26, no. 5, pp. 2124-2135, May 2022, doi: 10.1109/JBHI.2021.3130275.