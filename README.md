# Simulated-Annealing
This code is developed by Sreemannarayana Ikkurthi,
as a part of course notes for the course 15AES477: Multidisciplinary Design Optimization (MDO).

In support of Dr. Rajesh Senthil Kumar T.,
Assistant Professor, 

Department of Aerospace Engneering, Amrita Vishwa Vidyapeetham.
## About Simulated Annealing
Simulated Annealing is an optimization method, mimicing annealing process.

A detailed explanation about the method can be found in the text book:
###### *Deb Kalyanmoy, Optimization for Engineering Design, Algorithms and Examples. (2012)*
## About Code
This code can be used to optimize an objective function of n variables and produce a contour plots of adjacent variables of all generations.

### min_x, min_f, good_x = Sim_Ann(ini_x, fac, T, t_fac, n_fac):
        Inputs:
              ini_x = Initial search point
              fac = Search factor
              T = Temperature
              t_fac = Temperature factor
              n_fac = n factor
        Outputs:
              min_x = Minima point
              min_f = Minimum function value
              good_x = List of good points
        Usage: 
              Get minima point and its function value.
              
Give apprpriate objective function and input variables in INPUT ARENA to get the minima and plot contours.
