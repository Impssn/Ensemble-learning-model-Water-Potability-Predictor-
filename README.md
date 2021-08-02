# ML-Ensemble-model-Water-Potability-Predictor

An Ensemble ML model (ANN) used for Water Potability test. 

Bagging is the used ensembling method here.
At first we divide the given data-set into THREE parts by using K-fold cross validation technique and then
build THREE ML models using Random forest classifier algorithm. Then we use K-means clustering algorithm to build the fourth ML Model. We feed the input
across all the FOUR ML Models in a parallel way at a time and say 'POSITIVE' if no. of positives dominate
else if no. of negatives dominate we say the result to be 'NEGATIVE'. If both are in an equal we say 
it to be 'UNPREDICTABLE'.
