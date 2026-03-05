# Section 1 – Mechanics I (Solutions)

# Task 01 – Projectile Motion

## Problem Statement

A projectile is fired from the ground with initial speed $v_0 = 100\ \text{m/s}$ at an angle $\theta = 37^\circ$ above the horizontal. Assume no air resistance.

- Derive the differential equations of motion in the horizontal and vertical directions.
- Determine the time of flight.
- Determine the maximum height.
- Determine the range.

## Theory

With no air resistance, the only force is gravity:

$$
\vec{F} = m\vec{g}, \quad \vec{g} = (0, -g)
$$

Newton’s second law gives constant acceleration:

$$
\vec{a} = \frac{d\vec{v}}{dt} = (0,-g)
$$

Component form:

$$
\frac{dv_x}{dt} = 0, \quad \frac{dv_y}{dt} = -g
$$

Velocity is the time derivative of position:

$$
\frac{dx}{dt} = v_x, \quad \frac{dy}{dt} = v_y
$$

Initial velocity components for launch angle $\theta$:

$$
v_x(0) = v_0 \cos\theta, \quad v_y(0) = v_0 \sin\theta
$$

## Step-by-Step Solution

### Differential equations of motion

From constant acceleration:

$$
\frac{dv_x}{dt} = 0
$$

$$
\frac{dv_y}{dt} = -g
$$

Together with kinematics:

$$
\frac{dx}{dt} = v_x, \quad \frac{dy}{dt} = v_y
$$

These four first-order differential equations define the motion.

### Solve for velocity components

Integrate $\frac{dv_x}{dt}=0$:

$$
v_x(t) = v_0\cos\theta
$$

Integrate $\frac{dv_y}{dt}=-g$:

$$
v_y(t) = v_0\sin\theta - gt
$$

### Solve for position

Assuming launch from the origin:

$$
x(0)=0, \quad y(0)=0
$$

Integrate $x'(t)=v_x(t)$:

$$
x(t) = v_0\cos\theta \, t
$$

Integrate $y'(t)=v_y(t)$:

$$
y(t) = v_0\sin\theta \, t - \frac{1}{2}gt^2
$$

### Time of flight

The projectile lands when it returns to $y=0$ with $t>0$:

$$
0 = v_0\sin\theta \, t - \frac{1}{2}gt^2
$$

Factor out $t$:

$$
0 = t\left(v_0\sin\theta - \frac{1}{2}gt\right)
$$

Nonzero solution:

$$
t_f = \frac{2v_0\sin\theta}{g}
$$

With $v_0=100\ \text{m/s}$, $\theta=37^\circ$, $g=9.81\ \text{m/s}^2$:

$$
t_f = \frac{2(100)\sin 37^\circ}{9.81} \approx 12.27\ \text{s}
$$

### Maximum height

Maximum height occurs when vertical velocity becomes zero:

$$
v_y(t)=0 \Rightarrow v_0\sin\theta - gt = 0
$$

So the time to peak is:

$$
t_{\max} = \frac{v_0\sin\theta}{g}
$$

Height at that time:

$$
y_{\max} = v_0\sin\theta \, t_{\max} - \frac{1}{2}g t_{\max}^2
$$

Substitute $t_{\max} = \frac{v_0\sin\theta}{g}$:

$$
y_{\max} = \frac{v_0^2\sin^2\theta}{g} - \frac{1}{2}g\frac{v_0^2\sin^2\theta}{g^2}
$$

$$
y_{\max} = \frac{v_0^2\sin^2\theta}{2g}
$$

Numerically:

$$
y_{\max} = \frac{100^2\sin^2 37^\circ}{2(9.81)} \approx 184.60\ \text{m}
$$

### Range

The horizontal range is $R=x(t_f)$:

$$
R = v_0\cos\theta \, t_f
$$

Substitute $t_f=\frac{2v_0\sin\theta}{g}$:

$$
R = v_0\cos\theta \cdot \frac{2v_0\sin\theta}{g}
$$

Use $\sin(2\theta)=2\sin\theta\cos\theta$:

$$
R = \frac{v_0^2\sin(2\theta)}{g}
$$

Numerically:

$$
R = \frac{100^2\sin(74^\circ)}{9.81} \approx 979.88\ \text{m}
$$

## Final Result

$$
\frac{dv_x}{dt} = 0,\quad \frac{dv_y}{dt} = -g,\quad \frac{dx}{dt}=v_x,\quad \frac{dy}{dt}=v_y
$$

$$
t_f = \frac{2v_0\sin\theta}{g} \approx 12.27\ \text{s}
$$

$$
y_{\max} = \frac{v_0^2\sin^2\theta}{2g} \approx 184.60\ \text{m}
$$

$$
R = \frac{v_0^2\sin(2\theta)}{g} \approx 979.88\ \text{m}
$$

## Interpretation

- Horizontal motion is uniform because $a_x=0$.
- Vertical motion is uniformly accelerated because $a_y=-g$.
- The range depends on $\sin(2\theta)$, which controls the tradeoff between horizontal speed and time in the air.

# Task 02 – Range Optimization

## Problem Statement

For projectile motion, show analytically that the maximum range

$$
R(\theta)=\frac{v_0^2 \sin(2\theta)}{g}
$$

for a given initial velocity is achieved at $\theta=45^\circ$.

## Theory

For fixed $v_0$ and $g$, maximizing $R(\theta)$ is equivalent to maximizing $\sin(2\theta)$.

The sine function satisfies:

$$
-1 \le \sin(\phi) \le 1
$$

with maximum value $1$ achieved at $\phi = 90^\circ + 360^\circ k$.

## Step-by-Step Solution

Since

$$
R(\theta)=\frac{v_0^2}{g}\sin(2\theta)
$$

and $\frac{v_0^2}{g}>0$, the maximum of $R(\theta)$ occurs when $\sin(2\theta)$ is maximized.

The maximum value is:

$$
\sin(2\theta)=1
$$

This occurs when:

$$
2\theta = 90^\circ + 360^\circ k
$$

Within the physically relevant range $0^\circ \le \theta \le 90^\circ$, the only solution is:

$$
2\theta = 90^\circ \Rightarrow \theta = 45^\circ
$$

## Final Result

$$
\theta_{\max R} = 45^\circ
$$

## Interpretation

A $45^\circ$ launch angle balances horizontal speed and airtime in a way that maximizes horizontal displacement for level ground.

# Task 03 – Path Intersection

## Problem Statement

Alice moves along

$$
A(t) = (2+t,\ 8-3t)
$$

Bob moves along

$$
B(t) = (2t-1,\ 2t+2)
$$

Determine if they collide. If not, determine the minimum distance between them and when it occurs.

## Theory

A collision requires same position at the same time:

$$
A(t)=B(t)
$$

If no solution exists, define relative position:

$$
\Delta(t)=A(t)-B(t)
$$

Distance:

$$
d(t)=|\Delta(t)|
$$

Minimizing $d(t)$ is equivalent to minimizing $d(t)^2$ because the square root is monotone increasing:

$$
s(t)=d(t)^2
$$

## Step-by-Step Solution

### Check for collision

Set coordinates equal:

$$
2+t = 2t-1
$$

This gives:

$$
t = 3
$$

Check the $y$-coordinate at $t=3$:

$$
8-3(3) = 8-9 = -1
$$

$$
2(3)+2 = 8
$$

Since $-1 \ne 8$, there is no collision.

### Minimum distance

Compute relative position:

$$
\Delta(t) = A(t)-B(t) = \left((2+t)-(2t-1),\ (8-3t)-(2t+2)\right)
$$

$$
\Delta(t) = (3-t,\ 6-5t)
$$

Distance squared:

$$
s(t) = (3-t)^2 + (6-5t)^2
$$

Expand:

$$
s(t) = (t^2 - 6t + 9) + (25t^2 - 60t + 36)
$$

$$
s(t) = 26t^2 - 66t + 45
$$

Differentiate and set to zero:

$$
s'(t) = 52t - 66
$$

$$
52t - 66 = 0 \Rightarrow t = \frac{66}{52} = \frac{33}{26}
$$

Minimum distance:

$$
d_{\min} = \sqrt{s\left(\frac{33}{26}\right)}
$$

Evaluate $s\left(\frac{33}{26}\right)$:

$$
s\left(\frac{33}{26}\right) \approx 3.11538
$$

So

$$
d_{\min} \approx \sqrt{3.11538} \approx 1.77
$$

Optional: positions at this time:

$$
A\left(\frac{33}{26}\right) = \left(2+\frac{33}{26},\ 8-3\frac{33}{26}\right) \approx (3.27,\ 4.19)
$$

$$
B\left(\frac{33}{26}\right) = \left(2\frac{33}{26}-1,\ 2\frac{33}{26}+2\right) \approx (1.54,\ 4.54)
$$

## Final Result

$$
\text{No collision occurs.}
$$

$$
t_{\min} = \frac{33}{26}\ \text{s} \approx 1.27\ \text{s}, \quad d_{\min} \approx 1.77
$$

## Interpretation

The paths in the plane do not match at any common time parameter. The closest approach occurs at $t=\frac{33}{26}$, where the relative displacement is smallest.

# Task 04 – Vector Calculus

## Problem Statement

The position is

$$
\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}
$$

Find velocity and acceleration vectors as functions of time.

## Theory

Velocity is the time derivative of position:

$$
\vec{v}(t)=\frac{d\vec{r}}{dt}
$$

Acceleration is the time derivative of velocity:

$$
\vec{a}(t)=\frac{d\vec{v}}{dt}=\frac{d^2\vec{r}}{dt^2}
$$

## Step-by-Step Solution

Differentiate $\vec{r}(t)$:

$$
\vec{v}(t)=\frac{d}{dt}\left(3t^2\right)\hat{i} + \frac{d}{dt}\left(5t-8t^2\right)\hat{j}
$$

$$
\vec{v}(t)= (6t)\hat{i} + (5-16t)\hat{j}
$$

Differentiate again:

$$
\vec{a}(t)=\frac{d}{dt}(6t)\hat{i} + \frac{d}{dt}(5-16t)\hat{j}
$$

$$
\vec{a}(t)= 6\hat{i} - 16\hat{j}
$$

## Final Result

$$
\vec{v}(t)= (6t)\hat{i} + (5-16t)\hat{j}
$$

$$
\vec{a}(t)= 6\hat{i} - 16\hat{j}
$$

## Interpretation

Acceleration is constant, so the motion is uniformly accelerated in the plane with independent components.

# Task 05 – Relative Velocity

## Problem Statement

A river flows east at $2\ \text{m/s}$. A boat travels at $5\ \text{m/s}$ relative to still water and wants to go directly north across the river.

- In what direction (angle) should it head?
- How long will it take to cross a $200$ m wide river?

## Theory

Let $\vec{v}_{bw}$ be the boat velocity relative to water and $\vec{v}_{wg}$ the water velocity relative to ground. Then:

$$
\vec{v}_{bg} = \vec{v}_{bw} + \vec{v}_{wg}
$$

To go directly north relative to ground, the east-west component of $\vec{v}_{bg}$ must be zero.

## Step-by-Step Solution

Take east as $+x$, north as $+y$.

Given:

$$
\vec{v}_{wg} = (2,0)\ \text{m/s}
$$

Let:

$$
\vec{v}_{bw} = (v_x, v_y), \quad \sqrt{v_x^2+v_y^2}=5
$$

Condition for no drift (directly north):

$$
v_{bg,x} = v_x + 2 = 0 \Rightarrow v_x = -2
$$

Then $v_y$ follows from the boat speed in still water:

$$
v_y = \sqrt{5^2 - (-2)^2} = \sqrt{25-4} = \sqrt{21}
$$

So ground northward speed is:

$$
v_{bg,y} = \sqrt{21}\ \text{m/s}
$$

Heading angle relative to north (turning toward west) satisfies:

$$
\tan\alpha = \frac{|v_x|}{v_y} = \frac{2}{\sqrt{21}}
$$

So

$$
\alpha = \arctan\left(\frac{2}{\sqrt{21}}\right) \approx 23.6^\circ
$$

Crossing time for width $W=200\ \text{m}$:

$$
t = \frac{W}{v_{bg,y}} = \frac{200}{\sqrt{21}} \approx 43.6\ \text{s}
$$

## Final Result

$$
\text{Head } \alpha \approx 23.6^\circ \text{ west of north.}
$$

$$
t \approx 43.6\ \text{s}
$$

## Interpretation

The boat aims upstream so that the river current cancels its eastward drift, leaving purely northward motion relative to the ground.

# Task 06 – Variable Velocity

## Problem Statement

An object's velocity is

$$
v(t) = t^2 + 2t - 5
$$

If $x(0)=4$, find its position and acceleration at $t=3$.

## Theory

Velocity is the derivative of position:

$$
v(t) = \frac{dx}{dt}
$$

Acceleration is the derivative of velocity:

$$
a(t) = \frac{dv}{dt}
$$

Position from velocity uses a definite integral:

$$
x(t) = x(0) + \int_0^t v(\tau)\,d\tau
$$

## Step-by-Step Solution

### Acceleration

Differentiate:

$$
a(t) = \frac{d}{dt}(t^2+2t-5) = 2t+2
$$

At $t=3$:

$$
a(3) = 2(3)+2 = 8
$$

### Position

Integrate velocity from $0$ to $t$:

$$
x(t) = 4 + \int_0^t (\tau^2 + 2\tau - 5)\,d\tau
$$

Compute antiderivative:

$$
\int (\tau^2 + 2\tau - 5)\,d\tau = \frac{\tau^3}{3} + \tau^2 - 5\tau
$$

Evaluate:

$$
x(t) = 4 + \left(\frac{t^3}{3} + t^2 - 5t\right) - \left(\frac{0^3}{3} + 0^2 - 5\cdot 0\right)
$$

So:

$$
x(t)=4+\frac{t^3}{3}+t^2-5t
$$

At $t=3$:

$$
x(3)=4+\frac{27}{3}+9-15 = 4+9+9-15 = 7
$$

## Final Result

$$
x(3)=7, \quad a(3)=8
$$

## Interpretation

The acceleration increases linearly with time, and the position follows a cubic polynomial because the velocity is quadratic.

# Task 07 – Elimination of Time and Acceleration Interpretation

## Problem Statement

Given

$$
x(t)=2t^2, \qquad y(t)=3t^3
$$

- Eliminate the parameter $t$.
- Draw the trajectory.
- Calculate $\vec v(t)$, $|\vec v(t)|$, $\vec a(t)$ and $|\vec a(t)|$.
- Determine whether the acceleration is constant.

## Theory

For a planar parametric curve $(x(t),y(t))$:

$$
\vec{r}(t) = (x(t),y(t))
$$

$$
\vec{v}(t) = \frac{d\vec{r}}{dt} = \left(\frac{dx}{dt},\frac{dy}{dt}\right)
$$

$$
\vec{a}(t) = \frac{d\vec{v}}{dt} = \left(\frac{d^2x}{dt^2},\frac{d^2y}{dt^2}\right)
$$

Speed and acceleration magnitude:

$$
|\vec{v}(t)|=\sqrt{v_x^2+v_y^2}, \quad |\vec{a}(t)|=\sqrt{a_x^2+a_y^2}
$$

## Step-by-Step Solution

### Eliminate $t$

From $x(t)=2t^2$:

$$
t^2 = \frac{x}{2}
$$

For $t \ge 0$ (typical forward-time motion):

$$
t = \sqrt{\frac{x}{2}}
$$

Substitute into $y(t)=3t^3$:

$$
y = 3\left(\sqrt{\frac{x}{2}}\right)^3
$$

$$
y = 3\left(\frac{x}{2}\right)^{3/2}
$$

So the trajectory is:

$$
y = 3\left(\frac{x}{2}\right)^{3/2}
$$

### Trajectory sketch description

- For $t\ge 0$, $x=2t^2 \ge 0$ and $y=3t^3 \ge 0$, so the curve lies in the first quadrant.
- The curve starts at the origin and rises with increasing slope as $x$ increases, since $y \propto x^{3/2}$.

### Velocity

Differentiate:

$$
v_x(t)=\frac{dx}{dt}=4t
$$

$$
v_y(t)=\frac{dy}{dt}=9t^2
$$

Thus:

$$
\vec{v}(t) = (4t,\ 9t^2)
$$

Speed:

$$
|\vec{v}(t)|=\sqrt{(4t)^2 + (9t^2)^2}
$$

$$
|\vec{v}(t)|=\sqrt{16t^2 + 81t^4}
$$

For $t\ge 0$:

$$
|\vec{v}(t)|= t\sqrt{16+81t^2}
$$

### Acceleration

Differentiate velocity:

$$
a_x(t)=\frac{d}{dt}(4t)=4
$$

$$
a_y(t)=\frac{d}{dt}(9t^2)=18t
$$

So:

$$
\vec{a}(t)=(4,\ 18t)
$$

Magnitude:

$$
|\vec{a}(t)|=\sqrt{4^2+(18t)^2}=\sqrt{16+324t^2}
$$

$$
|\vec{a}(t)|=2\sqrt{4+81t^2}
$$

### Is acceleration constant?

The acceleration vector is:

$$
\vec{a}(t)=(4,\ 18t)
$$

It depends on $t$ through its $y$-component, so it is not constant.

## Final Result

$$
y = 3\left(\frac{x}{2}\right)^{3/2}
$$

$$
\vec{v}(t)=(4t,\ 9t^2), \quad |\vec{v}(t)|=\sqrt{16t^2+81t^4}
$$

$$
\vec{a}(t)=(4,\ 18t), \quad |\vec{a}(t)|=\sqrt{16+324t^2}
$$

$$
\text{Acceleration is not constant.}
$$

## Interpretation

The motion starts from rest at $t=0$ because $\vec{v}(0)=(0,0)$. The increasing $y$-component of acceleration produces a rapidly increasing vertical speed.

# Task 08 – Circular Motion: Centripetal Acceleration at the Equator

## Problem Statement

Calculate the centripetal acceleration of a person standing on Earth’s equator. Earth’s radius is approximately $R=6378\ \text{km}$.

## Theory

For uniform circular motion, centripetal acceleration is:

$$
a_c = \omega^2 R
$$

Angular speed $\omega$ relates to period $T$ by:

$$
\omega = \frac{2\pi}{T}
$$

Using $T \approx 24\ \text{h} = 86400\ \text{s}$ gives an acceptable estimate.

## Step-by-Step Solution

Convert radius:

$$
R = 6378\ \text{km} = 6.378\times 10^6\ \text{m}
$$

Compute angular speed:

$$
\omega = \frac{2\pi}{86400}\ \text{rad/s}
$$

Centripetal acceleration:

$$
a_c = \omega^2 R = \left(\frac{2\pi}{86400}\right)^2 (6.378\times 10^6)
$$

Numerically:

$$
a_c \approx 3.37\times 10^{-2}\ \text{m/s}^2
$$

## Final Result

$$
a_c \approx 0.034\ \text{m/s}^2
$$

## Interpretation

This is much smaller than $g \approx 9.81\ \text{m/s}^2$, so Earth’s rotation produces only a small reduction in effective weight at the equator.

# Task 09 – Momentum Comparison

## Problem Statement

Which has greater momentum:

- a $2$-gram fly flying at $10\ \text{m/s}$
- a $60$-gram tennis ball moving at $1\ \text{m/s}$

## Theory

Linear momentum magnitude is:

$$
p = mv
$$

## Step-by-Step Solution

Convert masses to kilograms:

$$
m_f = 2\ \text{g} = 0.002\ \text{kg}
$$

$$
m_b = 60\ \text{g} = 0.060\ \text{kg}
$$

Fly momentum:

$$
p_f = (0.002)(10) = 0.020\ \text{kg}\cdot\text{m/s}
$$

Ball momentum:

$$
p_b = (0.060)(1) = 0.060\ \text{kg}\cdot\text{m/s}
$$

## Final Result

$$
p_b > p_f
$$

## Interpretation

Even though the fly moves faster, the tennis ball’s much larger mass dominates, giving it greater momentum.

# Task 10 – Kinematics in 3D

## Problem Statement

Point $M$ moves as:

$$
\vec{r}(t) = (a \cos(\omega t),\ b \sin(\omega t),\ bt)
$$

where $a,b,\omega$ are positive constants.

a) Find the equation of the point's trajectory.

b) Compute the path length from $t=0$ to $t=t_0$.

c) Draw the trajectory using Python or interactive HTML. Discuss special cases.

## Theory

The trajectory is the set of points traced by $\vec{r}(t)$ in space.

Arc length for a parametric curve is:

$$
L = \int_{0}^{t_0} \left|\frac{d\vec{r}}{dt}\right| dt
$$

with speed:

$$
\left|\frac{d\vec{r}}{dt}\right| = \sqrt{\left(\frac{dx}{dt}\right)^2+\left(\frac{dy}{dt}\right)^2+\left(\frac{dz}{dt}\right)^2}
$$

## Step-by-Step Solution

### a) Trajectory equation

Let:

$$
x(t)=a\cos(\omega t), \quad y(t)=b\sin(\omega t), \quad z(t)=bt
$$

Eliminate $t$ from $x$ and $y$:

$$
\frac{x}{a} = \cos(\omega t), \quad \frac{y}{b} = \sin(\omega t)
$$

Square and add:

$$
\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = \cos^2(\omega t) + \sin^2(\omega t) = 1
$$

This shows the point lies on an elliptical cylinder.

Using $z=bt$:

$$
t=\frac{z}{b}
$$

Substitute into $x$ and $y$:

$$
x = a\cos\left(\frac{\omega}{b}z\right), \quad y = b\sin\left(\frac{\omega}{b}z\right)
$$

This is an elliptical helix wrapped around the cylinder.

### b) Path length from $0$ to $t_0$

Differentiate:

$$
\vec{r}\,'(t) = \left(-a\omega\sin(\omega t),\ b\omega\cos(\omega t),\ b\right)
$$

Speed:

$$
|\vec{r}\,'(t)| = \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2}
$$

So the arc length is:

$$
L = \int_0^{t_0} \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2}\ dt
$$

A useful rearrangement:

$$
a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t)
=
b^2\omega^2 + \omega^2(a^2-b^2)\sin^2(\omega t)
$$

Thus:

$$
L = \int_0^{t_0} \sqrt{b^2(1+\omega^2) + \omega^2(a^2-b^2)\sin^2(\omega t)}\ dt
$$

Substitute $u=\omega t$, $dt=du/\omega$:

$$
L = \frac{1}{\omega}\int_0^{\omega t_0} \sqrt{b^2(1+\omega^2) + \omega^2(a^2-b^2)\sin^2 u}\ du
$$

This integral is generally expressed in terms of an elliptic integral of the second kind unless special parameter choices make the speed constant.

### c) Python plot and special cases

A minimal Python script (Matplotlib) for plotting the trajectory:

```python
import numpy as np
import matplotlib.pyplot as plt

# Parameters (example values)
a = 2.0
b = 1.0
omega = 3.0
t0 = 4.0

# Sampling
t = np.linspace(0, t0, 2000)

x = a * np.cos(omega * t)
y = b * np.sin(omega * t)
z = b * t

fig = plt.figure()
ax = fig.add_subplot(111, projection="3d")
ax.plot(x, y, z)

ax.set_xlabel("x")
ax.set_ylabel("y")
ax.set_zlabel("z")
ax.set_title("Trajectory: (a cos(ωt), b sin(ωt), bt)")

plt.show()
```