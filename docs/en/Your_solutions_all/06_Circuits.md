# Section 6 – Circuits (Solutions)

# Task 01 – Series and Parallel Circuit

## Problem Statement

Three resistors are given:

$$
R_1 = 15\ \Omega, \qquad R_2 = 30\ \Omega, \qquad R_3 = 50\ \Omega
$$

A battery of voltage

$$
V = 12\ \text{V}
$$

is connected to them in two cases:

- all resistors in series,
- all resistors in parallel.

Determine the equivalent resistance and the battery current in each case.

## Theory

For resistors in series,

$$
R_{\text{eq}} = R_1 + R_2 + R_3
$$

For resistors in parallel,

$$
\frac{1}{R_{\text{eq}}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}
$$

The total current drawn from the battery is given by Ohm’s law:

$$
I = \frac{V}{R_{\text{eq}}}
$$

## Step-by-Step Solution

### Series connection

The equivalent resistance is

$$
R_{\text{eq, series}} = 15 + 30 + 50
$$

$$
R_{\text{eq, series}} = 95\ \Omega
$$

The current from the battery is

$$
I_{\text{series}} = \frac{12}{95}
$$

$$
I_{\text{series}} \approx 0.126\ \text{A}
$$

### Parallel connection

Compute the reciprocal:

$$
\frac{1}{R_{\text{eq, parallel}}} = \frac{1}{15} + \frac{1}{30} + \frac{1}{50}
$$

Use a common denominator of $150$:

$$
\frac{1}{15} = \frac{10}{150}, \qquad \frac{1}{30} = \frac{5}{150}, \qquad \frac{1}{50} = \frac{3}{150}
$$

Thus,

$$
\frac{1}{R_{\text{eq, parallel}}} = \frac{10+5+3}{150} = \frac{18}{150} = \frac{3}{25}
$$

So,

$$
R_{\text{eq, parallel}} = \frac{25}{3}\ \Omega \approx 8.33\ \Omega
$$

The battery current is

$$
I_{\text{parallel}} = \frac{12}{25/3} = 12 \cdot \frac{3}{25}
$$

$$
I_{\text{parallel}} = \frac{36}{25} = 1.44\ \text{A}
$$

## Final Result

Series:

$$
R_{\text{eq, series}} = 95\ \Omega
$$

$$
I_{\text{series}} \approx 0.126\ \text{A}
$$

Parallel:

$$
R_{\text{eq, parallel}} = \frac{25}{3}\ \Omega \approx 8.33\ \Omega
$$

$$
I_{\text{parallel}} = 1.44\ \text{A}
$$

## Interpretation

The series connection gives a much larger equivalent resistance, so the current is small. The parallel connection gives a much smaller equivalent resistance, so the battery delivers a much larger current.

# Task 02 – All Possible Equivalent Resistances from Three $1\ \Omega$ Resistors

## Problem Statement

You have exactly three resistors, each of resistance

$$
R = 1\ \Omega
$$

List all unique equivalent resistances obtainable by combining them.

## Theory

With three identical resistors, distinct equivalent resistances come from different series-parallel combinations.

The basic rules are:

- series:

$$
R_{\text{series}} = R_1 + R_2
$$

- parallel:

$$
R_{\text{parallel}} = \frac{R_1 R_2}{R_1 + R_2}
$$

## Step-by-Step Solution

Using all three resistors, the distinct configurations are as follows.

### All three in series

$$
R_{\text{eq}} = 1 + 1 + 1 = 3\ \Omega
$$

### All three in parallel

$$
\frac{1}{R_{\text{eq}}} = 1 + 1 + 1 = 3
$$

$$
R_{\text{eq}} = \frac{1}{3}\ \Omega
$$

### Two in series, then in parallel with the third

Two in series give

$$
R_s = 1 + 1 = 2\ \Omega
$$

Now put this in parallel with $1\ \Omega$:

$$
R_{\text{eq}} = \frac{(2)(1)}{2+1} = \frac{2}{3}\ \Omega
$$

### Two in parallel, then in series with the third

Two in parallel give

$$
R_p = \frac{1 \cdot 1}{1+1} = \frac{1}{2}\ \Omega
$$

Now add the third in series:

$$
R_{\text{eq}} = \frac{1}{2} + 1 = \frac{3}{2}\ \Omega
$$

## Final Result

All unique equivalent resistances are

$$
\frac{1}{3}\ \Omega, \qquad \frac{2}{3}\ \Omega, \qquad \frac{3}{2}\ \Omega, \qquad 3\ \Omega
$$

## Interpretation

Even with only three identical resistors, the arrangement changes the total resistance significantly. Parallel combinations reduce resistance, while series combinations increase it.

# Task 03 – Mixed Circuit with $5\ \Omega$ Resistors

## Problem Statement

Determine the equivalent resistance of the circuit shown in the figure, where every resistor has resistance

$$
5\ \Omega
$$

## Theory

To compute an equivalent resistance from a circuit diagram, the exact connectivity of the resistors must be known.

## Step-by-Step Solution

The circuit diagram referenced as `image-r1.png` is not present in the current conversation, so the resistor connections cannot be reconstructed reliably.

Without the figure, the equivalent resistance cannot be determined uniquely.

## Final Result

A numerical result cannot be given because the circuit diagram is missing.

## Interpretation

For mixed resistor networks, the geometry of the connections is essential. The same resistor values can produce many different equivalent resistances depending on how the nodes are connected.

# Task 04 – Mixed Circuit with $10\ \Omega$ Resistors

## Problem Statement

Determine the equivalent resistance of the circuit shown in the figure, where every resistor has resistance

$$
10\ \Omega
$$

## Theory

Equivalent resistance depends on the exact series-parallel structure of the network.

## Step-by-Step Solution

The circuit diagram referenced as `image-r2.png` is not present in the current conversation, so the topology of the circuit is unknown.

Without the figure, no unique equivalent resistance can be computed.

## Final Result

A numerical result cannot be given because the circuit diagram is missing.

## Interpretation

A resistor network problem cannot be solved from resistor values alone; the full connection pattern is required.

# Task 05 – Kirchhoff’s Laws in a Two-Loop Circuit

## Problem Statement

Using Kirchhoff’s laws, determine the currents $I_1$, $I_2$, and $I_3$ in the circuit described by:

- left loop: source $\mathcal{E}_1 = 4.5\ \text{V}$ with internal resistance $r_w = 1\ \Omega$ and resistor $R_1 = 20\ \Omega$,
- right loop: source $\mathcal{E}_2 = 9\ \text{V}$ with internal resistance $r_w = 1\ \Omega$,
- shared branch: resistor $R_2 = 10\ \Omega$.

## Theory

Kirchhoff’s laws consist of:

- junction law:

$$
\sum I_{\text{in}} = \sum I_{\text{out}}
$$

- loop law:

$$
\sum \Delta V = 0
$$

Because the exact orientation shown in `image-k1.png` is not available here, a completely unambiguous sign convention cannot be extracted from the figure. Still, the circuit can be solved from the textual description by assigning node voltages.

## Step-by-Step Solution

Let the bottom node be the reference:

$$
V_B = 0
$$

Let the top-left node be $V_L$ and the top-right node be $V_R$.

The left branch contains source $\mathcal{E}_1$ and internal resistance $1\ \Omega$ in series with $R_1=20\ \Omega$, so the total resistance in that branch is

$$
R_{\text{left}} = 21\ \Omega
$$

The right source branch has total resistance

$$
R_{\text{right}} = 1\ \Omega
$$

The shared resistor is

$$
R_2 = 10\ \Omega
$$

Assume both sources raise potential from bottom to top.

### Branch currents

Current through the left branch from node $L$ to bottom:

$$
I_1 = \frac{V_L - \mathcal{E}_1}{21}
$$

Current through the shared resistor from node $R$ to bottom:

$$
I_2 = \frac{V_R}{10}
$$

Current through the right source branch from node $R$ to bottom:

$$
I_3 = \frac{V_R - \mathcal{E}_2}{1}
$$

The top-left and top-right nodes are connected by an ideal wire through the ammeter, so

$$
V_L = V_R = V
$$

At the top node, Kirchhoff’s current law gives

$$
\frac{V - 4.5}{21} + \frac{V}{10} + (V - 9) = 0
$$

Multiply by $210$:

$$
10(V-4.5) + 21V + 210(V-9) = 0
$$

$$
10V - 45 + 21V + 210V - 1890 = 0
$$

$$
241V - 1935 = 0
$$

$$
V = \frac{1935}{241} \approx 8.03\ \text{V}
$$

Now compute the currents.

### Current through $R_1$

$$
I_1 = \frac{8.03 - 4.5}{21}
$$

$$
I_1 \approx \frac{3.53}{21} \approx 0.168\ \text{A}
$$

### Current through $R_2$

$$
I_2 = \frac{8.03}{10} \approx 0.803\ \text{A}
$$

### Current in the right branch

$$
I_3 = 8.03 - 9 = -0.97\ \text{A}
$$

The negative sign means the actual current direction is opposite to the assumed downward direction. Its magnitude is

$$
|I_3| \approx 0.97\ \text{A}
$$

## Final Result

Under the stated orientation convention,

$$
I_1 \approx 0.168\ \text{A}
$$

$$
I_2 \approx 0.803\ \text{A}
$$

$$
I_3 \approx -0.970\ \text{A}
$$

So the actual right-branch current has magnitude

$$
|I_3| \approx 0.970\ \text{A}
$$

in the opposite direction to the initial assumption.

## Interpretation

The larger $9\ \text{V}$ source dominates the circuit and drives current against the assumed direction in one branch. The exact arrow directions in the original figure would determine how the signs should be reported on the final diagram.

# Task 06 – Ammeter Current

## Problem Statement

Calculate the current flowing through the ammeter in the circuit shown in `image-k2.png`.

## Theory

An ammeter current depends on the exact node connections and branch elements in the diagram.

## Step-by-Step Solution

The figure `image-k2.png` is not included in the current conversation, so the circuit topology is unavailable.

Therefore the ammeter current cannot be determined uniquely.

## Final Result

A numerical answer cannot be given because the circuit diagram is missing.

## Interpretation

In circuit problems involving an ammeter, the exact branch placement is crucial. Even a small change in the diagram can completely change the ammeter reading.

# Task 07 – Capacitors in Parallel

## Problem Statement

Two capacitors,

$$
C_1 = 4\ \mu\text{F}, \qquad C_2 = 6\ \mu\text{F}
$$

are connected in parallel to a

$$
10\ \text{V}
$$

battery.

Determine the total charge stored and the total energy stored.

## Theory

For capacitors in parallel,

$$
C_{\text{eq}} = C_1 + C_2
$$

The total charge is

$$
Q = C_{\text{eq}}V
$$

The total stored energy is

$$
U = \frac{1}{2}C_{\text{eq}}V^2
$$

## Step-by-Step Solution

### Equivalent capacitance

$$
C_{\text{eq}} = 4\ \mu\text{F} + 6\ \mu\text{F} = 10\ \mu\text{F}
$$

Convert to farads:

$$
C_{\text{eq}} = 10 \times 10^{-6}\ \text{F}
$$

### Total charge

$$
Q = C_{\text{eq}}V = (10 \times 10^{-6})(10)
$$

$$
Q = 100 \times 10^{-6}\ \text{C} = 100\ \mu\text{C}
$$

### Total energy

$$
U = \frac{1}{2}C_{\text{eq}}V^2
$$

$$
U = \frac{1}{2}(10 \times 10^{-6})(10)^2
$$

$$
U = \frac{1}{2}(10 \times 10^{-6})(100)
$$

$$
U = 5.0 \times 10^{-4}\ \text{J}
$$

## Final Result

$$
Q_{\text{tot}} = 100\ \mu\text{C}
$$

$$
U_{\text{tot}} = 5.0 \times 10^{-4}\ \text{J}
$$

## Interpretation

In parallel, capacitances add directly, so the system behaves like one larger capacitor at the same voltage.

# Task 08 – AC Voltage Across a Resistor

## Problem Statement

The current in an AC circuit is

$$
I(t) = 2\sin(120\pi t)
$$

The circuit contains a single resistor of resistance

$$
R = 50\ \Omega
$$

Determine the voltage across the resistor.

## Theory

For a pure resistor,

$$
V(t) = RI(t)
$$

Current and voltage are in phase.

## Step-by-Step Solution

Substitute Ohm’s law:

$$
V(t) = 50 \cdot 2\sin(120\pi t)
$$

$$
V(t) = 100\sin(120\pi t)
$$

## Final Result

$$
V(t) = 100\sin(120\pi t)\ \text{V}
$$

## Interpretation

Because the circuit contains only a resistor, the voltage has the same sinusoidal shape and phase as the current. Only the amplitude changes by the factor $R$.

# Task 09 – Current from Charge Function

## Problem Statement

The charge flowing through a wire is

$$
Q(t) = 5t^2 + 5
$$

Determine the current at

$$
t = 3\ \text{s}
$$

## Theory

Electric current is the time derivative of charge:

$$
I(t) = \frac{dQ}{dt}
$$

## Step-by-Step Solution

Differentiate:

$$
I(t) = \frac{d}{dt}(5t^2 + 5) = 10t
$$

Now evaluate at $t=3$:

$$
I(3) = 10 \cdot 3 = 30\ \text{A}
$$

## Final Result

$$
I(3) = 30\ \text{A}
$$

## Interpretation

The current increases linearly with time because the charge function is quadratic.

# Task 10 – Average Current of a Lightning Bolt

## Problem Statement

A lightning bolt transfers charge

$$
Q = 30\ \text{C}
$$

to the ground in time

$$
\Delta t = 2\ \text{ms}
$$

Determine the average current.

## Theory

Average current is

$$
I_{\text{avg}} = \frac{\Delta Q}{\Delta t}
$$

## Step-by-Step Solution

Convert time to seconds:

$$
2\ \text{ms} = 2 \times 10^{-3}\ \text{s}
$$

Now compute:

$$
I_{\text{avg}} = \frac{30}{2 \times 10^{-3}}
$$

$$
I_{\text{avg}} = 1.5 \times 10^4\ \text{A}
$$

## Final Result

$$
I_{\text{avg}} = 1.5 \times 10^4\ \text{A}
$$

## Interpretation

Lightning currents are extremely large because a substantial amount of charge is transferred in a very short time interval.

# Task 11 – Power and Energy in a Resistor

## Problem Statement

A resistor has resistance

$$
R = 100\ \Omega
$$

A voltage of

$$
V = 50\ \text{V}
$$

is applied across it.

Determine:

- the power dissipated,
- the energy consumed in $5$ minutes.

## Theory

For a resistor,

$$
P = \frac{V^2}{R}
$$

Energy is related to power by

$$
E = Pt
$$

## Step-by-Step Solution

### Power

$$
P = \frac{50^2}{100}
$$

$$
P = \frac{2500}{100} = 25\ \text{W}
$$

### Energy in 5 minutes

Convert time:

$$
5\ \text{min} = 300\ \text{s}
$$

Now compute energy:

$$
E = Pt = 25 \cdot 300
$$

$$
E = 7500\ \text{J}
$$

## Final Result

$$
P = 25\ \text{W}
$$

$$
E = 7500\ \text{J}
$$

## Interpretation

The resistor continuously converts electrical energy into heat. Over several minutes, even moderate power leads to a noticeable energy consumption.

# Task 12 – Transformer Currents

## Problem Statement

A transformer has

$$
N_p = 1000
$$

turns on the primary and

$$
N_s = 200
$$

turns on the secondary. The primary voltage is

$$
V_p = 120\ \text{V}
$$

and the secondary current is

$$
I_s = 3\ \text{A}
$$

Determine the secondary voltage and the primary current.

## Theory

For an ideal transformer,

$$
\frac{V_s}{V_p} = \frac{N_s}{N_p}
$$

and power conservation gives

$$
V_p I_p = V_s I_s
$$

Equivalently,

$$
\frac{I_s}{I_p} = \frac{N_p}{N_s}
$$

## Step-by-Step Solution

### Secondary voltage

$$
V_s = V_p \frac{N_s}{N_p}
$$

$$
V_s = 120 \cdot \frac{200}{1000}
$$

$$
V_s = 120 \cdot 0.2 = 24\ \text{V}
$$

### Primary current

Use power conservation:

$$
I_p = \frac{V_s I_s}{V_p}
$$

$$
I_p = \frac{24 \cdot 3}{120}
$$

$$
I_p = \frac{72}{120} = 0.6\ \text{A}
$$

## Final Result

$$
V_s = 24\ \text{V}
$$

$$
I_p = 0.6\ \text{A}
$$

## Interpretation

This transformer steps voltage down by a factor of $5$, so the current is stepped up by a factor of $5$ on the secondary side.

# Task 13 – Transformer Ratio

## Problem Statement

A transformer steps voltage down from

$$
120\ \text{V}
$$

to

$$
9.0\ \text{V}
$$

If the primary has

$$
N_p = 400
$$

turns, determine the number of turns on the secondary.

## Theory

For an ideal transformer,

$$
\frac{V_s}{V_p} = \frac{N_s}{N_p}
$$

## Step-by-Step Solution

Solve for $N_s$:

$$
N_s = N_p \frac{V_s}{V_p}
$$

Substitute values:

$$
N_s = 400 \cdot \frac{9.0}{120}
$$

$$
N_s = 400 \cdot 0.075 = 30
$$

## Final Result

$$
N_s = 30
$$

turns.

## Interpretation

A strong step-down in voltage requires far fewer turns on the secondary than on the primary.

# Task 14 – Series RLC Circuit and Damped Oscillator Analogy

## Problem Statement

Write the differential equation for a series RLC circuit with voltage source $V$, resistor $R$, inductor $L$, and capacitor $C$. Assume the current is $I(t)$ and the capacitor voltage is $V_C(t)$. Compare this equation with the damped harmonic oscillator equation.

## Theory

Kirchhoff’s loop law in a series RLC circuit is

$$
V(t) = V_R + V_L + V_C
$$

with

$$
V_R = RI
$$

$$
V_L = L\frac{dI}{dt}
$$

$$
V_C = \frac{q}{C}
$$

and

$$
I = \frac{dq}{dt}
$$

## Step-by-Step Solution

### Equation in terms of charge

Using $q(t)$ as the capacitor charge, Kirchhoff’s law gives

$$
V(t) = R\frac{dq}{dt} + L\frac{d^2 q}{dt^2} + \frac{q}{C}
$$

Rearrange:

$$
L\frac{d^2 q}{dt^2} + R\frac{dq}{dt} + \frac{1}{C}q = V(t)
$$

This is the standard second-order equation for a driven series RLC circuit.

### Equation in terms of current

Differentiate the charge equation with respect to time:

$$
L\frac{d^2 I}{dt^2} + R\frac{dI}{dt} + \frac{1}{C}I = \frac{dV}{dt}
$$

For constant or zero source voltage, this simplifies accordingly.

### Comparison with damped harmonic oscillator

The damped oscillator equation is

$$
m\frac{d^2 x}{dt^2} + b\frac{dx}{dt} + kx = F(t)
$$

Comparing

$$
L\frac{d^2 q}{dt^2} + R\frac{dq}{dt} + \frac{1}{C}q = V(t)
$$

with

$$
m\frac{d^2 x}{dt^2} + b\frac{dx}{dt} + kx = F(t)
$$

gives the analogies:

$$
L \longleftrightarrow m
$$

$$
R \longleftrightarrow b
$$

$$
\frac{1}{C} \longleftrightarrow k
$$

$$
q \longleftrightarrow x
$$

$$
V(t) \longleftrightarrow F(t)
$$

## Final Result

Series RLC equation in charge form:

$$
L\frac{d^2 q}{dt^2} + R\frac{dq}{dt} + \frac{1}{C}q = V(t)
$$

Equivalent current form:

$$
L\frac{d^2 I}{dt^2} + R\frac{dI}{dt} + \frac{1}{C}I = \frac{dV}{dt}
$$

Analogy with the damped oscillator:

$$
L \leftrightarrow m, \qquad R \leftrightarrow b, \qquad \frac{1}{C} \leftrightarrow k, \qquad q \leftrightarrow x
$$

## Interpretation

An RLC circuit behaves mathematically like a damped mass-spring system. Inductance plays the role of inertia, resistance plays the role of damping, and capacitance provides the restoring effect.

# Task 15 – Equivalent Resistance of a Resistor Cube

## Problem Statement

A cube is made from $12$ identical resistors, each of resistance

$$
R
$$

placed along its edges.

Determine the equivalent resistance between two opposite corners of the cube.

## Theory

This is a symmetry problem. If current enters at one corner and leaves at the opposite corner, then by symmetry:

- the three vertices adjacent to the entry corner are at the same potential,
- the three vertices adjacent to the exit corner are also at the same potential.

Thus the cube can be reduced to a simpler equivalent network.

## Step-by-Step Solution

Let the opposite corners be $A$ and $B$.

### First group of three resistors from corner $A$

From $A$, current splits equally into the three edges leaving that corner. These three resistors are in parallel between node $A$ and the first equipotential layer.

Thus their equivalent resistance is

$$
R_{A} = \frac{R}{3}
$$

### Middle group of six resistors

Between the first equipotential layer and the second equipotential layer there are six resistors connecting corresponding vertices.

These six resistors are all in parallel between the two equipotential groups, so their equivalent resistance is

$$
R_{\text{mid}} = \frac{R}{6}
$$

### Final group of three resistors to corner $B$

Similarly, the last three resistors are in parallel:

$$
R_B = \frac{R}{3}
$$

### Total equivalent resistance

These three groups are in series:

$$
R_{\text{eq}} = \frac{R}{3} + \frac{R}{6} + \frac{R}{3}
$$

Use a common denominator:

$$
R_{\text{eq}} = \frac{2R}{6} + \frac{R}{6} + \frac{2R}{6}
$$

$$
R_{\text{eq}} = \frac{5R}{6}
$$

## Final Result

The equivalent resistance between opposite corners of the cube is

$$
R_{\text{eq}} = \frac{5R}{6}
$$

## Interpretation

The symmetry of the cube allows the current to distribute equally among equivalent branches. This reduces a complicated three-dimensional network to a simple series combination of three parallel groups.