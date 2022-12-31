---
title: "Baseline and Longitudinal Diagnosis of Mild Cognitive Impairment and Alzheimer's Disease using Deep Learning and Risk Scores"
excerpt: "Research project conducted at the Duong Lab. Published in the Journal of Alzheimer's Disease (IF 4.5)."
collection: portfolio
---

Abstract
===

Background: Many neurocognitive and neuropsychological tests are used to classify early mild cognitive impairment (EMCI), late mild cognitive impairment (LMCI), and Alzheimer’s disease (AD) from normal cognition (CN). This can make it challenging for clinicians to make efficient and objective clinical diagnoses. It is possible to reduce the number of variables needed to make a reasonably accurate classification using machine learning. 

Objective: The goal of this study was to develop a deep learning algorithm to identify a few significant neurocognitive tests that can accurately classify these four groups. We also derived a simplified risk-stratification score model for diagnosis. 

Methods: Over 100 variables that included neuropsychological/neurocognitive tests, demographics, genetic factors, and blood biomarkers were collected from 383 EMCI, 644 LMCI, 394 AD patients, and 516 cognitive normal from the Alzheimer’s Disease Neuroimaging Initiative database. A neural network algorithm was trained on data split 90% for training and 10% testing using 10-fold cross-validation. Prediction performance was calculated using area under the curve (AUC) of the receiver operating characteristic analysis. We also evaluated five different feature selection methods. 

Results: The five feature selection methods consistently yielded the top classifiers to be the Clinical Dementia Rating Scale - Sum of Boxes, Delayed total recall, Modified Preclinical Alzheimer Cognitive Composite with Trails test, Modified Preclinical Alzheimer Cognitive Composite with Digit test, and Mini-Mental State Examination. The best classification model yielded an AUC of 0.984, and the simplified risk-stratification score yielded an AUC of 0.963 on the test dataset. 

Conclusion: The deep-learning algorithm and simplified risk score accurately classifies EMCI, LMCI, AD and CN patients using a few common neurocognitive tests.

[Full Paper](https://content.iospress.com/articles/journal-of-alzheimers-disease/jad201438)

Further Impact
===

Alongside this paper, I developed longitudinal machine learning models to predict progression of individuals with neurocognitive disorders over 1 year, 
3 years, and 5 years with high accuracy. Together, this suite of models and their associated simplified risk-stratification scores were tested for their
potential as clinical aids and were effective in supplementing a primary care physician's judgement.
