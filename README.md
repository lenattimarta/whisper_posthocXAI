# whisper_posthocXAI
Python codes (v 3.8.7) for training and evaluation of machine learning models for hearing loss detection through speech-in-noise testing and post-hoc explainability analysis applied to non-natively explainable models (e.g., Random Forests).  
## Contents
* [General info](#general-info)
* [Technologies](#technologies)

### General info
This repository includes:
- a Python notebook for the training and evaluations of natively (Decision Tree) and non-natively (Random Forest) models for hearing loss detection based on a set of features extracted from the execution of a speech-in-noise test.
- a Python notebook with post-hoc explainability techniques (feature permutation importance, SHapley Additive exPlanations (SHAP), and Partial Dependence Plot (PDP)) applied to the best performing random forest model.
- a sample of synthetic data generated with a Generative Adversarial Network (GAN)
	
### Technologies
Project is created with:
* sklearn: 1.0.1
* Pickle: 4.0
* Pandas: 1.1.5
* Numpy: 1.19.5
* shap: 0.39.0
* eli5: 0.11.0
* seaborn: 0.11.1
* matplotlib: 3.4.2
### Notes
Results obtained with synthetic data may not coincide with published results on real data.
