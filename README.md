# BP-Prediction-From-PPG
Feature Selection to predicting BP from PPG using different models. 
---

## Requirement
> Python3  
> Pandas  
> PyTorch  
> Numpy  
> matplotlib  
> Scikit Learn  
> SciPy  
> IPython  
> pydot  

---

Run ``` python3 nn_bp_regression.py ``` to predict the SBP and DBP values using NN  
Run ``` python3 random_forest.py ``` to predict the SBP and DBP values using Random Forest  
Run ``` python3 nn_bp_classify.py ``` to classify the BP conditions using NN  
Run ``` python3 random_forest_classifiers.py ``` to classify the BP conditions using Random Forest  

---

The scripts mentioned above will generate a bunch of csv and png files for results and visualization.  
Once the result files are generated, run ```python3 get_selected_feature_names.py``` to print out the optimal features for different algorithm.  

