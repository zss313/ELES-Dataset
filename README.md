# SSN: Shift Suppression Network for Endogenous Shift of Photovoltaic Defect Detection

Electroluminescence (EL) Endogenous Shift (ELES) dataset is the first endogenous domain shift benchmark of photovoltaic manufacturing scenarios. Due to the differences in intrinsic mechanisms or hardware components of the imaging systems of different types of imaging conditions, there are subtle perturbations in EL images generated by different quality inspection production line, which cause the endogenous shift.

## 2023 Dataset Access Instructions:
We collected three sets of EL data (EL group 1, EL group 2, and EL group 3) at different times during the production line update process of the same manufacturer. In this study, EL group 1 is used for training the detector, and the other two are used for the test. To efficiently test PV modules, we slice a PV module based on the unit of 2 cells and spliced it into a complete module after the detection. Combined with deep learning technology and with the assistance of multiple experts, we meticulously annotate all defects. The dataset contains a total of $16,323$ EL PV images. 


![image](https://github.com/zss313/ELES/blob/main/motivation.png)

| Number of defects  | EL group 1 | EL group 2 | EL group 3 | Total |
| :---: | :---: | :---: | :---: | :---: |
| broken gate | 2436 | 909 | 335 | 1620 |
| unjoined weld | 1563 | 1167 | 275 | 1669 |
| black spot | 2313 | 833 | 270 | 1440 |
| crack | 1951 | 187 | 62 | 508 |
| scratch | 2219 | 1011 | 257 | 1567 |


<be />

| Datasets | EL group 1 | EL group 2 | EL group 3 |
| :---: | :---: | :---: | :---: |
| Number of defective image | 7762 | 3209 | 839 |
| Number of defect-free image | 1410 | 2541 | 562 |
| Total | 9172 | 5750 | 1401 |
| Acquisition time | September 2020 | May 2021 | October 2021 |
| Resolution | 384 x 384 | 640 x 589 | 700 x 668 |



## Download Dataset

If you want to access the dataset, please read the ELES-Dataset Request Form in this folder carefully, sign the corresponding commitment file, and send it to 202012801003@stu.hebut.edu.cn.

EDS dataset consists of:

  * 3 different domains

  * Altogether 16,323 EL images


