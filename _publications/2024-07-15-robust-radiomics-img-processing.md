---
title: "Mitigating the impact of image processing variations on tumour [<sup>18</sup>F]-FDG-PET radiomic feature robustness"
collection: publications
category: manuscripts
permalink: /publication/2024-07-15-robust-radiomics-img-processing
excerpt: '👆 This paper investigates how variations in image processing parameters affect the robustness of [<sup>18</sup>F]-FDG PET radiomic features, and demonstrates that applying parameter range conditions and mathematical corrections can improve feature robustness.'
date: 2024-07-15
venue: 'Scientific Reports'
paperurl: 'https://www.nature.com/articles/s41598-024-67239-8'
citation: 'Ramlee, S., Manavaki, R., Aloj, L., & Escudero Sanchez, L. (2024). &quot;Mitigating the impact of image processing variations on tumour [18F]-FDG-PET radiomic feature robustness.&quot; <i>Sci Rep</i>. 14(16294).'
---

Authors: Syafiq Ramlee, Roido Manavaki, Luigi Aloj, & Lorena Escudero Sanchez.


💡 Lay summary
------


- In this paper, we studied how reliable digital measurements (radiomic features) extracted from cancer PET scans are when the images are processed in many different ways (174 ways to be exact!).

- We found that most features, especially those describing textures, are sensitive to how the images are processed, which could limit their use in clinical practice. 

- However, by applying specific limits or simple mathematical corrections, we were able to make many of these features more consistent.

- We also learned that features from melanoma scans were less stable compared to lung cancer and lymphoma scans.

⚙️ Study schema
------

<img src='/images/PerturbationStudy_Fig1.png'>


📝 Abstract
------
Radiomics analysis of [<sup>18</sup>F]-fluorodeoxyglucose ([<sup>18</sup>F]-FDG) PET images could be leveraged for personalised cancer medicine. However, the inherent sensitivity of radiomic features to intensity discretisation and voxel interpolation complicates its clinical translation. In this work, we evaluated the robustness of tumour [<sup>18</sup>F]-FDG-PET radiomic features to 174 different variations in intensity resolution or voxel size, and determined whether implementing parameter range conditions or dependency corrections could improve their robustness. Using 485 patient images spanning three cancer types: non-small cell lung cancer (NSCLC), melanoma, and lymphoma, we observed features were more sensitive to intensity discretisation than voxel interpolation, especially texture features. In most of our investigations, the majority of non-robust features could be made robust by applying parameter range conditions. Correctable features, which were generally fewer than conditionally robust, showed systematic dependence on bin configuration or voxel size that could be minimised by applying corrections based on simple mathematical equations. Melanoma images exhibited limited robustness and correctability relative to NSCLC and lymphoma. Our study provides an in-depth characterisation of the sensitivity of [<sup>18</sup>F]-FDG-PET features to image processing variations and reinforces the need for careful selection of imaging biomarkers prior to any clinical application.

👇 Find our paper here!
------