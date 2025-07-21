**Cat vs Dog Image Classification Using SVM**
In this project, I developed an image classification model to distinguish between cats and dogs using Support Vector Machines (SVM) and GridSearchCV for hyperparameter tuning. The workflow included:

* Data Preprocessing: Loaded image data from the Cats vs Dogs dataset, resized each image to 150x150 pixels, and flattened them for SVM input.

* Label Encoding: Labeled the data with binary targets (0 for cats, 1 for dogs).

* Model Training: Trained an SVM classifier with the RBF kernel and enabled probability estimates for later use with predict_proba().

* Hyperparameter Tuning: Applied GridSearchCV to explore combinations of C, gamma, and kernel parameters to identify the optimal configuration.

* Performance Evaluation: Evaluated model performance using accuracy and probability predictions.
