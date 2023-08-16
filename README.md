# Optimised hidden layer neurons
Determining the optimal number of neurons in the hidden layer for an Artificial Neural Network (ANN) is a crucial step in model development. Various approaches exist, but no recognised rule for determining each layer's exact number of neurons exists. 

This study employed the root mean square error (RMSE) as a performance metric for the ANN model. A MATLAB code was implemented to evaluate the model's performance for a range of neurons in the hidden layer from 1 to 60. The minimal RMSE error identified the optimized number of hidden layer neurons.

the training error decreased as the number of neurons increased. However, the validation and testing errors increased, indicating the model's overfitting. On the other hand, with fewer neurons, the training error increased, leading to underfitting.

Based on the RMSE plot, we selected the number of neurons that achieved a balance between model complexity and generalization performance. These optimal neurons were used for the final ANN model.

Cite:
[1]	Moorthy V, Marappan K. Free vibration analysis and prediction modeling of delaminated tapered FRP composite plates. Proc Inst Mech Eng Part C J Mech Eng Sci n.d.;0:09544062221139777. https://doi.org/10.1177/09544062221139777.
[2]	Moorthy V, Marappan K. Identification of delamination severity in a tapered FRP composite plate. Compos Struct 2022;299:116054. https://doi.org/10.1016/j.compstruct.2022.116054.

