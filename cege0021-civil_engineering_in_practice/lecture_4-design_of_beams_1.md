# CEGE0021 - Design of Beams I

## Introduction
In general the design of a beam involves ensuring that the internal capacity of the beam is always greater than the action of the design loads acting on it

Members in bending are normally checked at critical points for the following:
- shear
- bending
- deflection

In certain cases it may also be necessary to check for **web failure**

## Shear
### Shear failure of web
Plastic hinges ocur in flanges

### Shear Buckling
Bucking of web in shear

## More sources of shear failure

Shear failure may arise die to:
- the shear capacity of the web beign exceeded
- buckling of the web

Shear failure of the web can be avoided by ensuring that the design shear force of the web, $V_{pl,Rd}$, where:

$V_{pl,Rd} = \frac{f_y A_v}{\sqrt{3}\gamma _{M0}}$

$A_y$ = Shear Area = $A - 2bt_f + (t_w + 2r)t_f \geq \Pi h_wt_w$


Buckling of the web need only be checked when

$\frac{d}{t} > 72\epsilon$

where $\epsilon = (\frac{235}{f_y})^{\frac{1}{2}}$

## Bending

### For point loads (W)
$M = \frac{WL}{4}$

### For UDL ($\omega$)
$M = \frac{\omega L^2}{8}$

## Moment Capacity - Class 1
### Moment of resistance of section, $M_{Rd}$

$M_{Rd} = F_c(\frac{D}{2}) = F_T(\frac{D}{2})$

### Where

$F_c = F_T = f_y(b\frac{D}{2})$

$M_{Rd} = f_y(\frac{bD}{2})(\frac{D}{2}) = f_y(\frac{bD^2}{4})$

$= f_yS_y$

$= f_yW_{pl}$

Where $W_{pl}$ = Plastic section modulus

## Moment Capacity - Class 3
### Moment of resistance of section, $M_{Rd}$

$M_{Rd} = F_c(\frac{2D}{3}) = F_T(\frac{2D}{3})$

### Where

$F_c = F_T = (\frac{f_y}{2})(b\frac{D}{2})$

$M_{Rd} = (\frac{f_y}{2})(\frac{bD}{2})(\frac{2D}{3}) = f_y(\frac{bD^2}{6})$

$= f_yZ_y$

$= f_yW_{el}$

Where $W_{el}$ = Elastic Limit

## Moment capacity - low shear load
The moment capacity of a section depends upon the co-exiting shear force. Where $V_{Ed} < 0.5V_{pl,Rd}$ (LOW SHEAR FORCE) the moment capacity for class 1 and 2 sections, $M_{c,Rd}$ is obtained from:

$M_{c,Rd} = \frac{W_{pl}f_y}{\gamma _{M0}}$

Where:

$W_{pl}$ = Plastic Section Modulus

$f_y$ = Desgin Strength of steel

$\gamma_{M0}$ = Partial Safety Factor for resistance of cross-section (= 1.00)

## Moment capacity - high shear load
Where $V_{Ed} > 0.5V_{pl,Rd}$ (HIGH SHEAR LOAD) the moment capacitu of UB and UC sections is given by:

$M_{y,V,Rd} = \frac{W_{pl.y}-\rho A^2_wf_y}{4t_w\gamma _{M0}} \leq M_{y,c,Rd}$

Where:

$\rho = [\frac{2(V_{Ed})}{V_{pl,Rd}}-1]^2$

$A_w = h_wt_w$

$M_{y,c,Rd}$ (se CI.6.2.5)

## Deflection
The elastic deflection of a beam cause by the unfactored imposed load should not exceed
- span/360 for beams carry brittle finishes
- span/200 for all other beams
- length/180 for cantilvers

These values are based on the recommendations in C1 2.23, NA to EC3