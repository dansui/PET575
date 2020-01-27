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

where h is tank level, <a href="https://www.codecogs.com/eqnedit.php?latex=k_c" target="_blank"><img src="https://latex.codecogs.com/svg.latex?k_c" title="k_c" /></a> is the valve constant; <a href="https://www.codecogs.com/eqnedit.php?latex=z_c" target="_blank"><img src="https://latex.codecogs.com/svg.latex?z_c" title="z_c" /></a> is the valve opening which is between [ 0, 1]. The valve is fully open when <a href="https://www.codecogs.com/eqnedit.php?latex=z_c" target="_blank"><img src="https://latex.codecogs.com/svg.latex?z_c" title="z_c" /></a>=1; which the valve is fully closed when <a href="https://www.codecogs.com/eqnedit.php?latex=z_c" target="_blank"><img src="https://latex.codecogs.com/svg.latex?z_c" title="z_c" /></a>=0. A iscross-sectional area of the tank. <a href="https://www.codecogs.com/eqnedit.php?latex=q_{in}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?q_{in}" title="q_{in}" /></a> is liquid flowing into the tank. g is acceleration of gravity.

Suppose A=4m, <a href="https://www.codecogs.com/eqnedit.php?latex=k_c" target="_blank"><img src="https://latex.codecogs.com/svg.latex?k_c" title="k_c" /></a>=0.12, the initial level is 2m, and the tank height is 2m. The valve is fully open. The total simulation time is 500s. The sampling time is 1s. The change of the flowin is given below

<a href="https://www.codecogs.com/eqnedit.php?latex=q_{in}(t)=\begin{Bmatrix}0.45\\&space;0.5\\&space;0.2&space;\end{matrix}~~~~~~~~\begin{matrix}0\leq&space;t\leq200s\\&space;200<&space;t\leq350s\\&space;t>350&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?q_{in}(t)=\begin{Bmatrix}0.45\\&space;0.5\\&space;0.2&space;\end{matrix}~~~~~~~~\begin{matrix}0\leq&space;t\leq200s\\&space;200<&space;t\leq350s\\&space;t>350&space;\end{matrix}" title="q_{in}(t)=\begin{Bmatrix}0.45\\ 0.5\\ 0.2 \end{matrix}~~~~~~~~\begin{matrix}0\leq t\leq200s\\ 200< t\leq350s\\ t>350 \end{matrix}" /></a>

Show the dynamic tank level with the change of the flowin.

## **Exercise 2**

A tank is provided to store the feed liquid. Assume that the plant equipment is operated continuously. The situation is sketched in the figure below, with the following notations

<a href="https://www.codecogs.com/eqnedit.php?latex=q_{in}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?q_{in}" title="q_{in}" /></a>: liquid flowing into the tank

<a href="https://www.codecogs.com/eqnedit.php?latex=q_{out}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?q_{out}" title="q_{out}" /></a>: liquid flowing out of the tank

A: cross-sectional area of the tank

𝑙: height of the tank

ℎ: liquid level height

𝜌: density of the liquid

𝑚: mass of the liquid in the tank

Assume that the tank is initially empty and the feed delivery is given as

<a href="https://www.codecogs.com/eqnedit.php?latex=q_{in}(t)=\begin{Bmatrix}30\\&space;0\\&space;30\\0\\30\\0&space;\end{matrix}~~~~~~~~\begin{matrix}~~\\0\leq&space;t\leq20h\\&space;20h<&space;t\leq40h\\&space;40h\leq&space;t\leq50h\\&space;50h<&space;t\leq70h\\70h\leq&space;t\leq80h\\&space;80h<&space;t\leq100h\\\\&space;\end{matrix}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?q_{in}(t)=\begin{Bmatrix}30\\&space;0\\&space;30\\0\\30\\0&space;\end{matrix}~~~~~~~~\begin{matrix}~~\\0\leq&space;t\leq20h\\&space;20h<&space;t\leq40h\\&space;40h\leq&space;t\leq50h\\&space;50h<&space;t\leq70h\\70h\leq&space;t\leq80h\\&space;80h<&space;t\leq100h\\\\&space;\end{matrix}" title="q_{in}(t)=\begin{Bmatrix}30\\ 0\\ 30\\0\\30\\0 \end{matrix}~~~~~~~~\begin{matrix}~~\\0\leq t\leq20h\\ 20h< t\leq40h\\ 40h\leq t\leq50h\\ 50h< t\leq70h\\70h\leq t\leq80h\\ 80h< t\leq100h\\\\ \end{matrix}" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=q_{in}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?q_{in}" title="q_{in}" /></a> is liquid flowing into the tank; <a href="https://www.codecogs.com/eqnedit.php?latex=q_{out}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?q_{out}" title="q_{out}" /></a> is liquid flowing out of the tank and <a href="https://www.codecogs.com/eqnedit.php?latex=q_{out}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?q_{out}" title="q_{out}" /></a>=12. The height of the tank is 7.2 meter.

Determine the minimum cross sectional area of the tank, A, that will prevent overflow between the time 0 to 100 hours by using Euler’s method.

# Chapter: Drilling Fluids

## **Exercise 1**

The Couette viscometer model is developed for non-Newtonian fluids, having a yield point (YP or <a href="https://www.codecogs.com/eqnedit.php?latex=\tau_0" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\tau_0" title="\tau_0" /></a>) and a plastic viscosity (PV or <a href="https://www.codecogs.com/eqnedit.php?latex=\mu_p" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\mu_p" title="\mu_p" /></a>), suitable for the Bingham plastic rheology model. The readings of a Couette-type viscometer model is given as:

<a href="https://www.codecogs.com/eqnedit.php?latex=\theta=\frac{\mu_p\omega}{A}&plus;\frac{B\tau_0}{A}~~~~~~~~~~~~~~~~~(1)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\theta=\frac{\mu_p\omega}{A}&plus;\frac{B\tau_0}{A}~~~~~~~~~~~~~~~~~(1)" title="\theta=\frac{\mu_p\omega}{A}+\frac{B\tau_0}{A}~~~~~~~~~~~~~~~~~(1)" /></a>

where θ is the dial readings of the viscometer,ω is the rotation of the cup in RPM (Note that in equation (1), <a href="https://www.codecogs.com/eqnedit.php?latex=\mu_p" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\mu_p" title="\mu_p" /></a> = Plastic Viscosity [cPoise], <a href="https://www.codecogs.com/eqnedit.php?latex=\tau_0" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\tau_0" title="\tau_0" /></a> = yield point [lbf/100 ft2]). The constants A and B are instrument constant for the Couette-type viscometer. The constant A is defined as

<a href="https://www.codecogs.com/eqnedit.php?latex=A=K_sA_g" target="_blank"><img src="https://latex.codecogs.com/svg.latex?A=K_sA_g" title="A=K_sA_g" /></a>

where:  <a href="https://www.codecogs.com/eqnedit.php?latex=K_s" target="_blank"><img src="https://latex.codecogs.com/svg.latex?K_s" title="K_s" /></a>  is the spring constant, typically denoted F1 in Fann 35 component list. The value is 363 dyne-cm per deg. The geometry constant is given by

<a href="https://www.codecogs.com/eqnedit.php?latex=A_g=\frac{6000}{8\pi^2L_b}(\frac{1}{r_b^2}-\frac{1}{r_c^2})" target="_blank"><img src="https://latex.codecogs.com/svg.latex?A_g=\frac{6000}{8\pi^2L_b}(\frac{1}{r_b^2}-\frac{1}{r_c^2})" title="A_g=\frac{6000}{8\pi^2L_b}(\frac{1}{r_b^2}-\frac{1}{r_c^2})" /></a>

where: <a href="https://www.codecogs.com/eqnedit.php?latex=L_b" target="_blank"><img src="https://latex.codecogs.com/svg.latex?L_b" title="L_b" /></a> is the length of the bob, typically 3.8 cm for a Fann 35 meter. The radius <a href="https://www.codecogs.com/eqnedit.php?latex=r_b" target="_blank"><img src="https://latex.codecogs.com/svg.latex?r_b" title="r_b" /></a> is the radius of the bob, typically 1.7245 cm for the B1 bob of a Fann 35 meter. The radius <a href="https://www.codecogs.com/eqnedit.php?latex=r_c" target="_blank"><img src="https://latex.codecogs.com/svg.latex?r_c" title="r_c" /></a>  is the radius of the rotor (cup), typically 1.8415 cm for the R1 rotor-cup of a Fann 35 meter. The yield point is given in lbf/100 ft2. B constant is given by

<a href="https://www.codecogs.com/eqnedit.php?latex=B=\frac{6000}{0.20886*2\pi}\log_e\frac{r_c}{r_b}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?B=\frac{6000}{0.20886*2\pi}\log_e\frac{r_c}{r_b}" title="B=\frac{6000}{0.20886*2\pi}\log_e\frac{r_c}{r_b}" /></a>

where: 0.20886 is the conversion factor for converting Poise to 1 lbf/100 ft2. Using this model, the various Couette-type viscometers can be simulated, and a dial reading, θ,  is calculated. Based on these calculations, the parameters for the Bingham plastic model can be found using two dial readings at two speed settings of the bob, where <a href="https://www.codecogs.com/eqnedit.php?latex=\theta_1" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\theta_1" title="\theta_1" /></a> is read at <a href="https://www.codecogs.com/eqnedit.php?latex=\omega_1" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\omega_1" title="\omega_1" /></a>, typically 600 rpm when using a Fann 35 meter and <a href="https://www.codecogs.com/eqnedit.php?latex=\theta_2" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\theta_2" title="\theta_2" /></a> is read at <a href="https://www.codecogs.com/eqnedit.php?latex=\omega_2" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\omega_2" title="\omega_2" /></a>, typically 300 rpm. The plastic viscosity parameter PV is found using

<a href="https://www.codecogs.com/eqnedit.php?latex=\mu_p=A(\frac{\theta_1-\theta_2}{\omega_1-\omega_2})" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\mu_p=A(\frac{\theta_1-\theta_2}{\omega_1-\omega_2})" title="\mu_p=A(\frac{\theta_1-\theta_2}{\omega_1-\omega_2})" /></a>

and the yield point YP is found using

<a href="https://www.codecogs.com/eqnedit.php?latex=\tau_0=\frac&space;AB\begin{bmatrix}&space;\theta_1&space;-(\frac{\omega_1}{\omega_1-\omega_2})(\theta_1-\theta_2)&space;\end{bmatrix}" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\tau_0=\frac&space;AB\begin{bmatrix}&space;\theta_1&space;-(\frac{\omega_1}{\omega_1-\omega_2})(\theta_1-\theta_2)&space;\end{bmatrix}" title="\tau_0=\frac AB\begin{bmatrix} \theta_1 -(\frac{\omega_1}{\omega_1-\omega_2})(\theta_1-\theta_2) \end{bmatrix}" /></a>

The following data are obtained from Fann 35.

|Speed(rpm)|3|6|100|200|300|600|
|--------------|--------|--------|--------|--------|--------|--------|
|Readings|7|7.3|13|16|19.5|30|

The Herschel-Buckley parameters are using a yield point τ0 =38.8183 Poise/s, a consistency index of K=0.4601 Poise/s, and a flow behavior index of n=0.8087. Generate the following plots  where the following data are shown:

(1)	The Fann readings VS. RPM

(2)Simulation of the Fann readings using the Herschel-Buckley model with the given coefficients VS. RPM

## **Exercise 2**

The data in the below table is obtained from Fann VG. Calculate the coefficients for three rheological models (Bingham, Power-law and Herchel-Bulkley)


|Speed(rpm)|3|6|100|200|300|600|
|Readings|9.4|14.2|24.5|32.1|19.5|30|
