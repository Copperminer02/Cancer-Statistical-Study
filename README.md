# FinalProject_050322_Breast Cancer

## Background

- Breast cancer is the most common type of cancer among women, accounting for nearly 1 in 3 cancers diagnosed among women in the United States. It is the second leading cause of cancer deaths among women. 

- Breast cancer occurs as a results of abnormal growth of cells in the breast tissue, commonly referred to as a tumor. Tumors can be benign (not cancerous), pre-malignant (pre-cancerous), or malignant (cancerous).

- Masses are characterized on the basis of their shape, margins, and internal enhancement patterns: 
    -	radius (mean of distances from center to points on the perimeter)
    - texture (determines heterogeneity of intratumor matter as a marker of malignancy; can be described as rough, smooth, silky, bumpy as a function of   spatial variation in pixel intensities)
    - perimeter (determine shape—round, oval, irregular)
    - area (measures space inside the mass margins)
    - smoothness (local variation in radius lengths)
    - compactness (measure denseness of the mass--calculated as: perimeter^2 / area - 1.0)
    - concavity (severity of concave portions of the contour that are curved like the inner surface of a sphere)
    - concave points (number of concave portions of the contour found within the mass)
    - symmetry (breast tissue in question looking similar to other breast—asymmetry is correlated to malignancy)
    - fractal dimension (used in characterizing shape/perimeter and texture)

## Breast Cancer Diagnostics

- Tests such as MRIs, mammograms, ultrasounds and biopsies are commonly used to diagnose breast cancer. MRI adds important three-dimensional information about the lesion, by looking at the above mentioned enhancement parameters.
    
- Imaging of the breast for breast cancer detection aims to fulfill two major goals: high sensitivity for detection of breast lesions and reliable differentiation of benign from malignant lesions (specificity). 

- Whereas the sensitivity of breast MRI is usually very high, specificity—as in all breast imaging modalities—depends on many factors such as reader  expertise, use of adequate techniques and composition of the patient cohorts. 

## Machine Learning and Breast Cancer

- Machine learning can extract high-throughput features of lesions that are imperceptible to human eyes, learn the characteristics of lesions, and make a diagnosis based on them using computer-aided technology 

- Such multiparametric assessment of breast lesions allows for excellent discrimination between benign and malignant breast lesions. 

## Purpose

- This analysis aims to observe which features are most helpful in predicting malignant or benign cancer and to see general trends that may aid us in future analysis.

