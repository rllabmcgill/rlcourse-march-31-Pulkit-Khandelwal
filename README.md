An Emphatic Approach to the Problem of Off-policy Temporal-Difference Learning---- Richard S. Sutton, A. Rupam Mahmood and Martha White

In this IPython Notebook, I will walk through the various Function Approximation methods for estimating an optimal solution for the value functions V(s) given in the above mentioned paper. We get introduced to a different type of trace: the followon trace, interest function and also a new variant of Squared Value error with interest function!
The algorithms implemented in this notebook are:

Emphatic TD(lambda)
Emphatic TD(0)
Off-policy Semi-gradient TD(0) for estimating V_pi

The above alogorithms are compared with the following algorithms from the previous assignment 4:

Gradient Monte Carlo Algorithm for Approximating V
Semi-gradient TD(0) for estimating V_pi
TD(lambda)
True-online TD(lambda)
TD(0) for prediction. This result will act as the V_pi(s) to calculate RMSVE
