# Numerical_Approximation
C++ code that I (Luke) wrote in my second year of college. I wrote it to assist with my Calculus 2 class because numerical approximation by hand is incredibly tedious.
I modified the original code to be more object-oriented so the numerical formulas are inside a class hierarchy.
The different numerical approximation formulas that are coded are Riemann's sums formula (I believe Middle Riemann sums instead of left or right Riemann sums), Trapezoidal formula, Parabolic formula (aka Simpson's Rule).
The user must input the 2 limits of integration since numerical approximation is a definite integration technique. 
The user must also input the step size for the formula, larger numbers for the step size (sub-interval size) means a more accurate approximation for the integration.
The equation which you would like to do the numerical approximation on must be changed inside the source code. 
A later update for the program may include a way to parse the equation input on the console window by the user instead of requiring the equation inside the source code to be modified to match each equation.
