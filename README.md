# Chapter: Numerical Approaches

## **Exercise 1**
From the following table, the rheological data is measured using Fann 35.

|Shear stress(![](https://latex.codecogs.com/svg.latex?\tau))|Shear stress(<a href="https://www.codecogs.com/eqnedit.php?latex=\gamma" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\gamma" title="\gamma" /></a>) |
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
 
<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{bmatrix}&space;2&space;&&space;0\\&space;0&1&space;\end{bmatrix}\begin{bmatrix}&space;\ddot{u}_1\\&space;\ddot{u}_2&space;\end{bmatrix}&plus;\begin{bmatrix}&space;9&space;&&space;-3\\&space;-3&3&space;\end{bmatrix}\begin{bmatrix}&space;\dot{u}_1\\&space;\dot{u}_2&space;\end{bmatrix}=\begin{bmatrix}&space;0\\&space;2\cos{\Omega&space;t}&space;\end{bmatrix}." target="_blank"><img src="https://latex.codecogs.com/svg.latex?\begin{bmatrix}&space;2&space;&&space;0\\&space;0&1&space;\end{bmatrix}\begin{bmatrix}&space;\ddot{u}_1\\&space;\ddot{u}_2&space;\end{bmatrix}&plus;\begin{bmatrix}&space;9&space;&&space;-3\\&space;-3&3&space;\end{bmatrix}\begin{bmatrix}&space;\dot{u}_1\\&space;\dot{u}_2&space;\end{bmatrix}=\begin{bmatrix}&space;0\\&space;2\cos{\Omega&space;t}&space;\end{bmatrix}." title="\begin{bmatrix} 2 & 0\\ 0&1 \end{bmatrix}\begin{bmatrix} \ddot{u}_1\\ \ddot{u}_2 \end{bmatrix}+\begin{bmatrix} 9 & -3\\ -3&3 \end{bmatrix}\begin{bmatrix} \dot{u}_1\\ \dot{u}_2 \end{bmatrix}=\begin{bmatrix} 0\\ 2\cos{\Omega t} \end{bmatrix}." /></a>
 
The initial conditions are 

<a href="https://www.codecogs.com/eqnedit.php?latex=U_0=\begin{bmatrix}&space;1\\&space;1&space;\end{bmatrix},~~\dot&space;U_0=\begin{bmatrix}&space;0\\&space;0&space;\end{bmatrix},&space;~~\ddot&space;U_0=\begin{bmatrix}&space;0\\&space;0&space;\end{bmatrix}." target="_blank"><img src="https://latex.codecogs.com/svg.latex?U_0=\begin{bmatrix}&space;1\\&space;1&space;\end{bmatrix},~~\dot&space;U_0=\begin{bmatrix}&space;0\\&space;0&space;\end{bmatrix},&space;~~\ddot&space;U_0=\begin{bmatrix}&space;0\\&space;0&space;\end{bmatrix}." title="U_0=\begin{bmatrix} 1\\ 1 \end{bmatrix},~~\dot U_0=\begin{bmatrix} 0\\ 0 \end{bmatrix}, ~~\ddot U_0=\begin{bmatrix} 0\\ 0 \end{bmatrix}." /></a>

(1) Simulate  the displacement responses over time range 0 ≤ t ≤ 12, for the following four values of the excitation frequency 

a) <a href="https://www.codecogs.com/eqnedit.php?latex=\Omega=0" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\Omega=0" title="\Omega=0" /></a>

b) <a href="https://www.codecogs.com/eqnedit.php?latex=\Omega=1" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\Omega=1" title="\Omega=1" /></a>

c) <a href="https://www.codecogs.com/eqnedit.php?latex=\Omega=3/\sqrt&space;2" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\Omega=3/\sqrt&space;2" title="\Omega=3/\sqrt 2" /></a>

d) <a href="https://www.codecogs.com/eqnedit.php?latex=\Omega=3" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\Omega=3" title="\Omega=3" /></a>

(2) Simulate  the displacement responses over time range 0 ≤ t ≤ 12, for the new initial displacement, <a href="https://www.codecogs.com/eqnedit.php?latex=U_0=\begin{bmatrix}&space;1&space;\\&space;-1&space;\end{bmatrix}." target="_blank"><img src="https://latex.codecogs.com/svg.latex?U_0=\begin{bmatrix}&space;1&space;\\&space;-1&space;\end{bmatrix}." title="U_0=\begin{bmatrix} 1 \\ -1 \end{bmatrix}." /></a>


 [Code for Exercise 4, 1st ODE Method](https://dansui.github.io/PET575/Chapter%203/Ex4_1.html)
 
 [Code for Exercise 4, 2nd ODE Method](https://dansui.github.io/PET575/Chapter%203/Ex4_2.html)
 
## **Exercise 5** 
The table gives the experimental data of shear rate VS shear stress with the use of viscometer. 

|Shear stress(<a href="https://www.codecogs.com/eqnedit.php?latex=\tau" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\tau" title="\tau" /></a>)|Shear stress(<a href="https://www.codecogs.com/eqnedit.php?latex=\gamma" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\gamma" title="\gamma" /></a>) |
|-------|-----------|
|31|1022|
|27|511|
|24|340|
|14|5|

Calculate the coefficients (<a href="https://www.codecogs.com/eqnedit.php?latex=\tau_0,\,\mu_p" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\tau_0,\,\mu_p" title="\tau_0,\,\mu_p" /></a>) of Bingham Plastic Model

<a href="https://www.codecogs.com/eqnedit.php?latex=\tau=\tau_0&plus;&space;\mu_p\gamma" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\tau=\tau_0&plus;&space;\mu_p\gamma" title="\tau=\tau_0+ \mu_p\gamma" /></a>
 
and coefficients (K, n) of Power Law Model

<a href="https://www.codecogs.com/eqnedit.php?latex=\tau=K\gamma^n" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\tau=K\gamma^n" title="\tau=K\gamma^n" /></a>

by the regression methods.  And use <a href="https://www.codecogs.com/eqnedit.php?latex=R^2" target="_blank"><img src="https://latex.codecogs.com/svg.latex?R^2" title="R^2" /></a> (coefficient of determination) to evaluate the two models’ performance. 

 [Code for Exercise 5](https://dansui.github.io/PET575/Chapter%203/Ex6.html)

# Chapter: Modeling
 
## **Exercise 1**
The tank level model is

<a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;h=\frac1A(q_{in}-z_ck_c\sqrt{gh})" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;h=\frac1A(q_{in}-z_ck_c\sqrt{gh})" title="\dot h=\frac1A(q_{in}-z_ck_c\sqrt{gh})" /></a>

where h is tank level, <a href="https://www.codecogs.com/eqnedit.php?latex=k_c" target="_blank"><img src="https://latex.codecogs.com/svg.latex?k_c" title="k_c" /></a> is the valve constant; <a href="https://www.codecogs.com/eqnedit.php?latex=z_c" target="_blank"><img src="https://latex.codecogs.com/svg.latex?z_c" title="z_c" /></a> is the valve opening which is between [ 0, 1]. The valve is fully open when <a href="https://www.codecogs.com/eqnedit.php?latex=z_c" target="_blank"><img src="https://latex.codecogs.com/svg.latex?z_c" title="z_c" /></a>=1; which the valve is fully closed when <a href="https://www.codecogs.com/eqnedit.php?latex=z_c" target="_blank"><img src="https://latex.codecogs.com/svg.latex?z_c" title="z_c" /></a>=0. A iscross-sectional area of the tank. 𝑞𝑞𝑖𝑖𝑖𝑖: liquid flowing into the tank. g is acceleration of gravity.
