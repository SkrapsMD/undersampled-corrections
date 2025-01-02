# undersampled-corrections
Comprehensive implementation and analysis of probability calibration techniques for imbalanced classification problems. Based on Dal Pozzolo et al (2015), we extend the theoretical framework to multiple machine learning classifiers.


Presently, either the code is wrong or the correction term proposed by Dal Pozzolo et el is wrong. We show that we are getting worse results after the correction term is introduced on our synthetic dataset than before. They validate their classification improvements without losing accuracy, we lose both accuracy and classification quality in this example. Next step is to simply replicate their code, and then ontop of thier posteriors place some classifiers. 
