# Tuberclosis-detection-using-python
This project contains code files for the lung lesion classification and tuberclosis detection from X-ray images using python.  
Tuberculosis is a highly contagious bacterial infection that primarily targets the lungs. According to WHO, TB remains one of the top 10 causes of death worldwide. Radiological imaging, particularly chest X-rays, is a commonly used diagnostic tool for TB. However, manual analysis is time consuming and prone to human error. With the rise of artificial intelligence, automated systems can now aid in efficient diagnosis. This study aims to implement an image classification model for detecting TB using X-ray images, improving  accuracy, and reducing diagnostic delay.
The dataset was preprocessed, split into training and validation sets, and passed through MobileNetV2. The imaging technique used is x-ray and here the differential disease is Tuberculosis.
MobileNetV2, known for its efficiency in resource-constrained devices, was used. The last layer was modified to classify two classes.
A sample chest X-ray was correctly predicted as "TB" with a probability of 52.46%. This indicates the model's capacity to distinguish even borderline cases. 
The model trained over 5 epochs and achieved consistent improvement in loss. Final validation accuracy reached 78.95% with an AUC score of 0.8422. 
