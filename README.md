# ML-Ensemble-model-Water-Potability-Predictor

An Ensemble ML model (ANN) used for Water Potability test. 

Bagging is the used ensembling method here.
At first we divide the given data-set into 3 parts by using K-fold cross validation algorithm and then
build 3 ML models. Then we use K-means clustering technique to build the ML 4th Model. We feed the input
across all the 4 ML Models in a parallel way at a time and say 'POSITIVE' if no. of positives dominate
else if no. of negatives dominate we say the result to be 'NEGATIVE'. If both are in an equal ratio we say 
it to be 'UNPREDICTABLE'.
