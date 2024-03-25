# UCM-LLNL-Data-Science-Challenges

## Descriptions


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
