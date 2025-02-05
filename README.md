# Depression Detection 


## Link to the Project : https://colab.research.google.com/drive/1hJpytWoGEFDBZRIjDl6sPxcmX8Vrep1o?authuser=3


## Summary of the Project 
Depression, a pervasive mental health condition, continues to impose a significant  burden on individuals and society at large. In response to this pressing concern,this  research endeavors to provide an advanced solution for the detection of depressive  symptoms through the analysis of electroencephalogram(EEG) biomarkers.  Leveraging the capabilities of the MNE library in Python, this study explores a novel  methodology for discerning depression indicators from EEG recordings. 


The dataset utilized comprises EEG recordings collected from 181 patients at HUSM  Hospital. The preprocessing pipeline involves bandpass filtering to enhance signal  clarity and reduce noise inference. Subsequently, essential features including Alpha,  Beta and Theta band powers as well as indices such as Alpha Power Variation,  Relative Gamma Wave and Spectral Asymmetry Index are extracted from the  preprocessed EEG data. These features serve as input variables for training four  distinct models - Support Vector Machine (SVM), K-Nearest Neighbors (KNN),  Decision Tree and Logistic Regression. Utilizing a supervised learning paradigm,  these models are rigorously tested to ascertain their accuracy in depression detection  when presented with similar EEG datasets. 

This comprehensive approach aims to not only identify EEG biomarkers associated  with depression but also to construct predictive models capable of reliably distinguishing individuals exhibiting depressive symptoms at an early stage. Through  the fusion of EEG data analysis and supervised learning methodologies, this research  contributes to the burgeoning field of computational psychiatry, offering a robust  framework for depression detection. The findings of this research hold significant  promise for enhancing early detection and personalized management of depression,  thereby advancing mental health care practices.

## Tech-Stack Used : 
    MNE Python Library - MNE-Python is an open-source Python module for processing, analysis, and visualization of functional neuroimaging data.

## Results
The validation of the depression detection project using EEG biomarkers reveals  significant insights into the effectiveness and applicability of various machine  learning models for this task. Each model exhibits unique strengths and limitations,  as evidenced by their performance metrics—accuracy, precision, recall, and F1- score. These metrics not only offer a comprehensive understanding of each model's  predictive capability but also inform the selection of the most suitable model for  real-world applications in clinical settings. 

Random Forest Classifier emerges as the most proficient model with the highest  overall accuracy of 88.39%. Its balanced precision and recall scores for both classes  (non-depressed and depressed) suggest a robust capability to generalize across  diverse data samples. The model's high F1-scores further indicate a harmonious  balance between precision and recall, making it a reliable choice for accurately  diagnosing depression through EEG signals. 

K-Nearest Neighbors (KNN), while demonstrating a lower accuracy of 76.60%  compared to Random Forest.
Decision Tree Classifier presents a compelling case with an accuracy of 84.32%.
Logistic Regression showcases an enhanced model accuracy of 74.09%.
Support Vector Machine (SVM), with a model accuracy of 78.67%.

In conclusion, the validation of these models underscores the potential of machine  learning in augmenting the detection and diagnosis of depression using EEG  biomarkers. 
