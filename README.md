## Master_thesis-Job_report_analysis

This repository contains the code and some additional files produced for the final master thesis project on job report analysis.

Author: Dal Zotto Luca

Title: Text Mining and Machine Learning techniques for job report analysis

Supervisor: Bruno Scarpa


### Repository structure

- models:
  folder containing the two best models trained on the original dataset and the corresponding word
  vectorizer.

- putting_into_production:
  folder containing two cleaned notebooks that can be used for the putting into production.
  One is used for hyper-parameters tuning and for training the models, the other is used
  to compute predictions on the new dataset.

- results: 
  folder containing the predictions of the two best models for the new test set.


- 1_Exploration_&_Preprocessing.ipynb -> notebook reporting the exploration and 
					 pre-processing phases.

- 2.1_ML_models_&_FFNN.ipynb -> notebook with the implementation and training procedure of 
			        the Machine Learning models and the FFNN architectures.

- 2.2_RNN_models.ipynb -> notebook with the implementation and training procedure of the RNN

- 2.3_RNN_features_&_dimensionality_reduction.ipynb -> notebook with the implementation and
				training procedure of Gradient Boosting model with the 
				features extracted by the RNN, and with dimensionality 
				reduction approaches.

- 3_Final_test.ipynb -> notebook containing pre-processing and final tests of the best model
			in the new dataset.

