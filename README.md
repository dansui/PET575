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
 
## **Exercise 3**
The ODE function is 

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac&space;{dy}{dx}=y-sin(x),~~~~~~~~~~~y(0)=0." target="_blank"><img src="https://latex.codecogs.com/svg.latex?\frac&space;{dy}{dx}=y-sin(x),~~~~~~~~~~~y(0)=0." title="\frac {dy}{dx}=y-sin(x),~~~~~~~~~~~y(0)=0." /></a>

Use Euler method to solve it with different steps, <a href="https://www.codecogs.com/eqnedit.php?latex=\pi" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\pi" title="\pi" /></a>/32, <a href="https://www.codecogs.com/eqnedit.php?latex=\pi" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\pi" title="\pi" /></a>/16,<a href="https://www.codecogs.com/eqnedit.php?latex=\pi" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\pi" title="\pi" /></a>/8,<a href="https://www.codecogs.com/eqnedit.php?latex=\pi" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\pi" title="\pi" /></a>/4, and plot the graphs.
 
 [Code for Exercise 3](https://dansui.github.io/PET575/Chapter%203/Ex3.html)
 
 ## **Exercise 4** 
 The following figure shows the system with equations
 
 <a href="https://www.codecogs.com/eqnedit.php?latex=\begin{bmatrix}&space;2&space;&&space;0\\&space;0&1&space;\end{bmatrix}\begin{bmatrix}&space;\ddot{u}_1\\&space;\ddot{u}_2&space;\end{bmatrix}&plus;\begin{bmatrix}&space;9&space;&&space;-3\\&space;-3&3&space;\end{bmatrix}\begin{bmatrix}&space;\dot{u}_1\\&space;\dot{u}_2&space;\end{bmatrix}=\begin{bmatrix}&space;0\\&space;F_2\cos{\Omega&space;t}&space;\end{bmatrix}." target="_blank"><img src="https://latex.codecogs.com/svg.latex?\begin{bmatrix}&space;2&space;&&space;0\\&space;0&1&space;\end{bmatrix}\begin{bmatrix}&space;\ddot{u}_1\\&space;\ddot{u}_2&space;\end{bmatrix}&plus;\begin{bmatrix}&space;9&space;&&space;-3\\&space;-3&3&space;\end{bmatrix}\begin{bmatrix}&space;\dot{u}_1\\&space;\dot{u}_2&space;\end{bmatrix}=\begin{bmatrix}&space;0\\&space;F_2\cos{\Omega&space;t}&space;\end{bmatrix}." title="\begin{bmatrix} 2 & 0\\ 0&1 \end{bmatrix}\begin{bmatrix} \ddot{u}_1\\ \ddot{u}_2 \end{bmatrix}+\begin{bmatrix} 9 & -3\\ -3&3 \end{bmatrix}\begin{bmatrix} \dot{u}_1\\ \dot{u}_2 \end{bmatrix}=\begin{bmatrix} 0\\ F_2\cos{\Omega t} \end{bmatrix}." /></a>
 

 [Code for Exercise 4, 1st ODE Method](https://dansui.github.io/PET575/Chapter%203/Ex4_1.html)
 
 [Code for Exercise 4, 2nd ODE Method](https://dansui.github.io/PET575/Chapter%203/Ex4_2.html)
 
  Exercise 5
<img src="Images/ex35.png" width="1000" height="500">
 
 [Code for Exercise 5](https://dansui.github.io/PET575/Chapter%203/Ex6.html)

