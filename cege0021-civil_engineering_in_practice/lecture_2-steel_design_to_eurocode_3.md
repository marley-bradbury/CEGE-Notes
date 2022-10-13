# CEGE0021 - Introduction to steel

## General principles
The limit state design method can be summarised as follows:
- Indentifying relevant limit states
- Determining relevant laods/actions and resulting design effects
- Checing that corrsponding strengths/permitted limits are not exceeded

## Limit state design
This can be expressed mathematically as:

R<sub>d</sub> >= S<sub>d</sub>

Where:

S<sub>d</sub> is the design effect of the loads I.E. internal forces and moments and is given by:

S<sub>d</sub> = f<sub>n</sub>{y<sub>f1</sub>F<sub>k1</sub>y<sub>f2</sub>F<sub>k2</sub>y<sub>f3</sub>F<sub>k3</sub>...}

R<sub>d</sub> is the design strength of the element or structure and is given by:

R<sub>d</sub> = f<sub>n</sub>{y<sub>f1</sub>F<sub>m1</sub>y<sub>f2</sub>F<sub>m2</sub>y<sub>f3</sub>F<sub>k3</sub>...}

## Limit states relevant to the design of steel structures
### Ultimate
- Strength (including general yeilding, rupture, buckling and forming a mechanism)
- Stability against overturning and sway stability
- Fracture due to fatigue
- Brittle fracture

### Servicability
- Deflection
- Vibration
    
        structures have become lighter and lighter of years, vibration less damped
- Wind induced oscillation
        
        Tacoma bridge collapse
- Durability

## Standard rolled steel section
### Universal beam
serve as beams mainly, taller web

### Universal column
serve as columns mainly, shorter web, more square

### Channel section
Used as bracing or truss

### Equal angle
Used as bracing or truss

### Circular hollow section
Make good columns. Can fill core with concrete

### Rectangular hollow section
Make good columns. Can fill core with concrete

## Cold formed steel section
Stamped and bent from sheet metal
### Sigma beam
### Zed beam
### Sigma and zed sheeting rails
### Castellated beam
Material efficient displaced and welded expansion of an i beam

### Manufacturing process (image pending)
Really easy

## Member definitions and axes used in EC3

## Characteristic loads/actions
Characteristic permanent (g<sub>k</sub>,G<sub>k</sub>), variable and wind actions (W<sub>k</sub>) are obtained from:
- EN 1991: Actions on structures (EC1)
- Manufacturer's literature

Other documents:
- BS 6399: Part 1 - Dead and imposed loads
- BS 646: - Wieght of building materials
- CP3: Chapter V: Part 2 / BS 6399: Part 2 - Wind loads

## Scope of Eurocode 1

BS EN 1991-1-1 --- Densities, self-weight and imposed loads for buildings

BS EN 1991-1-2 --- Actions on structures exposed to fire

BS EN 1991-1-3 --- Snow loads

BS EN 1991-1-4 --- Wind loads

BS EN 1991-1-5 --- Thermal actions

BS EN 1991-1-6 --- Actions during execution

BS EN 1991-1-7 --- Accidental actions due to impact and explosions

BS EN 1991-2 ----- Traffic loads on bridges

BS EN 1991-3 ----- Actions induced by cranes and machinery

BS EN 1991-4 ----- Actions in silos and tanks

## Design loads/action - Ultimate limit states
Design loads/actions at ultimate limit state for strength and stability by calculations - The characteristic loads/actions are multiplied by a partial saftey factor taken from EN 1990 (EC0).

Several Load cases may need to be considered to obtain a 'worst case' envelop of forces and moments around the structure.

## Design value of actions (EN 1990)
The design value of action affects, E<sub>d</sub> assuming the structure is subjected to both a permanent action and a variable action can be assed using the following expression:

E<sub>d</sub> = $\sum_{j>=1}^{}$(γ<sub>G.j</sub>G<sub>k.j</sub> "+" γ<sub>Q.1</sub>G<sub>k.1</sub>)

The design value of an action effect due to a permanent action and two (or more) variable actions e.g. imposed plus wind load, is obtained  using the following expression:

E<sub>d</sub> = $\sum_{j>=1}^{}$(γ<sub>G.j</sub>G<sub>k.j</sub> "+" γ<sub>Q.1</sub>G<sub>k.1</sub>) "+" $\sum_{i>=1}^{}$(γ<sub>Q.i</sub>$\phi$<sub>0 iQ<sub>k1</sub></sub>)

## Partial load factors
Partial load factors for common load combinations (based on EN 1990)

### Common load combinations and factors
- 1.35G<sub>k</sub> "+" 1.5Q<sub>k</sub>
- 1.35G<sub>k</sub> "+" 1.5W<sub>k</sub>
- 1.00G<sub>k</sub> "+" 1.5W<sub>k</sub> (uplift)
- 1.35G<sub>k</sub> "+" 1.5Q<sub>k</sub> "+" 0.75W<sub>k</sub>
- 1.35G<sub>k</sub> "+" 1.5Q<sub>k</sub> "+" 1.5W<sub>k</sub>

## Design loads/action - Serviceability limit states

To obtain design loading at servicability limit state for calculation of deflections use the most adverse realistic combination of unfactored imposed loads/variable actions

## Characteristic and design strengths

Structural steel is manufactured in four basic grades: S235, S275, S355 and S460, in which "S" stands for structural steel and 235, 275, ETC denote the yeild strenght of the material

## Actual stress strain curves (image pending)

## Idealised stress strain curve (image pending)

## Steel grade, yeild & ultimate strengths (extracted from EN10025-2: 2019: Table 6)
| Steel Grade | Thickness of flange tf (mm) | Yeild Strength fy (Nmm-2) | Ultimate Strength fu (Nmm-2) |
|-------------|-----------------------------|---------------------------|------------------------------|
| S235        | <= 16                       | 235                       | 360                          |
|             | > 16 <= 40                  | 225                       | 360                          |
|             | >40 <= 100                  | 215                       | 360                          |
| S275        | <= 16                       | 275                       | 430                          |
|             | > 16 <= 40                  | 265                       | 410                          |
|             | >40 <= 63                   | 255                       | 410                          |
| S355        | <= 16                       | 355                       | 510                          |
|             | > 16 <= 40                  | 345                       | 470                          |
|             | >40 <= 63                   | 335                       | 470                          |


## Bending failure of a beam (image pending)

## Behaviour in bending of different classes of section (image pending)

## Limiting width to thickness ratios (based on table 5.2, EC3)
| Type of element                                                        | Class of Section |            |            |
|------------------------------------------------------------------------|------------------|------------|------------|
| (all rolled sections)                                                  | 1                | 2          | 3          |
| Outstand element of compression flange                                 | c/t <= 9ϵ         | c/t <= 10ϵ  | c/t <= 14ϵ  |
| Web with neutral axis at mid-depth                                     | c/t <= 72ϵ        | c/t <= 83ϵ  | c/t <= 124ϵ |
| Web where the whole cross-section is subject to axial compression onlu | c/t <= 33ϵ        | c/t <= 938ϵ | c/t <= 42ϵ  |
