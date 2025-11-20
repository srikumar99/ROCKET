# ROCKET
Random Convolutional Kernel Transform
Algorithm 1 One nearest neighbour with dynamic time warping algorithm
 
1: for every time series in the test set do
2:	Let a represent the time series from the training set of the current iteration.
3:	for every time series in the training set do
4:	Let b represent the time series from the training set of the current iteration.
5:	for every feature i in time series do
6:	Find the warping path Pˆi with DTW distance DPˆ,i of the current feature i between
a and b.
7:	Sum the DTW distance DPˆ,i of every feature to obtain the total DTW distance DPˆ of the two time current series.
8:	Choose the time series from the training set which resulted in the smallest DTW distance
DPˆ and check the label of that instance. Classify a as that label.

lkernel−1
X ∗ ω =	Xi+(j×d) × ωj.	(19)
j=0
fθ(x) = θ0 + θ1x1 + θ2x2 + ... + θpxp = θ⊤x.
L(y, f (x)) = ln(1 + e−yθ⊤x).
R(θ) = ||θ||1.
