# CEGE0021 - Design of Beams II

## BEAM TYPES
Two main types:
- Laterally restained
    - not free to move horizontally
    - experiences only inplane bending
- Laterally unrestained
    - free to move horizontally
    - experiences both inplane and out of plane bending

## Design considerations
Laterally unrestrained should be checked for:
- Shear
- Bending
- Web failure
- Deflection
- **Lateral Torsional Buckling**

## Lateral Torsional Buckling
Factors influencing this are:
- Beam length
- Restraint at supports
- Loading condition
- Section shape
- Shape of bending moment diagram

## Elastic Critical Moment, $M_{cr}$
$M_{cr} = \frac{\pi^2EI_z}{L^2_{cr}}(\frac{I_w}{I_z}+\frac{L^2_{cr}GI_t}{\pi^2EI_z})^{\frac12} = \frac{\pi}{L_{cr}}(EI_zGI_t)^{\frac12}(1+\frac{pi^2EI_2}{L^2_{cr}GI_t})^{\frac12}$

## General Case
$\frac{M_{Ed}}{M_{b,Rd}}\leq1.0$

where:
- $M_{Ed}$ = Maximum major axis moment in section
- $M_{b,Rd}$ = Buckling resistance moment

## General Case (Continued)
$M_{b,Rd} = \chi_{LT}W_y\frac{f_y}{\gamma_{M1}}$

Where:

$\chi_{LT} = \frac 1{\phi_{LT}+\sqrt{\phi^2_{LT}-\lambda^{-2}_{LT}}}\leq 1.0$

In which:

$\phi_{LT} = \frac 12[1+\alpha_{LT}(\overline\lambda_{LT}-0.2)+\overline\lambda^2_{LT}]$

## The Imperfection Factor $\alpha_{LT}$ - Determined from tables 6.3 and 6.4 (EC3)
### Table 6.3 - Imperfection Factor
|Buckling Curve|a|b|c|d|
|--------------|--|--|--|--|
|Imperfection Factor, $\alpha_{LT}$|0.21|0.34|0.49|0.76|

### Table 6.4 - Buckling Curves for Cross-Sections
|Cross-Section|Limits|Buckling Curve|
|-------------|------|------|
|Rolled I Section|$\frac hb\leq 2$|a|
||$\frac hb>2$|b|
|Welded I Section|$\frac hb\leq 2$|c|
||$\frac hb>2$|d|

## General Case (Continued)
$\overline\lambda = \sqrt{\frac{W_yf_y}{M_{cr}}}$

EC3 gives no guidence to calculate $M_{cr}$ therefore in NCCI SN003 the following equation is used:

$M_{cr} = C_1\frac{\pi^2EI_z}{L^2_{cr}}(\frac{I_w}{I_z}+\frac{L^2_{cr}GI_t}{\pi^2EI_z})^{\frac12}$

Values of $C_1$ determined from the table:

![image](files://C:/Users/MarleyBradbury/lecture_images/cege0021/lecture_6/C1_table.png)