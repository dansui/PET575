# Chapter: Numerical Approaches

## **Exercise 1**
From the following table, the rheological data is measured using Fann 35.

|Shear stress(<a href="https://www.codecogs.com/eqnedit.php?latex=\tau" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\tau" title="\tau" /></a>)|Shear stress(<a href="https://www.codecogs.com/eqnedit.php?latex=\gamma" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\gamma" title="\gamma" /></a>) |
|-------|-----------|
|64|1022|
|42|511|
|34|340|
|26|170|
|15|10|
|10|5|

Now the Herschel-Bulkley model is considered as

<a href="https://www.codecogs.com/eqnedit.php?latex=\tau=\tau_0&plus;K\gamma^n" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\tau=\tau_0&plus;K\gamma^n" title="\tau=\tau_0+K\gamma^n" /></a>

Based on the data, please 

(1)	calculate the coeffients of Herschel-Bulkley model (<a href="https://www.codecogs.com/eqnedit.php?latex=\tau_0" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\tau_0" title="\tau_0" /></a>, K, n) using bisection method;

(2)	calculate them using fsolve function.


 [Code for Exercise 1](https://dansui.github.io/PET575/Chapter%203/Ex1.html)
 
## **Exercise 2**
The velocity of a falling parachutist is given by a dynamic model as

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac&space;{dv}{dt}=9.8-\frac&space;c&space;M&space;v,~~~~~~~~~~~v(0)=0." target="_blank"><img src="https://latex.codecogs.com/svg.latex?\frac&space;{dv}{dt}=9.8-\frac&space;c&space;M&space;v,~~~~~~~~~~~v(0)=0." title="\frac {dv}{dt}=9.8-\frac c M v,~~~~~~~~~~~v(0)=0." /></a>

It is assumed that M=2, c=0.1.  Please

(1) simulate the dynamic falling velocity within [0, 4s] by solving it analytically;
(2) simulate the dynamic falling velocity within [0, 4s] by using Euler method with different time steps, Δt =2s, 1s, 0.4s,0.2s respectively. 

 
 [Code for Exercise 2](https://dansui.github.io/PET575/Chapter%203/Ex2.html)
 
 Exercise 3
<img src="Images/ex33.png" width="1000" height="150">
 
 [Code for Exercise 3](https://dansui.github.io/PET575/Chapter%203/Ex3.html)
 
 Exercise 4
<img src="Images/ex34.png" width="1000" height="1150">

 [Code for Exercise 4, 1st ODE Method](https://dansui.github.io/PET575/Chapter%203/Ex4_1.html)
 
 [Code for Exercise 4, 2nd ODE Method](https://dansui.github.io/PET575/Chapter%203/Ex4_2.html)
 
  Exercise 5
<img src="Images/ex35.png" width="1000" height="500">
 
 [Code for Exercise 5](https://dansui.github.io/PET575/Chapter%203/Ex6.html)

