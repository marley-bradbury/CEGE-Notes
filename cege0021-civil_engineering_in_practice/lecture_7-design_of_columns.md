# CEGE0021 - Design of Columns
## Lecture Notes
- Check if beam is class 4. As long as it is not, good
- Short Columns
    - arrive at axial load resistance by multiplying yeild strength by area of cross section for the column
- Slender Column
    - deflection y at the distace along the column x under axial load P  for column of length L is given by:
        - $B = 0$ AND $y = Asin(\frac{P}{EL})^{\frac12}x$
        - THEN $A = 0$ or $(\frac{P}{EL})^{\frac12} = n\pi$ (where n = 0,1,2 etc)
        - (A and B are integration constants)
        - If A = 0 or n = 0 the column remains straight
    - If n = 1 then:
        - $P = \frac{\pi^2EI}{L^2}$
    - Load capacity:
        - $P_E = \frac{\pi^2EI}{L^2}=\frac{\pi^2EA_gi^2}{L^2}=\frac{\pi^2EA_g}{\lambda^2}$
        - where $i = \sqrt{\frac IA}$
- Effective length of a beam
    - Effectively restrained at both ends (class 1) $L_E = 0.7L$
    - Partially restrained in direction at both ends (class 2)$L_E = 0.85L$
    - Restrained in direction at on end (3) $L_E = 0.85L$
    - Not Restrain in direction at either end (4) - $L_E = 1.0L$
- Design procedure
    1. SELECT STEEL GRADE AND SECTION
    2. DETERMINE DESIGN STRENGTH OF SECTION, fy, VIA TABLE 7 OF EN 10025-2
    3. DETERMINE EFFECTIVE LENGTH OF COLUMN, Lcr ,VIA TABLE 22 OF BS5950
    4. CALCULATE NON-DIMENSIONAL SLENDERNESS RATIO, ത, FOR APPROPRIATE AXIS
    5. SELECT APPROPRIATE BUCKLING CURVE (ao, a, b, c, d) VIA TABLE 6.2 OF EC3
    6. DETERMINE REDUCTION FACTOR, $\chi$
    7. CALCULATE DESIGN BUCKLING RESISTANCE OF COLUMN, Nb,Rd, USING
    - $N_{b,RD} = \frac{\chi Af_y}{\gamma_{M1}}$ 𝐟𝐨𝐫 𝐂𝐥𝐚𝐬𝐬 𝟏, 𝟐 𝐚𝐧𝐝 𝟑 cross − 𝐬𝐞𝐜𝐭𝐢𝐨𝐧𝐬
    8. CHECK Nb,Rd > NEd . IF NOT RETURN TO (1)