# Section 2 – Mechanics II (Solutions)

# Task 01 – Gravitational Dependence

## Problem Statement

A simple pendulum has a period of $4\ \text{s}$ on Earth. What would its period be on the Moon, where the gravitational acceleration is about $\frac{1}{6}$ of Earth's?

What is the required length of a simple pendulum to have a period of exactly $1\ \text{s}$ on Earth?

## Theory

For small oscillations, the period of a simple pendulum is

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

This shows that

$$
T \propto \frac{1}{\sqrt{g}}
$$

for fixed length $L$, and

$$
L = \frac{gT^2}{4\pi^2}
$$

for a specified period $T$.

## Step-by-Step Solution

### Period on the Moon

Let $g_M = \frac{g_E}{6}$. For the same pendulum length,

$$
T_M = 2\pi \sqrt{\frac{L}{g_M}}
$$

and

$$
T_E = 2\pi \sqrt{\frac{L}{g_E}}
$$

Divide the two equations:

$$
\frac{T_M}{T_E} = \sqrt{\frac{g_E}{g_M}}
$$

Substitute $g_M = \frac{g_E}{6}$:

$$
\frac{T_M}{T_E} = \sqrt{\frac{g_E}{g_E/6}} = \sqrt{6}
$$

Therefore,

$$
T_M = T_E \sqrt{6} = 4\sqrt{6}\ \text{s}
$$

Numerically,

$$
T_M \approx 4(2.449) \approx 9.80\ \text{s}
$$

### Pendulum length for a period of $1$ s on Earth

Use

$$
L = \frac{gT^2}{4\pi^2}
$$

with $T=1\ \text{s}$ and $g=9.81\ \text{m/s}^2$:

$$
L = \frac{9.81 \cdot 1^2}{4\pi^2}
$$

$$
L \approx \frac{9.81}{39.478} \approx 0.2485\ \text{m}
$$

## Final Result

$$
T_M = 4\sqrt{6}\ \text{s} \approx 9.80\ \text{s}
$$

$$
L \approx 0.249\ \text{m}
$$

## Interpretation

The pendulum oscillates more slowly on the Moon because gravity is weaker. A pendulum with a period of $1$ s on Earth must be relatively short, about $25$ cm.

# Task 02 – Harmonic Motion

## Problem Statement

A $10$ kg mass is attached to a spring and oscillates according to

$$
x(t) = 0.2 \cos(10\pi t)
$$

where $x$ is measured in meters. Determine the spring constant $k$ and the total mechanical energy.

## Theory

The standard form of simple harmonic motion is

$$
x(t) = A \cos(\omega t + \phi)
$$

For a mass-spring system,

$$
\omega = \sqrt{\frac{k}{m}}
$$

so

$$
k = m\omega^2
$$

The total mechanical energy of the oscillator is

$$
E = \frac{1}{2}kA^2
$$

## Step-by-Step Solution

From

$$
x(t)=0.2\cos(10\pi t)
$$

identify:

$$
A = 0.2\ \text{m}, \quad \omega = 10\pi\ \text{rad/s}
$$

### Spring constant

Use

$$
k = m\omega^2
$$

Substitute $m=10\ \text{kg}$:

$$
k = 10(10\pi)^2
$$

$$
k = 10 \cdot 100\pi^2 = 1000\pi^2\ \text{N/m}
$$

Numerically,

$$
k \approx 1000(9.8696) \approx 9869.6\ \text{N/m}
$$

### Total mechanical energy

Use

$$
E = \frac{1}{2}kA^2
$$

Substitute $k = 1000\pi^2$ and $A=0.2$:

$$
E = \frac{1}{2}(1000\pi^2)(0.2)^2
$$

$$
E = \frac{1}{2}(1000\pi^2)(0.04) = 20\pi^2\ \text{J}
$$

Numerically,

$$
E \approx 20(9.8696) \approx 197.4\ \text{J}
$$

## Final Result

$$
k = 1000\pi^2\ \text{N/m} \approx 9.87\times 10^3\ \text{N/m}
$$

$$
E = 20\pi^2\ \text{J} \approx 197.4\ \text{J}
$$

## Interpretation

The large angular frequency implies a stiff spring. The total energy remains constant because ideal simple harmonic motion has no dissipation.

# Task 03 – Conservation of Energy in a Pendulum

## Problem Statement

A pendulum of length $1.0$ m is released from an initial angle of $15^\circ$. Find the speed of the bob at the bottom of the swing.

## Theory

Mechanical energy is conserved if friction and air resistance are neglected. The decrease in gravitational potential energy equals the increase in kinetic energy:

$$
mgh = \frac{1}{2}mv^2
$$

The vertical drop from angle $\theta$ to the bottom is

$$
h = L(1-\cos\theta)
$$

## Step-by-Step Solution

Given:

$$
L = 1.0\ \text{m}, \quad \theta = 15^\circ
$$

The vertical drop is

$$
h = 1.0(1-\cos 15^\circ)
$$

Using $\cos 15^\circ \approx 0.9659$:

$$
h \approx 1 - 0.9659 = 0.0341\ \text{m}
$$

Apply energy conservation:

$$
mgh = \frac{1}{2}mv^2
$$

Cancel $m$:

$$
gh = \frac{1}{2}v^2
$$

$$
v^2 = 2gh
$$

Substitute values:

$$
v = \sqrt{2(9.81)(0.0341)}
$$

$$
v \approx \sqrt{0.669} \approx 0.818\ \text{m/s}
$$

## Final Result

$$
v \approx 0.82\ \text{m/s}
$$

## Interpretation

The initial angle is small, so the bob descends only a short vertical distance. As a result, the bottom speed is well below $1\ \text{m/s}$.

# Task 04 – Energy and Momentum

## Problem Statement

A $0.5$ kg block slides down a frictionless track from a height of $3.0$ m. At the bottom, it collides and sticks to a $1.5$ kg block initially at rest. Find the speed of the combined mass immediately after the collision.

## Theory

Before the collision, the first block converts gravitational potential energy into kinetic energy:

$$
mgh = \frac{1}{2}mv^2
$$

During the sticking collision, linear momentum is conserved:

$$
m_1 v_1 + m_2 v_2 = (m_1+m_2)v_f
$$

## Step-by-Step Solution

### Speed before collision

For the $0.5$ kg block:

$$
mgh = \frac{1}{2}mv^2
$$

Cancel $m$:

$$
gh = \frac{1}{2}v^2
$$

$$
v = \sqrt{2gh}
$$

Substitute $g=9.81\ \text{m/s}^2$ and $h=3.0\ \text{m}$:

$$
v_1 = \sqrt{2(9.81)(3.0)} = \sqrt{58.86} \approx 7.67\ \text{m/s}
$$

### Inelastic collision

Given:

$$
m_1 = 0.5\ \text{kg}, \quad v_1 \approx 7.67\ \text{m/s}
$$

$$
m_2 = 1.5\ \text{kg}, \quad v_2 = 0
$$

Momentum conservation gives

$$
m_1v_1 = (m_1+m_2)v_f
$$

So

$$
v_f = \frac{m_1v_1}{m_1+m_2}
$$

$$
v_f = \frac{0.5(7.67)}{0.5+1.5}
$$

$$
v_f = \frac{3.835}{2.0} \approx 1.92\ \text{m/s}
$$

## Final Result

$$
v_f \approx 1.92\ \text{m/s}
$$

## Interpretation

The first block reaches the bottom quickly because the track is frictionless, but the sticking collision redistributes the momentum over a larger combined mass, greatly reducing the final speed.

# Task 05 – Inelastic Collision

## Problem Statement

A $70$ kg runner moving at $3\ \text{m/s}$ jumps onto a $140$ kg cart initially at rest. Find the final speed of the cart-runner system. Is kinetic energy conserved?

## Theory

For a perfectly inelastic collision, momentum is conserved:

$$
m_1v_1 + m_2v_2 = (m_1+m_2)v_f
$$

Kinetic energy is generally not conserved in such collisions because some mechanical energy is transformed into heat, sound, and internal energy.

## Step-by-Step Solution

Given:

$$
m_1 = 70\ \text{kg}, \quad v_1 = 3\ \text{m/s}
$$

$$
m_2 = 140\ \text{kg}, \quad v_2 = 0
$$

Final speed:

$$
v_f = \frac{m_1v_1 + m_2v_2}{m_1+m_2}
$$

$$
v_f = \frac{70\cdot 3 + 140\cdot 0}{70+140}
$$

$$
v_f = \frac{210}{210} = 1\ \text{m/s}
$$

### Check kinetic energy

Initial kinetic energy:

$$
K_i = \frac{1}{2}m_1v_1^2 = \frac{1}{2}(70)(3^2)
$$

$$
K_i = 35\cdot 9 = 315\ \text{J}
$$

Final kinetic energy:

$$
K_f = \frac{1}{2}(m_1+m_2)v_f^2
$$

$$
K_f = \frac{1}{2}(210)(1^2) = 105\ \text{J}
$$

Since

$$
K_f \ne K_i
$$

kinetic energy is not conserved.

## Final Result

$$
v_f = 1.0\ \text{m/s}
$$

$$
K_i = 315\ \text{J}, \quad K_f = 105\ \text{J}
$$

$$
\text{Kinetic energy is not conserved.}
$$

## Interpretation

Momentum is conserved because the collision time is short and external horizontal forces are negligible. Kinetic energy decreases because the runner and cart stick together, making the collision inelastic.

# Task 06 – Energy Dissipation in Bouncing Motion

## Problem Statement

A tennis ball is dropped from a height of $2.0$ m. After each bounce, it loses $30\%$ of its mechanical energy. Find the height after the second bounce.

## Theory

Mechanical energy near the top of each bounce is purely gravitational potential energy:

$$
E = mgh
$$

If the ball loses $30\%$ of its energy in each bounce, then it retains $70\%$:

$$
E_{\text{after}} = 0.7 E_{\text{before}}
$$

Since $E \propto h$, the rebound height is multiplied by the same factor.

## Step-by-Step Solution

Initial height:

$$
h_0 = 2.0\ \text{m}
$$

After the first bounce:

$$
h_1 = 0.7 h_0 = 0.7(2.0) = 1.4\ \text{m}
$$

After the second bounce:

$$
h_2 = 0.7 h_1 = 0.7(1.4)
$$

$$
h_2 = 0.98\ \text{m}
$$

## Final Result

$$
h_2 = 0.98\ \text{m}
$$

## Interpretation

Because the same fraction of energy is lost at each impact, the bounce heights form a geometric sequence.

# Task 07 – Dynamics with Friction

## Problem Statement

A $5$ kg block is placed on a $10$ kg block. A horizontal force of $45$ N is applied to the $10$ kg block, and the $5$ kg block is tied to the wall. The coefficient of kinetic friction between all moving surfaces is $0.2$. Find the acceleration of the $10$ kg block.

## Theory

The $10$ kg block experiences:

- the applied force to the right,
- kinetic friction from the floor to the left,
- kinetic friction from the upper $5$ kg block to the left.

Kinetic friction magnitude is

$$
f_k = \mu_k N
$$

## Step-by-Step Solution

Let the $10$ kg block move to the right.

### Friction between the $10$ kg block and the floor

The floor supports both masses, so the normal force from the floor is

$$
N_{\text{floor}} = (10+5)g = 15g
$$

Thus the kinetic friction from the floor is

$$
f_{\text{floor}} = \mu_k N_{\text{floor}} = 0.2(15g)
$$

$$
f_{\text{floor}} = 3g \approx 29.43\ \text{N}
$$

### Friction between the two blocks

The $5$ kg block is tied to the wall, so the lower block slides under it. The normal force between the blocks is

$$
N_{\text{top}} = 5g
$$

Hence

$$
f_{\text{top}} = \mu_k N_{\text{top}} = 0.2(5g)
$$

$$
f_{\text{top}} = g \approx 9.81\ \text{N}
$$

This friction acts to the left on the $10$ kg block.

### Net force on the $10$ kg block

Net horizontal force:

$$
F_{\text{net}} = 45 - f_{\text{floor}} - f_{\text{top}}
$$

$$
F_{\text{net}} = 45 - 29.43 - 9.81 = 5.76\ \text{N}
$$

Apply Newton’s second law to the $10$ kg block:

$$
F_{\text{net}} = ma
$$

$$
a = \frac{5.76}{10} = 0.576\ \text{m/s}^2
$$

## Final Result

$$
a \approx 0.576\ \text{m/s}^2
$$

## Interpretation

Most of the applied force is spent overcoming friction with the floor and the upper block. Only a small residual force accelerates the $10$ kg block.

# Task 08 – Work of a Variable Force

## Problem Statement

Given the one-dimensional force

$$
F(x) = -kx
$$

- Write the equation of motion and solve it.
- Calculate the work done during the displacement from $0$ to $x_0$.
- Interpret the result as potential energy.
- Verify the relationship $F = -\frac{dU}{dx}$.
- Draw the graphs of $F(x)$ and $U(x)$.

## Theory

Newton’s second law gives

$$
m\frac{d^2x}{dt^2} = F(x)
$$

For the restoring force $F(x)=-kx$, the equation becomes

$$
m\frac{d^2x}{dt^2} + kx = 0
$$

This is the equation of simple harmonic motion.

The work done by a position-dependent force from $x=a$ to $x=b$ is

$$
W_{a\to b} = \int_a^b F(x)\,dx
$$

Potential energy satisfies

$$
F(x) = -\frac{dU}{dx}
$$

## Step-by-Step Solution

### Equation of motion

Start from Newton’s law:

$$
m\ddot{x} = -kx
$$

or

$$
\ddot{x} + \frac{k}{m}x = 0
$$

Define

$$
\omega = \sqrt{\frac{k}{m}}
$$

Then

$$
\ddot{x} + \omega^2 x = 0
$$

The general solution is

$$
x(t) = A\cos(\omega t) + B\sin(\omega t)
$$

Equivalently,

$$
x(t) = C\cos(\omega t + \phi)
$$

### Work done from $0$ to $x_0$

Compute

$$
W_{0\to x_0} = \int_0^{x_0} (-kx)\,dx
$$

$$
W_{0\to x_0} = -k \int_0^{x_0} x\,dx
$$

$$
W_{0\to x_0} = -k \left[\frac{x^2}{2}\right]_0^{x_0}
$$

$$
W_{0\to x_0} = -\frac{1}{2}k x_0^2
$$

### Interpretation as potential energy

For a conservative force,

$$
W_{0\to x_0} = -(U(x_0)-U(0))
$$

Choose the zero of potential energy at $x=0$:

$$
U(0)=0
$$

Then

$$
U(x_0) = \frac{1}{2}k x_0^2
$$

Therefore the potential energy function is

$$
U(x)=\frac{1}{2}kx^2
$$

### Verify $F=-\frac{dU}{dx}$

Differentiate:

$$
\frac{dU}{dx} = \frac{d}{dx}\left(\frac{1}{2}kx^2\right) = kx
$$

Hence

$$
-\frac{dU}{dx} = -kx = F(x)
$$

The relationship is verified.

### Graphs of $F(x)$ and $U(x)$

The force

$$
F(x)=-kx
$$

is a straight line through the origin with negative slope.

The potential energy

$$
U(x)=\frac{1}{2}kx^2
$$

is an upward-opening parabola with minimum at $x=0$.

## Final Result

$$
m\ddot{x}+kx=0
$$

$$
x(t)=A\cos\left(\sqrt{\frac{k}{m}}\,t\right)+B\sin\left(\sqrt{\frac{k}{m}}\,t\right)
$$

$$
W_{0\to x_0}=-\frac{1}{2}k x_0^2
$$

$$
U(x)=\frac{1}{2}kx^2
$$

$$
F(x)=-\frac{dU}{dx}
$$

## Interpretation

This is the standard model of an ideal spring. The restoring force always points toward equilibrium, while the potential energy grows quadratically with displacement from equilibrium.

# Task 09 – Vertical Throw with Drag

## Problem Statement

The equation of motion is

$$
m\frac{dv}{dt} = -mg - kv
$$

with initial conditions

$$
v(0)=v_0, \quad x(0)=10
$$

- Solve the equation analytically.
- Determine the maximum height.
- Compare with the case without drag.
- Perform a numerical simulation using HTML or Python.

## Theory

This is a first-order linear differential equation for $v(t)$:

$$
\frac{dv}{dt} + \frac{k}{m}v = -g
$$

Once $v(t)$ is known, position follows from

$$
\frac{dx}{dt}=v(t)
$$

The maximum height occurs when

$$
v(t_{\max})=0
$$

## Step-by-Step Solution

### Analytical solution for velocity

Write the equation as

$$
\frac{dv}{dt} + \frac{k}{m}v = -g
$$

A constant particular solution is obtained by setting $\frac{dv}{dt}=0$:

$$
\frac{k}{m}v_p = -g
$$

$$
v_p = -\frac{mg}{k}
$$

The homogeneous solution satisfies

$$
\frac{dv_h}{dt} + \frac{k}{m}v_h = 0
$$

so

$$
v_h = Ce^{-kt/m}
$$

Thus

$$
v(t) = Ce^{-kt/m} - \frac{mg}{k}
$$

Use $v(0)=v_0$:

$$
v_0 = C - \frac{mg}{k}
$$

$$
C = v_0 + \frac{mg}{k}
$$

Therefore

$$
v(t) = \left(v_0 + \frac{mg}{k}\right)e^{-kt/m} - \frac{mg}{k}
$$

### Analytical solution for position

Integrate $x'(t)=v(t)$:

$$
x(t)=10+\int_0^t \left[\left(v_0+\frac{mg}{k}\right)e^{-k\tau/m}-\frac{mg}{k}\right] d\tau
$$

Compute the integral:

$$
\int_0^t e^{-k\tau/m}\,d\tau = \frac{m}{k}\left(1-e^{-kt/m}\right)
$$

Thus

$$
x(t)=10+\left(v_0+\frac{mg}{k}\right)\frac{m}{k}\left(1-e^{-kt/m}\right)-\frac{mg}{k}t
$$

### Maximum height

At the top, $v(t_{\max})=0$:

$$
\left(v_0 + \frac{mg}{k}\right)e^{-kt_{\max}/m} - \frac{mg}{k}=0
$$

So

$$
e^{-kt_{\max}/m} = \frac{mg/k}{v_0+mg/k}
$$

$$
e^{-kt_{\max}/m} = \frac{mg}{kv_0+mg}
$$

Take the natural logarithm:

$$
-\frac{k}{m}t_{\max} = \ln\left(\frac{mg}{kv_0+mg}\right)
$$

Hence

$$
t_{\max} = \frac{m}{k}\ln\left(\frac{kv_0+mg}{mg}\right)
$$

Now substitute into $x(t)$:

$$
x_{\max}=10+\left(v_0+\frac{mg}{k}\right)\frac{m}{k}\left(1-e^{-kt_{\max}/m}\right)-\frac{mg}{k}t_{\max}
$$

Use

$$
e^{-kt_{\max}/m} = \frac{mg}{kv_0+mg}
$$

Then

$$
1-e^{-kt_{\max}/m} = 1-\frac{mg}{kv_0+mg} = \frac{kv_0}{kv_0+mg}
$$

Also,

$$
v_0+\frac{mg}{k} = \frac{kv_0+mg}{k}
$$

Therefore

$$
\left(v_0+\frac{mg}{k}\right)\frac{m}{k}\left(1-e^{-kt_{\max}/m}\right)
=
\frac{kv_0+mg}{k}\cdot\frac{m}{k}\cdot\frac{kv_0}{kv_0+mg}
=
\frac{mv_0}{k}
$$

So

$$
x_{\max} = 10 + \frac{mv_0}{k} - \frac{mg}{k}t_{\max}
$$

Finally,

$$
x_{\max} = 10 + \frac{mv_0}{k} - \frac{m^2g}{k^2}\ln\left(\frac{kv_0+mg}{mg}\right)
$$

### Comparison with no drag

Without drag, the equation becomes

$$
m\frac{dv}{dt} = -mg
$$

so

$$
v(t)=v_0-gt
$$

and

$$
x(t)=10+v_0t-\frac{1}{2}gt^2
$$

The maximum height occurs at

$$
t_{\max}^{(0)} = \frac{v_0}{g}
$$

and is

$$
x_{\max}^{(0)} = 10 + \frac{v_0^2}{2g}
$$

Because drag opposes the upward motion, the dragged trajectory reaches a smaller maximum height than the ideal one.

### Python simulation

```python
import numpy as np
import matplotlib.pyplot as plt

# Example parameters
m = 0.5
k = 0.2
g = 9.81
v0 = 20.0
x0 = 10.0

t = np.linspace(0, 5, 1000)

v = (v0 + m*g/k) * np.exp(-k*t/m) - m*g/k
x = x0 + (v0 + m*g/k) * (m/k) * (1 - np.exp(-k*t/m)) - (m*g/k) * t

plt.figure()
plt.plot(t, x)
plt.xlabel("t [s]")
plt.ylabel("x(t) [m]")
plt.title("Vertical motion with linear drag")
plt.grid(True)
plt.show()