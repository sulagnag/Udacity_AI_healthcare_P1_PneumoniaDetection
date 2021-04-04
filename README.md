# Udacity_AI_healthcare_P1_PneumoniaDetection
Pneumonia Detection from Chest X-rays and FDA submission

## Problem description
The task is to analyze data from the NIH Chest X-ray Dataset and train a CNN to classify a given chest x-ray for the presence or absence of pneumonia. The project will culminate in a model that can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. As part of the submission preparation, we need to formally describe the model, the data that it was trained on, and a validation plan that meets FDA criteria.

## The Dataset
NIH Chest Xray Dataset - 112,000 chest x-rays with disease labels acquired from 30,000 patients. The disease labels were created using Natural Language Processing (NLP) to mine the associated radiological reports. The labels include 14 common thoracic pathologies:

1. Atelectasis
2. Consolidation
3. Infiltration
4. Pneumothorax
5. Edema
6. Emphysema
7. Fibrosis
8. Effusion
9. Pneumonia
10. Pleural thickening
11. Cardiomegaly
12. Nodule
13. Mass
14. Hernia
The biggest limitation of this dataset is that image labels were NLP-extracted so there could be some erroneous labels but the NLP labeling accuracy is estimated to be >90%.

The original radiology reports are not publicly available but you can find more details on the labeling process here.

**Dataset Contents:**
112,120 frontal-view chest X-ray PNG images in 1024*1024 resolution (under images folder)
Meta data for all images (Data_Entry_2017.csv): Image Index, Finding Labels, Follow-up #, Patient ID, Patient Age, Patient Gender, View Position, Original Image Size and Original Image Pixel Spacing.

## Getting Started - installations
Python packages
- python 3.6
- numpy
- tensorflow
- keras
- pandas
- matplotlib
- sklearn

## Execution
This project would require GPUs to train the deep learning model.

Note: I have not uploaded the hdf5 file, the weights of the trained model since its a big file.
