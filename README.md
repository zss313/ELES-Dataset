== SSN: Shift Suppression Network for Endogenous Shift of Photovoltaic Defect Detection

Electroluminescence (EL) Endogenous Shift (ELES) dataset is the first endogenous domain shift benchmark of photovoltaic manufacturing scenarios. Due to the differences in intrinsic mechanisms or hardware components of the imaging systems of different types of imaging conditions, there are subtle perturbations in EL images generated by different quality inspection production line, which cause the endogenous shift.

## 2023 Dataset Access Instructions:
We collected three sets of EL data (EL group 1, EL group 2, and EL group 3) at different times during the production line update process of the same manufacturer. In this study, EL group 1 is used for training the detector, and the other two are used for the test. To efficiently test PV modules, we slice a PV module based on the unit of 2 cells and spliced it into a complete module after the detection. Combined with deep learning technology and with the assistance of multiple experts, we meticulously annotate all defects. The dataset contains a total of $16,323$ EL PV images. 

| Number of defects | Training | Testing |  |  | Total |  
|-|-|-|-|-|-|
|  | EL<br>group 1 | EL<br>group<br>1 | EL<br>group<br>2 | EL<br>group<br>3 |  |
| broken gate | 2060 | 376 | 909 | 335 | 1620 |
| unjoined<br>weld | 1336 | 227 | 1167 | 275 | 1669 |  
| black spot | 1976 | 337 | 833 | 270 | 1440 |
| crack | 1692 | 259 | 187 | 62 | 508 |
| scratch | 1920 | 299 | 1011 | 257 | 1567 |



## Download Dataset

If you want to access the dataset, please read the ELES-Dataset Request Form in this folder carefully, sign the corresponding commitment file and send it to 202012801003@stu.hebut.edu.cn.

EDS dataset consists of:

  * 3 different domains

  * Altogether 16,323 EL images


