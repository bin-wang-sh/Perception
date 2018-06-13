Perceptron Algorithm Exercise for Udacity Data Science
============================================================
Recall that the perceptron step works as follows. For a point with coordinates  (p,q), label y, and prediction given by the equation：

•	If the point is correctly classified, do nothing.
•	If the point is classified positive, but it has a negative label, subtract αp,αq, and α from w_1, w_2,w1,w2, and b respectively.
•	If the point is classified negative, but it has a positive label, add  αp,αq, and  α to  w1,w2, and b respectively.
