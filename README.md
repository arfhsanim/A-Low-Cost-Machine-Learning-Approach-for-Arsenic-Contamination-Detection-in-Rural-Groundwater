A Low-Cost Machine Learning Approach for Arsenic Contamination 
Detection in Rural Groundwater

Arsenic contamination of groundwater in rural Bangladesh is a serious public health issue, with shallow wells relying 
on millions of people exceeding the national safety standard (50 µg/L). Existing laboratory analyses and commercial 
field kits are unsuitable for routine community-level screening due to cost and time constraints. This study investigates 
whether unsafe wells can be identified without a laboratory using a low-cost approach that combines IoT sensors (pH, 
electrical conductivity, water temperature) with simple field measurements (iron, manganese) and well depth. Using the 
BGS/DFID/DPHE Special Study dataset (n=271), five classifiers logistic regression, random forest, multilayer perceptron, 
—
—
XGBoost, and gradient boosting were trained and evaluated in conjunction with the SMOTE technique. Random forest 
achieved the best performance with an AUC of 0.923, F1 of 0.838, and unsafe class recall of 0.94, maintaining a 
discriminative ability of 93.8% compared to all laboratory analyses. SHAP analysis confirmed that iron concentration, 
pH, and well depth are key predictor variables.
