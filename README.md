This repository contains various Jupyter notebooks and accompanying materials for conducting extensive CNN-based experiments on ResActionsImages datasets, with a focus on tackling overfitting and improving model performance through several techniques.

Contents:

1) full_experimentation_on_ResActionsImagesM_with_CNNs.ipynb.

   - Conducts around 20 experiments on the ResActionsImagesM dataset.
   - Covers data preprocessing, class weighting, L2 regularization, dropout, cross-validation, and many other methods to address overfitting and enhance performance.

2) full_experimentation_on_ResActionsImages_variants_and_transfer_learning_with_CNNs.ipynb.
   
   - Applies set of 8 experiments to seven dataset variants (M, R, L, their combinations, and a small dataset).
   - Demonstrates transfer learning on the small dataset using a model pretrained on one of the larger datasets.

3) create_src.ipynb.

   - Provides the source code modules and utility functions that the other notebooks import and use.

4) human_recognition_pseudo_images.ipynb.

   - Contains the baseline CNN model and initial setup for the ResActionsImages datasets.

5) Report of Findings.
   
   - Summarizes the outcomes and key observations from the experiments, including how different techniques and configurations impacted model performance.

Feel free to explore each notebook to understand the experimentation pipeline in detail, from data preprocessing to final model evaluations. If you have any questions or issues, please open an issue. Regarding the dataset, it is too large to upload. If you're interested, leave a comment, and we can arrange to share it via Google Drive.
