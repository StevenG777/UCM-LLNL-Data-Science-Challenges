# UCM-LLNL-Data-Science-Challenges

## Descriptions
- The project is part of the study of computational chemistry and the drug discovery process. Identifying an effective chemical compound to inhibit SARS-CoV-2 is a time-consuming and costly process through the physical laboratory. However, the new approach to machine learning propels the development of identifying chemical compound candidates for drug discovery. - The Data Science Challenge program offered two tasks for students to try out:
  - Task 1: Screen compounds using SMILES and molecular descriptor
  - Task 2: Screen compounds using 3D atomic representation
  - Bonus Task: Model fusion and performance analysis

## Project Details
- We first loaded the database to perform data preprocessing such as data cleansing and normalization.
- We then employ machine learning models such as linear regression, support vector machine, random forest, and multilayer perceptron.
- Performed parameter tuning to improve the accuracy of multilayer perceptron

## Results
- Multilayer Perceptron (MLP) yielded the highest accuracy of 82.03% among all the models, followed by XGBoost and Random Forest
- Data normalization demonstrated to reduce the fluctuation of loss over epochs during model training
- During the hyperparameter tuning for MLP, increasing the number of nodes per layer or the number of layers with constant numbers of nodes didn't significantly improve the accuracy, increasing the node's quantity increased training time whereas increasing the layer's quantity decreased training time.
- During the hyperparameter tuning for MLP, increasing to a certain amount of epoch for training did improve the accuracy (In the context of the project, accuracy stop increased when the epoch was over 20)
- During the hyperparameter tuning for MLP, smaller batch size of data led to higher accuracy and less fluctuation but sacrificed training time, and vice versa.

## File Details
- [Task 1.ipynb](https://github.com/StevenG777/UCM-LLNL-Data-Science-Challenges/blob/main/Task%201.ipynb): Code Script
- [/data/*](https://github.com/StevenG777/UCM-LLNL-Data-Science-Challenges/tree/main/data): Dataset
- [LLNL DSC Team 2.pdf](https://github.com/StevenG777/UCM-LLNL-Data-Science-Challenges/blob/main/LLNL%20DSC%20Team%202.pdf): Summary of learning experience and experimental outcomes

## Future Work
- Continue with Task 2
- Tackle Task 1 with different machine learning models
