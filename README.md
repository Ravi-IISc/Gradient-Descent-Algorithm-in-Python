# Gradient-Descent-Algorithm-in-Python
Gradient Descent method is a conventional method for optimization of a function. Since gradient of a function is the direction of the steepest ascent, this method chooses negative of the gradient, that is direction of steepest descent. 

In this algorithm, Numerical method (forward difference) is used to calculate the gradient of the function. To compute the step-size along the steepest descent direction, backtracking line search method is used. 
To stop the iterations, tolereance value is imposed on the function value i.e. run - 
while f(x_current) - f(x_previous) > tol 
else stop 
