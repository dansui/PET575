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
 The  system is with equations
 
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

 [Code for Exercise 1](https://dansui.github.io/PET575/Chapter%204/Ex1.html)

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

[Code for Exercise 2](https://dansui.github.io/PET575/Chapter%204/Ex4.html)

## **Temperature Modeling**

The configuration data used for the temperature modeling is given below

|Definiation|Value|Description | Unit|
|-------|-----------|-----------|--------------------|
|h|Well depth| 15000|Feet|
|d_pi| Drill string OD|6.625|Inch|
|d_p| Drill string ID|6.375|Inch|
|d_bit| Drill bit size|8.375|Inch|
|d_ci|Casing ID|10.25|Inch|
|q|Flowrate|100|bbl/hour|
|T_in|Inlet fluid temperature|30|F|
|mu|Fluid viscosity|110|lb/(ft-hr)|
|k_f|Fluid thermal conductivity|1|Btu/(ft-F-hr)|
|k_p|Drill string thermal conductivity|1|Btu/(ft-F-hr)|
|k|Formation thermal conductivity|1.3|Btu/(ft-F-hr)|
|c_f|Fluid specific heat capacity|0.4| Btu/(lb-F)|
|c|Formation specific heat capacity|0.2| Btu/(lb-F)|
|rho_f|Fluid denisty|10|lb/gal|
|rho|Formation density|165|lb/gal|
|T_e|Surface earth temperature|19.5|F|
|g_e|Geothermal gradient|0.0127|F/ft|
|t|Circulation time|44|hours

Please simulate the temperature profiles of fluids in drillstring and in annulus respectively.

[Code for Temperature Modeling](https://dansui.github.io/PET575/Chapter%204/Example_temperature.html)


 
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

[Code for Exercise 1](https://dansui.github.io/PET575/Chapter%205/Ex1.html)

## **Exercise 2**

The data in the below table is obtained from Fann VG. Calculate the coefficients for three rheological models (Bingham, Power-law and Herchel-Bulkley)


|Speed(rpm)|3|6|100|200|300|600|
|--------------|--------|--------|--------|--------|--------|--------|
|Readings|9.4|14.2|24.5|32.1|39.6|60.4|
|Speed(s^-1)|5|10|170|340|511|1022|
|Shear stress(lbf/100 ft2)|10|15|26|34|42|64|

[Code for Exercise 2 (Field Method)](https://dansui.github.io/PET575/Chapter%205/Ex2.html)

[Code for Exercise 2 (Regression Method)](https://dansui.github.io/PET575/Chapter%205/Ex2_1.html)

## **Exercise 3**

Please calculate the best-fit coefficients of the following density model

<a href="https://www.codecogs.com/eqnedit.php?latex=\rho=\rho_0&plus;\frac{\rho_0}\beta(P-P_0)-\rho_0\alpha(T-T_0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\rho=\rho_0&plus;\frac{\rho_0}\beta(P-P_0)-\rho_0\alpha(T-T_0)" title="\rho=\rho_0+\frac{\rho_0}\beta(P-P_0)-\rho_0\alpha(T-T_0)" /></a>

by regression method. Reference points for the density (<a href="https://www.codecogs.com/eqnedit.php?latex=\rho_0" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\rho_0" title="\rho_0" /></a>) and temperature (<a href="https://www.codecogs.com/eqnedit.php?latex=T_0" target="_blank"><img src="https://latex.codecogs.com/svg.latex?T_0" title="T_0" /></a>) are defined as:

<a href="https://www.codecogs.com/eqnedit.php?latex=\rho_0=800kg/m^3,~~~T_0=20^oC" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\rho_0=800kg/m^3,~~~T_0=20^oC" title="\rho_0=800kg/m^3,~~~T_0=20^oC" /></a>

The dataset used, varies in pressures from 1 bar to 900 bar and the temperatures used is from 4°C to 200°C. For the varying pressures and temperatures, respectable densities are given in the dataset.

temp=[4,20,50,75,100,125,150,175,200];

pres=[1,14.790,42.230,69.940,90.632,118.211,145.790,173.369,200.948,228.527,256.106,311.264,366.422,435.370,490.528,900.000];

|P(bar)/D(sg)/T(C)|4|20|50|75|100|125|150|175|200|
|--------------|--------|--------|--------|--------|--------|--------|--------|--------|--------|
|1|0.806125| 0.800000| 0.780827 |0.763662| 0.746678| 0.728862 |0.710629| 0.691998 |0.672913|
|14.790|0.806817| 0.800736| 0.781693| 0.764649| 0.747784| 0.730090| 0.711983| 0.693480| 0.674531|
|42.230|0.808179 |0.802188| 0.783405| 0.766599| 0.749967| 0.732518 |0.714662| 0.696410| 0.677723|
|69.940|0.809532 |0.803627 |0.785100 |0.768529| 0.752127| 0.734918| 0.717301| 0.699301 |0.680865|
|90.632|0.810547| 0.804707| 0.786366| 0.769966 |0.753731| 0.736691 |0.719258| 0.701437| 0.683187|
|118.211|0.811883| 0.806129| 0.788038 |0.771860| 0.755843 |0.739038 |0.721835| 0.704256 |0.686248|
|145.790|0.813225 |0.807552 |0.789697| 0.773734| 0.757926| 0.741345| 0.724378| 0.707023| 0.689258|
|173.369|0.814552| 0.808956| 0.791332| 0.775586 |0.759992| 0.743628 |0.726880 |0.709757 |0.692223|
|200.948|0.815870 |0.810355 |0.792962 |0.777418 |0.762022| 0.745876 |0.729348 |0.712445 |0.695138|
|228.527|0.817183| 0.811741 |0.794567| 0.779229 |0.764034| 0.748095| 0.731775| 0.715087| 0.698009|
|256.106|0.818492| 0.813122 |0.796161| 0.781018| 0.766017 |0.750278 |0.734167 |0.717695| 0.700828|
|311.264|0.821073| 0.815847 |0.799305| 0.784537| 0.769903 |0.754556 |0.738845 |0.722772| 0.706323|
|366.422|0.823640| 0.818543| 0.802382| 0.787971 |0.773688| 0.758708 |0.743370 |0.727692| 0.711635|
|435.370|0.826798| 0.821853| 0.806142| 0.792151| 0.778279| 0.763727 |0.748833| 0.733596 |0.718013|
|490.528|0.829287| 0.824457| 0.809084| 0.795400 |0.781831| 0.767602 |0.753036 |0.738137 |0.722899|
|900.000|0.847760| 0.843786 |0.830923| 0.819527| 0.808205| 0.796365 |0.784232 |0.771855 |0.759173|



## **Exercise 4**

Suppose that D=0.15m, v=3.6m/s, ρ=1258 kg/m^3 ,μ=0.96Pa.s. Determine the flow regime.

[Code for Exercise 4](https://dansui.github.io/PET575/Chapter%205/Ex4.html)

## **Exercise 5**

For Newtonian fluids, make graphs of Reynolds number vs. flow rate (from 1 l/min to 500 l/min, the increment is 10 l/min), friction factor vs. flow rates, friction factor vs. Reynolds number in a 3.5m long pipe with inner diameter of 24mm. The mud density is 1000kg/l and viscosity is 1cP.

[Code for Exercise 5](https://dansui.github.io/PET575/Chapter%205/Ex5.html)

## **Exercise 6**

The data in the following table is obtained from Fann VG. 

|Speed(rpm)|3|6|100|200|300|600|
|--------------|--------|--------|--------|--------|--------|--------|
|Readings|9.5|10.5|17|19.9|23|28.9|

Suppose the mud density is 1000kg/l. The pipe length is 3.5m and inner diameter is 24mm. 

(1)	Calculate the coefficients for three rheological models (Bingham, Power-law and Herchel-Bulkley).

(2)	Calculate the generalized Reynolds number for these three fluids vs. flow rate (from 1 l/min to 300 l/min).

(3)	Calculate the apparent viscosities for these three fluids vs. flow rate (from 1 l/min to 300 l/min).

(4)	Calculate the friction factors for these three fluids vs. flow rate (from 1 l/min to 300 l/min).

(5)	Calculate the pressure drops for these three fluids vs. flow rate (from 1 l/min to 300  l/min).

[Code for Exercise 6](https://dansui.github.io/PET575/Chapter%205/Ex6.html)

## **Exercise 7**

The structure of the drilling system is shown below. The differential pressure sensors are installed on the pipes in order to automatically evaluate the drilling fluid density and viscosity.  DP1 in the figure is the horizontal differential pressure between pressure sensors 1 and 2; DP2 in the figure is the vertical differential pressure between pressure sensors 3 and 4.  The values of the parameters involved in the calculation is given in the table.

|Description|Notation|Values|Unit|
|--------------------|--------|--------|--------|
|Horizontal differential pressure between sensor 1, 2 |DP1|1000|Pa|
|Vertical differential pressure between sensor 3, 4 |DP2|197000|Pa|
|Vertical depth between sensor 3,4 |h|20|m|
|Acceleration of gravity|g|9.8|m/s^2|
|Pipe inner diameter |D|0.2|m|
|Length between sensor 1,2 |l|30|m|
|Length between sensor 3,4|l|30|m|
|Pipe roughness |<a href="https://www.codecogs.com/eqnedit.php?latex=\varepsilon" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\varepsilon" title="\varepsilon" /></a>|0|-|
|Flow rate |q|0.0283|m ^3/s|

Based on the values given in the table, calculate the density (ρ) and apparent viscosity (μ).

[Code for Exercise 7](https://dansui.github.io/PET575/Chapter%205/Ex7.html)

# Chapter: Drillstring Dynamics

## **Exercise 1**

For the undamped system 

<a href="https://www.codecogs.com/eqnedit.php?latex=m\ddot&space;x(t)&plus;kx(t)=0" target="_blank"><img src="https://latex.codecogs.com/svg.latex?m\ddot&space;x(t)&plus;kx(t)=0" title="m\ddot x(t)+kx(t)=0" /></a>

Solve the analytical solutions and plot the dynamic responses of x(t), where

(1) m=1,k=1 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=0;


(2) m=1,k=2 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=0;


(3) m=2,k=1 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=0;


(4) m=1,k=1 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=1;


(5) m=1,k=1 and x(0)=-1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=0.

## **Exercise 2**

For the damped system 

<a href="https://www.codecogs.com/eqnedit.php?latex=m\ddot&space;x(t)&plus;c\dot&space;x(t)&plus;kx(t)=0" target="_blank"><img src="https://latex.codecogs.com/svg.latex?m\ddot&space;x(t)&plus;c\dot&space;x(t)&plus;kx(t)=0" title="m\ddot x(t)+c\dot x(t)+kx(t)=0" /></a>

Solve the analytical solutions and plot the dynamic responses of x(t), where

(1) m=1,k=1,c=2 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=-1;

(2) m=1,k=1,c=4 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=-1;

(3) m=1,k=1,c=1 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=-1;

(4) m=1,k=1,c=0.1 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=-1;

(5) m=4,k=1,c=0.1 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=-1;

(6) m=1,k=4,c=0.1 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=-1;

(6) m=1,k=4,c=0.1 and x(0)=1, <a href="https://www.codecogs.com/eqnedit.php?latex=\dot&space;x(0)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\dot&space;x(0)" title="\dot x(0)" /></a>=0.


## **Exercise 3**

Compute the analytical solution of the following system

<a href="https://www.codecogs.com/eqnedit.php?latex=\ddot&space;x(t)&plus;c\dot&space;x(t)&plus;4x(t)=1/\sqrt2\cos(at)" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\ddot&space;x(t)&plus;c\dot&space;x(t)&plus;4x(t)=1/\sqrt2\cos(at)" title="\ddot x(t)+c\dot x(t)+4x(t)=1/\sqrt2\cos(at)" /></a>

Show the dynamic response of the system when

(1) c=0.4, a=3 and  <a href="https://www.codecogs.com/eqnedit.php?latex=x(0)=-3/\sqrt2,\dot&space;x(0)=0" target="_blank"><img src="https://latex.codecogs.com/svg.latex?x(0)=-3/\sqrt2,\dot&space;x(0)=0" title="x(0)=-3/\sqrt2,\dot x(0)=0" /></a>;

(2) c=0.4, a=2 and  <a href="https://www.codecogs.com/eqnedit.php?latex=x(0)=-3/\sqrt2,\dot&space;x(0)=0" target="_blank"><img src="https://latex.codecogs.com/svg.latex?x(0)=-3/\sqrt2,\dot&space;x(0)=0" title="x(0)=-3/\sqrt2,\dot x(0)=0" /></a>;

(3) c=0.4, a=2 and  <a href="https://www.codecogs.com/eqnedit.php?latex=x(0)=1,\dot&space;x(0)=-1" target="_blank"><img src="https://latex.codecogs.com/svg.latex?x(0)=1,\dot&space;x(0)=-1" title="x(0)=1,\dot x(0)=-1" /></a>;

(3) c=0.0001, a=2 and  <a href="https://www.codecogs.com/eqnedit.php?latex=x(0)=1,\dot&space;x(0)=-1" target="_blank"><img src="https://latex.codecogs.com/svg.latex?x(0)=1,\dot&space;x(0)=-1" title="x(0)=1,\dot x(0)=-1" /></a>.


## **Exercise 4**

 The  system is with equations
 
<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{bmatrix}&space;2&space;&&space;0\\&space;0&1&space;\end{bmatrix}\begin{bmatrix}&space;\ddot{u}_1\\&space;\ddot{u}_2&space;\end{bmatrix}&plus;\begin{bmatrix}&space;9&space;&&space;-3\\&space;-3&3&space;\end{bmatrix}\begin{bmatrix}&space;\dot{u}_1\\&space;\dot{u}_2&space;\end{bmatrix}=\begin{bmatrix}&space;0\\&space;2\cos{\Omega&space;t}&space;\end{bmatrix}." target="_blank"><img src="https://latex.codecogs.com/svg.latex?\begin{bmatrix}&space;2&space;&&space;0\\&space;0&1&space;\end{bmatrix}\begin{bmatrix}&space;\ddot{u}_1\\&space;\ddot{u}_2&space;\end{bmatrix}&plus;\begin{bmatrix}&space;9&space;&&space;-3\\&space;-3&3&space;\end{bmatrix}\begin{bmatrix}&space;\dot{u}_1\\&space;\dot{u}_2&space;\end{bmatrix}=\begin{bmatrix}&space;0\\&space;2\cos{\Omega&space;t}&space;\end{bmatrix}." title="\begin{bmatrix} 2 & 0\\ 0&1 \end{bmatrix}\begin{bmatrix} \ddot{u}_1\\ \ddot{u}_2 \end{bmatrix}+\begin{bmatrix} 9 & -3\\ -3&3 \end{bmatrix}\begin{bmatrix} \dot{u}_1\\ \dot{u}_2 \end{bmatrix}=\begin{bmatrix} 0\\ 2\cos{\Omega t} \end{bmatrix}." /></a>
 
The initial conditions are 

<a href="https://www.codecogs.com/eqnedit.php?latex=U_0=\begin{bmatrix}&space;1\\&space;1&space;\end{bmatrix},~~\dot&space;U_0=\begin{bmatrix}&space;0\\&space;0&space;\end{bmatrix},&space;~~\ddot&space;U_0=\begin{bmatrix}&space;0\\&space;0&space;\end{bmatrix}." target="_blank"><img src="https://latex.codecogs.com/svg.latex?U_0=\begin{bmatrix}&space;1\\&space;1&space;\end{bmatrix},~~\dot&space;U_0=\begin{bmatrix}&space;0\\&space;0&space;\end{bmatrix},&space;~~\ddot&space;U_0=\begin{bmatrix}&space;0\\&space;0&space;\end{bmatrix}." title="U_0=\begin{bmatrix} 1\\ 1 \end{bmatrix},~~\dot U_0=\begin{bmatrix} 0\\ 0 \end{bmatrix}, ~~\ddot U_0=\begin{bmatrix} 0\\ 0 \end{bmatrix}." /></a>

Show the general solution of the system and the dynamics with <a href="https://www.codecogs.com/eqnedit.php?latex=\Omega=1/\sqrt&space;2" target="_blank"><img src="https://latex.codecogs.com/svg.latex?\Omega=1/\sqrt&space;2" title="\Omega=1/\sqrt 2" /></a>.
