# CEGE0026 Equations of Motion

## Table of Contents
- Different types of flows
- Euler's equation of motion
- Navier-Stokes Equation
- Examples

## Learning outcomes
- Basic
    - Identify and explain the different forces
    - Apply Eulers Equations to simple problems
- Advanced
    - Derive Navier-Stokes Equations from first principles
    - Apply Navier-Stokes Equations to more complicated problems

## Part 1: Different types of flows
### Reynolds Averaged Navier-Stokes Equations
$\frac{∂u}{∂t}$ + **u**$\frac{∂u}{∂x}$ + **v**$\frac{∂u}{∂y}$ + **w**$\frac{∂u}{∂z}$ = g<sub>x</sub> - $\frac{1}{ρ}\frac{∂P}{∂x} + V∇^2$**u** - ($\frac{∂w′u′}{∂x} + \frac{∂w′u′}{∂y} + \frac{∂w′u′}{∂z}$)

$\frac{∂v}{∂t}$ + **u**$\frac{∂v}{∂x}$ + **v**$\frac{∂v}{∂y}$ + **w**$\frac{∂v}{∂z}$ = g<sub>y</sub> - $\frac{1}{ρ}\frac{∂P}{∂y} + V∇^2$**v** - ($\frac{∂w′u′}{∂x} + \frac{∂w′u′}{∂y} + \frac{∂w′u′}{∂z}$)

$\frac{∂w}{∂t}$ + **u**$\frac{∂w}{∂x}$ + **v**$\frac{∂w}{∂y}$ + **w**$\frac{∂w}{∂z}$ = g<sub>z</sub> - $\frac{1}{ρ}\frac{∂P}{∂z} + V∇^2$**w** - ($\frac{∂w′u′}{∂x} + \frac{∂w′u′}{∂y} + \frac{∂w′u′}{∂z}$)

- where $∇^2 = \frac{∂^2}{∂x^2} + \frac{∂^2}{∂y^2} + \frac{∂^2}{∂z^2}$
- $V = \frac{μ}{ρ}$ = kinematic viscosity
- $μ$ = dynamic viscosity

### Ideal flow
**u**$\frac{∂u}{∂x}$ + **v**$\frac{∂u}{∂y}$ + **w**$\frac{∂u}{∂z}$ = g<sub>x</sub> - $\frac{1}{ρ}\frac{∂P}{∂x}$

### Viscous (laminar) flow
**u**$\frac{∂u}{∂x}$ + **v**$\frac{∂u}{∂y}$ + **w**$\frac{∂u}{∂z}$ = g<sub>x</sub> - $\frac{1}{ρ}\frac{∂P}{∂x} + V(\frac{∂^2u}{∂x^2} + \frac{∂^2u}{∂y^2} + \frac{∂^2u}{∂z^2})$

### Turbulent flow
**u**$\frac{∂u}{∂x}$ + **v**$\frac{∂u}{∂y}$ + **w**$\frac{∂u}{∂z}$ = g<sub>x</sub> - $\frac{1}{ρ}\frac{∂P}{∂x} + V∇^2$**u** - ($\frac{∂\overline{w′u′}}{∂x} + \frac{∂\overline{w′u′}}{∂y} + \frac{∂\overline{w′u′}}{∂z}$)

### Non-steady laminar flow
$\frac{∂u}{∂t}$ + **u**$\frac{∂u}{∂x}$ + **v**$\frac{∂u}{∂y}$ + **w**$\frac{∂u}{∂z}$ = g<sub>x</sub> - $\frac{1}{ρ}\frac{∂P}{∂x} + V(\frac{∂^2u}{∂x^2} + \frac{∂^2u}{∂y^2} + \frac{∂^2u}{∂z^2})$

### Non-steady turbulent flow
$\frac{∂u}{∂t}$ + **u**$\frac{∂u}{∂x}$ + **v**$\frac{∂u}{∂y}$ + **w**$\frac{∂u}{∂z}$ = g<sub>x</sub> - $\frac{1}{ρ}\frac{∂P}{∂x} + V∇^2$**u** - ($\frac{∂u′u′}{∂x} + \frac{∂u′v′}{∂y} + \frac{∂u′w′}{∂z}$)

### Navier-Stokes equation for non turbelent flow
$\frac{∂u}{∂t}$ + **u**$\frac{∂u}{∂x}$ + **v**$\frac{∂u}{∂y}$ + **w**$\frac{∂u}{∂z}$ = g<sub>x</sub> - $\frac{1}{ρ}\frac{∂P}{∂x} + V∇^2$**u**
    
$\frac{∂v}{∂t}$ + **u**$\frac{∂v}{∂x}$ + **v**$\frac{∂v}{∂y}$ + **w**$\frac{∂v}{∂z}$ = g<sub>x</sub> - $\frac{1}{ρ}\frac{∂P}{∂y} + V∇^2$**v**

$\frac{∂w}{∂t}$ + **u**$\frac{∂w}{∂x}$ + **v**$\frac{∂w}{∂y}$ + **w**$\frac{∂w}{∂z}$ = g<sub>x</sub> - $\frac{1}{ρ}\frac{∂P}{∂z} + V∇^2$**w**
- where $∇^2 = \frac{∂^2}{∂x^2} + \frac{∂^2}{∂y^2} + \frac{∂^2}{∂z^2}$
- $v = \frac{μ}{ρ}$ = kinematic viscosity
- μ = dynamic viscosity

### Conservation of Mass
- Incompressible fluid motion is subject to constraint:
       $\frac{∂u}{∂x} + \frac{∂v}{∂y} + \frac{∂w}{∂z} = 0$
- Derived from the principle of the conservation of mass
- Volume in the element = volume out of the element

### Navier-Stokes derivation
- Stems from the principle of conservation of momentum
- Equations are derived from Newton’s second Law
($δ$**F** = $δm$ **a**)
- Where $δm$ = $ρδxδyδz$
- In component form:
    
    δF<sub>x</sub> = δma<sub>x</sub> ⇒ a<sub>x</sub> = $\frac{δFx}{δm}$,

    δF<sub>y</sub> = δma<sub>y</sub> ⇒ a<sub>x</sub> = $\frac{δFy}{δm}$,

    δF<sub>z</sub> = δma<sub>z</sub> ⇒ a<sub>x</sub> = $\frac{δFz}{δm}$,

### Acceleration of a fluid particle
- Velocity components u, v , w are dependent on x, y , z, t
- Hence u(x, y, z, t), v (x, y , z, t) and w(x, y, z, t)
- We need to use the total derivative

    $\frac{du}{dt}$ = $\frac{∂u}{∂x}\frac{dx}{dt} + \frac{∂u}{∂y}\frac{dy}{dt} + \frac{∂u}{∂z}\frac{dz}{dt} + \frac{∂u}{∂t}\frac{dt}{dt}$
- Hence

    a<sub>x</sub> = **u**$\frac{∂u}{∂x}$ + **v**$\frac{∂u}{∂y}$ + **w**$\frac{∂u}{∂z}$ + $\frac{∂u}{∂t}$
- Hence acceleration in three directions:

    a<sub>x</sub> = **u**$\frac{∂u}{∂x}$ + **v**$\frac{∂u}{∂y}$ + **w**$\frac{∂u}{∂z}$ + $\frac{∂u}{∂t}$

    a<sub>y</sub> = **u**$\frac{∂v}{∂x}$ + **v**$\frac{∂v}{∂y}$ + **w**$\frac{∂v}{∂z}$ + $\frac{∂v}{∂t}$

    a<sub>z</sub> = **u**$\frac{∂w}{∂x}$ + **v**$\frac{∂w}{∂y}$ + **w**$\frac{∂w}{∂z}$ + $\frac{∂w}{∂t}$
- Composed of the convective accleration and the temporal acceleration (also known as local acceleration)

## Part 2: Euler's equation of motion
### Total force on fluid particles
**F** = **F**<sub>gravity</sub> + **F**<sub>pressure</sub> + **F**<sub>friction</sub>

- **Body forces**: acts throughout the entire body

    **F**<sub>gravity</sub>
- **Surface forces**: acts on the surface of the element

    **F**<sub>pressure</sub> and **F**<sub>friction</sub>

### Body forces
- The only body force, δF b, of interest is the weight of the
element:

    δF<sub>bx</sub> = δmg<sub>x</sub>

    δF<sub>by</sub> = δmg<sub>y</sub>

    δF<sub>bz</sub> = δmg<sub>z</sub>
- Where g<sub>x</sub> , g<sub>y</sub> , g<sub>z</sub> are the component of the acceleration of gravity vector in the x, y and z direction respectively
- Adopring the convention that y is positive vertically upwards. We have g<sub>x</sub> = g<sub>z</sub> = 0 and g<sub>y</sub> ≈ −9.81 m/s<sup>2</sup>

### Surface forces
- Normal stresses σ (pressure force δ**F**<sub>p</sub>)
- Shear stresses τ (friction force δ**F**<sub>f</sub>)

### Pressure force
- Pressure force is due to a change in pressure

    $\frac{δF~px~}{δm}$ = $-\frac{1}{ρ}\frac{∂P}{∂x}$

    $\frac{δF~py~}{δm}$ = $-\frac{1}{ρ}\frac{∂P}{∂y}$

    $\frac{δF~pz~}{δm}$ = $-\frac{1}{ρ}\frac{∂P}{∂y}$

### Euler’s equation of motion
- For inviscid flow (no friction hence no shear)

    $\frac{∂u}{∂t}$ + **u**$\frac{∂u}{∂x}$ + **v**$\frac{∂u}{∂y}$ + **w**$\frac{∂u}{∂z}$ = g<sub>x</sub> - $\frac{1}{ρ}\frac{∂P}{∂x}$

    $\frac{∂v}{∂t}$ + **u**$\frac{∂v}{∂x}$ + **v**$\frac{∂v}{∂y}$ + **w**$\frac{∂v}{∂z}$ = g<sub>y</sub> - $\frac{1}{ρ}\frac{∂P}{∂y}$

    $\frac{∂w}{∂t}$ + **u**$\frac{∂w}{∂x}$ + **v**$\frac{∂w}{∂y}$ + **w**$\frac{∂w}{∂z}$ = g<sub>z</sub> - $\frac{1}{ρ}\frac{∂P}{∂z}$
- Referred to as Euler’s equation of motion
- No general analytical solution exists to determine pressure and velocity within the flow field

### Euler's equations for static flow
- with condition P  = P<sub>0</sub> at y = 0
    
    P - P<sub>0</sub> = -gρy

### Bernoulli's equation along a streamline
