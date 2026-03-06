# Section 4 – Electromagnetism I (Solutions)

# Task 01 – Coulomb’s Law in a Symmetric Charge Configuration

## Problem Statement

Four point charges of $+1.0\ \text{C}$ are placed at the corners of a square of side length $1.0\ \text{m}$. A charge of $-2.0\ \text{C}$ is placed at the center of the square.

Determine the magnitude and direction of the electric force acting on the central charge.

## Theory

The electrostatic force between two point charges is given by Coulomb’s law:

$$
F = k \frac{|q_1 q_2|}{r^2}
$$

where

$$
k = \frac{1}{4\pi \varepsilon_0} \approx 8.99 \times 10^9\ \text{N m}^2\text{/C}^2
$$

The force is attractive for opposite charges and repulsive for like charges.

When several charges act on a test charge, the total force is the vector sum of all individual forces.

## Step-by-Step Solution

Each corner charge is positive, and the charge at the center is negative. Therefore, each individual force on the central charge points from the center toward the corresponding corner.

The square is perfectly symmetric, so the four forces have equal magnitude.

### Distance from the center to a corner

For a square of side length $a = 1.0\ \text{m}$, the diagonal is

$$
d = a\sqrt{2}
$$

Hence the distance from the center to a corner is half the diagonal:

$$
r = \frac{a\sqrt{2}}{2} = \frac{1}{\sqrt{2}}\ \text{m}
$$

### Magnitude of one force

For one corner charge $q = +1.0\ \text{C}$ and the central charge $Q = -2.0\ \text{C}$:

$$
F_1 = k \frac{|qQ|}{r^2}
$$

Substitute $r^2 = \left(\frac{1}{\sqrt{2}}\right)^2 = \frac{1}{2}$:

$$
F_1 = 8.99 \times 10^9 \frac{2}{1/2}
$$

$$
F_1 = 8.99 \times 10^9 \cdot 4
$$

$$
F_1 = 3.596 \times 10^{10}\ \text{N}
$$

### Vector sum

Although each individual force is nonzero, the four force vectors are arranged symmetrically:

- the force from the upper-right corner is canceled by the force from the lower-left corner,
- the force from the upper-left corner is canceled by the force from the lower-right corner.

Therefore, the net force is zero.

## Final Result

$$
|\vec{F}_{\text{net}}| = 0
$$

The net force has no direction because the total force is zero.

## Interpretation

This is a standard symmetry result. Even though the central charge is strongly attracted toward each corner charge individually, the four attractions cancel exactly because the charge is placed at the geometric center of the square.

# Task 02 – Electric Potential at the Center of a Square

## Problem Statement

Point charges of $+1\ \text{C}$, $-2\ \text{C}$, $+3\ \text{C}$, and $-4\ \text{C}$ are placed at the corners of a square of side length $1.0\ \text{m}$ in order. Determine the electric potential at the center.

## Theory

Electric potential due to a point charge is

$$
V = k \frac{q}{r}
$$

Electric potential is a scalar quantity, so the total potential is the algebraic sum of the contributions from all charges:

$$
V_{\text{tot}} = \sum_i k \frac{q_i}{r_i}
$$

## Step-by-Step Solution

All four charges are at the same distance from the center.

### Distance from the center to a corner

For a square of side length $a = 1.0\ \text{m}$,

$$
r = \frac{a\sqrt{2}}{2} = \frac{1}{\sqrt{2}}\ \text{m}
$$

### Sum of the charges

The total charge sum is

$$
q_{\text{sum}} = 1 - 2 + 3 - 4 = -2\ \text{C}
$$

### Total potential

Since all distances are equal,

$$
V_{\text{center}} = k \frac{q_{\text{sum}}}{r}
$$

Substitute the values:

$$
V_{\text{center}} = 8.99 \times 10^9 \cdot \frac{-2}{1/\sqrt{2}}
$$

$$
V_{\text{center}} = -17.98 \times 10^9 \sqrt{2}
$$

$$
V_{\text{center}} \approx -2.54 \times 10^{10}\ \text{V}
$$

## Final Result

$$
V_{\text{center}} \approx -2.54 \times 10^{10}\ \text{V}
$$

## Interpretation

The potential is negative because the negative charges dominate the algebraic sum. Unlike force, potential does not cancel by direction, because it is a scalar.

# Task 03 – Electrostatic Equilibrium Between Two Charges

## Problem Statement

Two positive charges are fixed on a line:

$$
q_1 = +4\ \text{C}, \qquad q_2 = +9\ \text{C}
$$

They are separated by $2\ \text{m}$. A third charge

$$
q_3 = +1\ \text{C}
$$

is placed somewhere on the line between them.

Determine the equilibrium position of $q_3$.

## Theory

For equilibrium, the net force on $q_3$ must be zero. Since all charges are positive, the forces on $q_3$ between the charges are repulsive and point in opposite directions.

Thus the equilibrium condition is

$$
F_1 = F_2
$$

Using Coulomb’s law,

$$
k \frac{q_1 q_3}{x^2} = k \frac{q_2 q_3}{(2-x)^2}
$$

## Step-by-Step Solution

Let the distance from $q_1$ to $q_3$ be $x$. Then the distance from $q_3$ to $q_2$ is $2-x$.

Set the magnitudes equal:

$$
k \frac{4 \cdot 1}{x^2} = k \frac{9 \cdot 1}{(2-x)^2}
$$

Cancel $k$:

$$
\frac{4}{x^2} = \frac{9}{(2-x)^2}
$$

Cross-multiply:

$$
4(2-x)^2 = 9x^2
$$

Take square roots. Since distances are positive and $0<x<2$:

$$
2(2-x) = 3x
$$

$$
4 - 2x = 3x
$$

$$
4 = 5x
$$

$$
x = \frac{4}{5} = 0.8\ \text{m}
$$

## Final Result

The equilibrium point is

$$
x = 0.8\ \text{m}
$$

from the $+4\ \text{C}$ charge, or equivalently

$$
2 - 0.8 = 1.2\ \text{m}
$$

from the $+9\ \text{C}$ charge.

## Interpretation

The equilibrium point lies closer to the smaller charge. This is necessary because the larger charge produces a stronger force, so the weaker-charge side must compensate by being closer.

# Task 04 – Electric and Gravitational Forces in a Hydrogen Atom

## Problem Statement

Calculate the magnitude of the electric force and the gravitational force between an electron and a proton in a hydrogen atom, using the average separation

$$
r \approx 5.3 \times 10^{-11}\ \text{m}
$$

Then determine the ratio

$$
\frac{F_e}{F_g}
$$

## Theory

The electric force is

$$
F_e = k \frac{e^2}{r^2}
$$

The gravitational force is

$$
F_g = G \frac{m_e m_p}{r^2}
$$

The ratio is therefore

$$
\frac{F_e}{F_g} = \frac{k e^2}{G m_e m_p}
$$

since $r^2$ cancels.

Useful constants:

$$
k = 8.99 \times 10^9
$$

$$
G = 6.67 \times 10^{-11}
$$

$$
e = 1.60 \times 10^{-19}\ \text{C}
$$

$$
m_e = 9.11 \times 10^{-31}\ \text{kg}
$$

$$
m_p = 1.67 \times 10^{-27}\ \text{kg}
$$

## Step-by-Step Solution

### Electric force

$$
F_e = k \frac{e^2}{r^2}
$$

Substitute values:

$$
F_e = 8.99 \times 10^9 \cdot \frac{(1.60 \times 10^{-19})^2}{(5.3 \times 10^{-11})^2}
$$

Compute numerator:

$$
(1.60 \times 10^{-19})^2 = 2.56 \times 10^{-38}
$$

Compute denominator:

$$
(5.3 \times 10^{-11})^2 = 2.809 \times 10^{-21}
$$

Thus

$$
F_e = 8.99 \times 10^9 \cdot \frac{2.56 \times 10^{-38}}{2.809 \times 10^{-21}}
$$

$$
F_e \approx 8.19 \times 10^{-8}\ \text{N}
$$

### Gravitational force

$$
F_g = G \frac{m_e m_p}{r^2}
$$

Substitute values:

$$
F_g = 6.67 \times 10^{-11} \cdot \frac{(9.11 \times 10^{-31})(1.67 \times 10^{-27})}{2.809 \times 10^{-21}}
$$

First multiply the masses:

$$
(9.11 \times 10^{-31})(1.67 \times 10^{-27}) \approx 1.52 \times 10^{-57}
$$

So

$$
F_g = 6.67 \times 10^{-11} \cdot \frac{1.52 \times 10^{-57}}{2.809 \times 10^{-21}}
$$

$$
F_g \approx 3.61 \times 10^{-47}\ \text{N}
$$

### Ratio

$$
\frac{F_e}{F_g} = \frac{8.19 \times 10^{-8}}{3.61 \times 10^{-47}}
$$

$$
\frac{F_e}{F_g} \approx 2.27 \times 10^{39}
$$

## Final Result

$$
F_e \approx 8.19 \times 10^{-8}\ \text{N}
$$

$$
F_g \approx 3.61 \times 10^{-47}\ \text{N}
$$

$$
\frac{F_e}{F_g} \approx 2.27 \times 10^{39}
$$

## Interpretation

The electric force between the proton and electron is enormously stronger than the gravitational force. At atomic scales, gravity is completely negligible compared with electromagnetism.

# Task 05 – Electric Field Required for Proton Levitation

## Problem Statement

Determine the electric field strength required to levitate a proton against Earth’s gravity.

Use

$$
m_p \approx 1.67 \times 10^{-27}\ \text{kg}
$$

$$
e \approx 1.6 \times 10^{-19}\ \text{C}
$$

$$
g \approx 9.8\ \text{m/s}^2
$$

## Theory

For levitation, the upward electric force must balance the downward gravitational force:

$$
qE = mg
$$

Hence

$$
E = \frac{mg}{q}
$$

For a proton, $q=e$.

## Step-by-Step Solution

Set electric force equal to weight:

$$
eE = m_p g
$$

Solve for $E$:

$$
E = \frac{m_p g}{e}
$$

Substitute values:

$$
E = \frac{(1.67 \times 10^{-27})(9.8)}{1.6 \times 10^{-19}}
$$

Compute numerator:

$$
1.67 \times 10^{-27} \cdot 9.8 \approx 1.64 \times 10^{-26}
$$

Thus

$$
E \approx \frac{1.64 \times 10^{-26}}{1.6 \times 10^{-19}}
$$

$$
E \approx 1.02 \times 10^{-7}\ \text{N/C}
$$

## Final Result

$$
E \approx 1.0 \times 10^{-7}\ \text{N/C}
$$

The electric field must point upward, because the proton has positive charge and its electric force is in the direction of the field.

## Interpretation

A very small electric field is enough to support a proton against gravity because the proton is extremely light.

# Task 06 – Electric Field of Two Point Charges

## Problem Statement

Two point charges are located at

- $+q$ at $(-a,0)$
- $+2q$ at $(a,0)$

Determine:

1. $\vec{E}(0,y)$, $\vec{E}(x,0)$, and the general field $\vec{E}(x,y)$,
2. the conditions for $E_x=0$, $E_y=0$, and $\vec{E}=0$,
3. the field for

$$
a = 0.2\ \text{m}, \quad y = 0.3\ \text{m}, \quad q = 2\ \mu\text{C}
$$

4. the limit $y \gg a$.

## Theory

The electric field of a point charge $Q$ at position $\vec{r}_0$ is

$$
\vec{E}(\vec{r}) = kQ \frac{\vec{r}-\vec{r}_0}{|\vec{r}-\vec{r}_0|^3}
$$

The total field is the vector sum of the fields of the two charges.

## Step-by-Step Solution

### 1. General expression for $\vec{E}(x,y)$

Let the observation point be

$$
\vec{r} = (x,y)
$$

For the charge $+q$ at $(-a,0)$:

$$
\vec{r} - \vec{r}_1 = (x+a,\ y)
$$

So

$$
\vec{E}_1 = kq \frac{(x+a,\ y)}{\left[(x+a)^2+y^2\right]^{3/2}}
$$

For the charge $+2q$ at $(a,0)$:

$$
\vec{r} - \vec{r}_2 = (x-a,\ y)
$$

So

$$
\vec{E}_2 = 2kq \frac{(x-a,\ y)}{\left[(x-a)^2+y^2\right]^{3/2}}
$$

Hence

$$
\vec{E}(x,y) =
kq \frac{(x+a,\ y)}{\left[(x+a)^2+y^2\right]^{3/2}}
+
2kq \frac{(x-a,\ y)}{\left[(x-a)^2+y^2\right]^{3/2}}
$$

Therefore the components are

$$
E_x(x,y) =
kq \frac{x+a}{\left[(x+a)^2+y^2\right]^{3/2}}
+
2kq \frac{x-a}{\left[(x-a)^2+y^2\right]^{3/2}}
$$

$$
E_y(x,y) =
kq \frac{y}{\left[(x+a)^2+y^2\right]^{3/2}}
+
2kq \frac{y}{\left[(x-a)^2+y^2\right]^{3/2}}
$$

### Field on the $y$-axis: $\vec{E}(0,y)$

Set $x=0$:

$$
E_x(0,y) =
kq \frac{a}{(a^2+y^2)^{3/2}}
+
2kq \frac{-a}{(a^2+y^2)^{3/2}}
$$

$$
E_x(0,y) = -kq \frac{a}{(a^2+y^2)^{3/2}}
$$

For the $y$-component:

$$
E_y(0,y) =
kq \frac{y}{(a^2+y^2)^{3/2}}
+
2kq \frac{y}{(a^2+y^2)^{3/2}}
$$

$$
E_y(0,y) = 3kq \frac{y}{(a^2+y^2)^{3/2}}
$$

Thus

$$
\vec{E}(0,y) =
\left(
-kq \frac{a}{(a^2+y^2)^{3/2}},
\ 
3kq \frac{y}{(a^2+y^2)^{3/2}}
\right)
$$

### Field on the $x$-axis: $\vec{E}(x,0)$

Set $y=0$:

$$
E_y(x,0)=0
$$

and

$$
E_x(x,0) =
kq \frac{x+a}{|x+a|^3}
+
2kq \frac{x-a}{|x-a|^3}
$$

Thus

$$
\vec{E}(x,0) =
\left(
kq \frac{x+a}{|x+a|^3}
+
2kq \frac{x-a}{|x-a|^3},
\ 0
\right)
$$

### 2. Conditions for $E_x=0$, $E_y=0$, and $\vec{E}=0$

#### Condition for $E_y=0$

From the general formula,

$$
E_y(x,y) =
kq y
\left[
\frac{1}{\left[(x+a)^2+y^2\right]^{3/2}}
+
\frac{2}{\left[(x-a)^2+y^2\right]^{3/2}}
\right]
$$

The bracket is always positive, so

$$
E_y=0 \quad \Longrightarrow \quad y=0
$$

#### Condition for $E_x=0$ on the $x$-axis

Since total zero field must also satisfy $E_y=0$, it is enough to solve on the $x$-axis:

$$
kq \frac{x+a}{|x+a|^3}
+
2kq \frac{x-a}{|x-a|^3}
=0
$$

Cancel $kq$:

$$
\frac{x+a}{|x+a|^3}
+
2 \frac{x-a}{|x-a|^3}
=0
$$

The only possible location is between the charges, where $-a < x < a$. In that region:

$$
|x+a| = x+a, \qquad |x-a| = a-x
$$

and

$$
\frac{x+a}{|x+a|^3} = \frac{1}{(x+a)^2}
$$

$$
\frac{x-a}{|x-a|^3} = -\frac{1}{(a-x)^2}
$$

So the equation becomes

$$
\frac{1}{(x+a)^2} - \frac{2}{(a-x)^2} = 0
$$

$$
\frac{1}{(x+a)^2} = \frac{2}{(a-x)^2}
$$

Take square roots:

$$
a-x = \sqrt{2}(x+a)
$$

Solve for $x$:

$$
a - x = \sqrt{2}x + \sqrt{2}a
$$

$$
a(1-\sqrt{2}) = x(1+\sqrt{2})
$$

$$
x = a \frac{1-\sqrt{2}}{1+\sqrt{2}}
$$

Rationalize:

$$
x = a(1-\sqrt{2})^2 / (1-2)
$$

A simpler direct simplification is

$$
x = a(2\sqrt{2}-3)
$$

Numerically,

$$
2\sqrt{2}-3 \approx -0.1716
$$

Thus the zero-field point lies slightly to the left of the origin.

Therefore

$$
\vec{E}=0
$$

at

$$
y=0, \qquad x = a(2\sqrt{2}-3)
$$

### 3. Numerical field for $a=0.2\ \text{m}$, $y=0.3\ \text{m}$, $q=2\ \mu\text{C}$

This refers to the point $(0,y)$.

Use

$$
\vec{E}(0,y) =
\left(
-kq \frac{a}{(a^2+y^2)^{3/2}},
\ 
3kq \frac{y}{(a^2+y^2)^{3/2}}
\right)
$$

Compute:

$$
a^2+y^2 = 0.2^2 + 0.3^2 = 0.13
$$

$$
(a^2+y^2)^{3/2} = 0.13^{3/2} \approx 0.04687
$$

Also,

$$
kq = (8.99 \times 10^9)(2 \times 10^{-6}) \approx 1.798 \times 10^4
$$

Then

$$
E_x = - \frac{(1.798 \times 10^4)(0.2)}{0.04687}
\approx -7.67 \times 10^4\ \text{N/C}
$$

$$
E_y = \frac{3(1.798 \times 10^4)(0.3)}{0.04687}
\approx 3.45 \times 10^5\ \text{N/C}
$$

So

$$
\vec{E}(0,0.3) \approx
\left(
-7.67 \times 10^4,\ 
3.45 \times 10^5
\right)\ \text{N/C}
$$

Its magnitude is

$$
|\vec{E}| = \sqrt{E_x^2 + E_y^2}
$$

$$
|\vec{E}| \approx 3.53 \times 10^5\ \text{N/C}
$$

### 4. Limit $y \gg a$

For the point $(0,y)$:

$$
\vec{E}(0,y) =
\left(
-kq \frac{a}{(a^2+y^2)^{3/2}},
\ 
3kq \frac{y}{(a^2+y^2)^{3/2}}
\right)
$$

If $y \gg a$, then

$$
(a^2+y^2)^{3/2} \approx y^3
$$

Therefore,

$$
E_x \approx -kq \frac{a}{y^3}
$$

$$
E_y \approx 3kq \frac{1}{y^2}
$$

Thus,

$$
\vec{E}(0,y) \approx
\left(
-kq \frac{a}{y^3},
\ 
\frac{3kq}{y^2}
\right)
$$

The dominant term is the $y$-component, so far away the system behaves approximately like a single point charge of total charge $3q$.

## Final Result

General field:

$$
\vec{E}(x,y) =
kq \frac{(x+a,\ y)}{\left[(x+a)^2+y^2\right]^{3/2}}
+
2kq \frac{(x-a,\ y)}{\left[(x-a)^2+y^2\right]^{3/2}}
$$

On the $y$-axis:

$$
\vec{E}(0,y) =
\left(
-kq \frac{a}{(a^2+y^2)^{3/2}},
\ 
3kq \frac{y}{(a^2+y^2)^{3/2}}
\right)
$$

On the $x$-axis:

$$
\vec{E}(x,0) =
\left(
kq \frac{x+a}{|x+a|^3}
+
2kq \frac{x-a}{|x-a|^3},
\ 0
\right)
$$

Zero field occurs at

$$
y=0, \qquad x = a(2\sqrt{2}-3)
$$

For

$$
a=0.2\ \text{m}, \quad y=0.3\ \text{m}, \quad q=2\ \mu\text{C}
$$

at the point $(0,0.3)$:

$$
\vec{E} \approx
\left(
-7.67 \times 10^4,\ 
3.45 \times 10^5
\right)\ \text{N/C}
$$

## Interpretation

Near the charges, the field is strongly asymmetric because one charge is twice as large as the other. Far away, the system looks like a single effective charge $3q$.

# Task 07 – Cyclotron Motion of an Electron

## Problem Statement

An electron is accelerated from rest through a potential difference of $5000\ \text{V}$. It then enters a uniform magnetic field

$$
B = 0.1\ \text{T}
$$

perpendicular to its velocity.

Determine the radius of the circular path.

## Theory

An electron accelerated through a potential difference $V$ gains kinetic energy:

$$
eV = \frac{1}{2}mv^2
$$

Thus,

$$
v = \sqrt{\frac{2eV}{m}}
$$

In a uniform magnetic field perpendicular to the velocity, the magnetic force provides the centripetal force:

$$
qvB = \frac{mv^2}{r}
$$

So the radius is

$$
r = \frac{mv}{qB}
$$

## Step-by-Step Solution

### Speed after acceleration

Use

$$
v = \sqrt{\frac{2eV}{m_e}}
$$

Substitute

$$
e = 1.60 \times 10^{-19}\ \text{C}
$$

$$
V = 5000\ \text{V}
$$

$$
m_e = 9.11 \times 10^{-31}\ \text{kg}
$$

Then

$$
v = \sqrt{\frac{2(1.60 \times 10^{-19})(5000)}{9.11 \times 10^{-31}}}
$$

$$
v = \sqrt{1.76 \times 10^{15}}
$$

$$
v \approx 4.19 \times 10^7\ \text{m/s}
$$

### Radius in the magnetic field

Use

$$
r = \frac{m_e v}{eB}
$$

Substitute values:

$$
r = \frac{(9.11 \times 10^{-31})(4.19 \times 10^7)}{(1.60 \times 10^{-19})(0.1)}
$$

$$
r \approx 2.38 \times 10^{-3}\ \text{m}
$$

## Final Result

$$
r \approx 2.4 \times 10^{-3}\ \text{m}
$$

or

$$
r \approx 2.4\ \text{mm}
$$

## Interpretation

Even after a fairly large accelerating voltage, the electron’s mass is so small that a modest magnetic field bends it into a very tight circular path.

# Task 08 – Magnitude of the Lorentz Force

## Problem Statement

A charged particle has

$$
q = 2 \times 10^{-19}\ \text{C}
$$

$$
m = 4 \times 10^{-27}\ \text{kg}
$$

It enters a magnetic field

$$
B = 0.5\ \text{T}
$$

with speed

$$
v = 10^6\ \text{m/s}
$$

perpendicular to the field.

Determine the magnitude of the Lorentz force.

## Theory

The magnetic Lorentz force magnitude is

$$
F = qvB\sin\theta
$$

For motion perpendicular to the field,

$$
\theta = 90^\circ
$$

so

$$
\sin\theta = 1
$$

and

$$
F = qvB
$$

## Step-by-Step Solution

Substitute the values:

$$
F = (2 \times 10^{-19})(10^6)(0.5)
$$

$$
F = 1.0 \times 10^{-13}\ \text{N}
$$

## Final Result

$$
F = 1.0 \times 10^{-13}\ \text{N}
$$

## Interpretation

The magnetic force is perpendicular to both the velocity and the magnetic field, so it changes the direction of motion but not the speed.

# Task 09 – Vector Lorentz Force on a Proton

## Problem Statement

A proton moves with velocity

$$
\vec{v} = (2\hat{i} - 4\hat{j} + \hat{k})\ \text{m/s}
$$

in a magnetic field

$$
\vec{B} = (\hat{i} + 2\hat{j} - \hat{k})\ \text{T}
$$

Determine the magnitude of the magnetic force on the proton.

## Theory

The magnetic force on a charge is

$$
\vec{F} = q \vec{v} \times \vec{B}
$$

Its magnitude is

$$
|\vec{F}| = q |\vec{v} \times \vec{B}|
$$

For a proton,

$$
q = e = 1.60 \times 10^{-19}\ \text{C}
$$

## Step-by-Step Solution

### Compute the cross product

Write the determinant:

$$
\vec{v} \times \vec{B} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
2 & -4 & 1 \\
1 & 2 & -1
\end{vmatrix}
$$

Expand:

$$
\vec{v} \times \vec{B}
=
\hat{i}\left[(-4)(-1) - (1)(2)\right]
-
\hat{j}\left[(2)(-1) - (1)(1)\right]
+
\hat{k}\left[(2)(2) - (-4)(1)\right]
$$

$$
\vec{v} \times \vec{B}
=
\hat{i}(4-2) - \hat{j}(-2-1) + \hat{k}(4+4)
$$

$$
\vec{v} \times \vec{B} = 2\hat{i} + 3\hat{j} + 8\hat{k}
$$

### Magnitude of the cross product

$$
|\vec{v} \times \vec{B}| = \sqrt{2^2 + 3^2 + 8^2}
$$

$$
|\vec{v} \times \vec{B}| = \sqrt{4+9+64} = \sqrt{77}
$$

### Force magnitude

$$
|\vec{F}| = e \sqrt{77}
$$

Substitute $e = 1.60 \times 10^{-19}\ \text{C}$:

$$
|\vec{F}| = (1.60 \times 10^{-19})\sqrt{77}
$$

$$
|\vec{F}| \approx 1.40 \times 10^{-18}\ \text{N}
$$

## Final Result

$$
|\vec{F}| \approx 1.40 \times 10^{-18}\ \text{N}
$$

## Interpretation

The magnetic force depends only on the component of velocity perpendicular to the magnetic field. The cross product automatically captures both the direction and the effective perpendicular contribution.

# Task 10 – Magnetic Force on a Current-Carrying Wire

## Problem Statement

A straight wire of length

$$
L = 2.0\ \text{m}
$$

carries current

$$
I = 10\ \text{A}
$$

in a uniform magnetic field

$$
B = 0.5\ \text{T}
$$

Determine the magnetic force on the wire when the angle between the wire and the magnetic field is

a) $90^\circ$

b) $45^\circ$

c) $0^\circ$

## Theory

The magnitude of the magnetic force on a straight current-carrying wire is

$$
F = ILB\sin\theta
$$

where $\theta$ is the angle between the direction of current and the magnetic field.

## Step-by-Step Solution

First compute the constant factor:

$$
ILB = (10)(2.0)(0.5) = 10
$$

So

$$
F = 10\sin\theta
$$

### a) Angle $90^\circ$

$$
F = 10\sin 90^\circ = 10 \cdot 1 = 10\ \text{N}
$$

### b) Angle $45^\circ$

$$
F = 10\sin 45^\circ = 10 \cdot \frac{\sqrt{2}}{2}
$$

$$
F = 5\sqrt{2}\ \text{N} \approx 7.07\ \text{N}
$$

### c) Angle $0^\circ$

$$
F = 10\sin 0^\circ = 0
$$

## Final Result

For the three angles:

$$
F_{90^\circ} = 10\ \text{N}
$$

$$
F_{45^\circ} = 5\sqrt{2}\ \text{N} \approx 7.07\ \text{N}
$$

$$
F_{0^\circ} = 0
$$

## Interpretation

The force is maximum when the wire is perpendicular to the field and zero when the wire is parallel to the field, because only the component perpendicular to the field contributes.