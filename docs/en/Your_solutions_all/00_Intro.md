# Section 0 – Mathematical Foundations (Solutions)

# Task 01 – Vector Algebra

## Problem Statement

Given two vectors in 3D space

$$
\vec{a} = [2, 1, -3], \quad \vec{b} = [4, -2, 1]
$$

Calculate:

a) The magnitude of each vector.

b) The dot product $\vec{a} \cdot \vec{b}$.

c) The cross product $\vec{a} \times \vec{b}$.

d) The angle between vectors $\vec{a}$ and $\vec{b}$.

## Theory

For a vector $\vec{v} = [v_x, v_y, v_z]$:

- Magnitude:

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}
$$

- Dot product:

$$
\vec{a}\cdot\vec{b} = a_x b_x + a_y b_y + a_z b_z
$$

- Cross product:

$$
\vec{a}\times\vec{b} =
\begin{pmatrix}
a_y b_z - a_z b_y \\
a_z b_x - a_x b_z \\
a_x b_y - a_y b_x
\end{pmatrix}
$$

- Angle between vectors (from the dot product identity):

$$
\vec{a}\cdot\vec{b} = |\vec{a}|\,|\vec{b}| \cos\theta
$$

so

$$
\cos\theta = \frac{\vec{a}\cdot\vec{b}}{|\vec{a}|\,|\vec{b}|}
$$

## Step-by-Step Solution

### a) Magnitudes

For $\vec{a} = [2,1,-3]$:

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
$$

$$
|\vec{a}| = \sqrt{4 + 1 + 9} = \sqrt{14}
$$

For $\vec{b} = [4,-2,1]$:

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
$$

$$
|\vec{b}| = \sqrt{16 + 4 + 1} = \sqrt{21}
$$

### b) Dot product

$$
\vec{a}\cdot\vec{b} = (2)(4) + (1)(-2) + (-3)(1)
$$

$$
\vec{a}\cdot\vec{b} = 8 - 2 - 3 = 3
$$

### c) Cross product

Using components:

$$
\vec{a}\times\vec{b} =
\begin{pmatrix}
a_y b_z - a_z b_y \\
a_z b_x - a_x b_z \\
a_x b_y - a_y b_x
\end{pmatrix}
=
\begin{pmatrix}
(1)(1) - (-3)(-2) \\
(-3)(4) - (2)(1) \\
(2)(-2) - (1)(4)
\end{pmatrix}
$$

Compute each component:

$$
(1)(1) - (-3)(-2) = 1 - 6 = -5
$$

$$
(-3)(4) - (2)(1) = -12 - 2 = -14
$$

$$
(2)(-2) - (1)(4) = -4 - 4 = -8
$$

So

$$
\vec{a}\times\vec{b} =
\begin{pmatrix}
-5 \\
-14 \\
-8
\end{pmatrix}
$$

### d) Angle between the vectors

First compute $\cos\theta$:

$$
\cos\theta = \frac{\vec{a}\cdot\vec{b}}{|\vec{a}|\,|\vec{b}|}
= \frac{3}{\sqrt{14}\sqrt{21}}
$$

Since $14\cdot 21 = 294 = 49\cdot 6$, this simplifies to:

$$
\cos\theta = \frac{3}{\sqrt{294}} = \frac{3}{7\sqrt{6}} = \frac{\sqrt{6}}{14}
$$

Then the angle is

$$
\theta = \arccos\left(\frac{\sqrt{6}}{14}\right)
$$

## Final Result

$$
|\vec{a}| = \sqrt{14}, \quad |\vec{b}| = \sqrt{21}
$$

$$
\vec{a}\cdot\vec{b} = 3
$$

$$
\vec{a}\times\vec{b} =
\begin{pmatrix}
-5 \\
-14 \\
-8
\end{pmatrix}
$$

$$
\theta = \arccos\left(\frac{\sqrt{6}}{14}\right)
$$

## Interpretation

- The dot product is positive, so the angle is acute ($0^\circ < \theta < 90^\circ$).
- The cross product gives a vector perpendicular to the plane spanned by $\vec{a}$ and $\vec{b}$, with direction given by the right-hand rule.

# Task 02 – Systems of Equations

## Problem Statement

Find $x$ and $y$ that satisfy

$$
2x + 3y = 12, \quad x - y = 1
$$

## Theory

A linear system in two unknowns can be solved by substitution:

1. Solve one equation for one variable.
2. Substitute into the other equation.
3. Back-substitute to find the remaining variable.

## Step-by-Step Solution

From

$$
x - y = 1
$$

solve for $x$:

$$
x = y + 1
$$

Substitute into $2x + 3y = 12$:

$$
2(y+1) + 3y = 12
$$

Expand and combine like terms:

$$
2y + 2 + 3y = 12
$$

$$
5y + 2 = 12
$$

$$
5y = 10
$$

$$
y = 2
$$

Back-substitute into $x = y + 1$:

$$
x = 2 + 1 = 3
$$

## Final Result

$$
x = 3, \quad y = 2
$$

## Interpretation

The solution $(x,y)=(3,2)$ is the unique intersection point of the two lines represented by the equations.

# Task 03 – Proportionality in Gravitation

## Problem Statement

For

$$
F = G\frac{m_1 m_2}{r^2}
$$

determine the factor by which $F$ changes if $r$ is doubled and both masses are halved.

## Theory

The force scales proportionally as:

- $F \propto m_1$
- $F \propto m_2$
- $F \propto \frac{1}{r^2}$

Therefore, a change in variables produces a multiplicative change in $F$.

## Step-by-Step Solution

Let the new values be:

$$
r' = 2r, \quad m_1' = \frac{m_1}{2}, \quad m_2' = \frac{m_2}{2}
$$

Compute the ratio:

$$
\frac{F'}{F}
=
\frac{G\frac{m_1' m_2'}{(r')^2}}{G\frac{m_1 m_2}{r^2}}
=
\frac{m_1' m_2'}{m_1 m_2}\cdot \frac{r^2}{(r')^2}
$$

Mass factor:

$$
\frac{m_1' m_2'}{m_1 m_2}
=
\frac{\left(\frac{m_1}{2}\right)\left(\frac{m_2}{2}\right)}{m_1 m_2}
=
\frac{1}{4}
$$

Distance factor:

$$
\frac{r^2}{(r')^2}
=
\frac{r^2}{(2r)^2}
=
\frac{r^2}{4r^2}
=
\frac{1}{4}
$$

Combine:

$$
\frac{F'}{F} = \frac{1}{4}\cdot \frac{1}{4} = \frac{1}{16}
$$

## Final Result

$$
F' = \frac{1}{16}F
$$

## Interpretation

The gravitational force decreases by a factor of $16$ (it becomes sixteen times smaller).

# Task 04 – Rearranging the Pendulum Period Formula

## Problem Statement

Given

$$
T = 2\pi\sqrt{\frac{L}{g}}
$$

rearrange to obtain $g$ in terms of $T$ and $L$.

## Theory

To isolate a variable inside a square root:

1. Divide to isolate the square root.
2. Square both sides.
3. Solve algebraically for the desired variable.

## Step-by-Step Solution

Divide both sides by $2\pi$:

$$
\frac{T}{2\pi} = \sqrt{\frac{L}{g}}
$$

Square both sides:

$$
\left(\frac{T}{2\pi}\right)^2 = \frac{L}{g}
$$

Rewrite the left-hand side:

$$
\frac{T^2}{4\pi^2} = \frac{L}{g}
$$

Solve for $g$ by multiplying both sides by $g$ and then dividing:

$$
g\frac{T^2}{4\pi^2} = L
$$

$$
g = \frac{4\pi^2 L}{T^2}
$$

## Final Result

$$
g = \frac{4\pi^2 L}{T^2}
$$

## Interpretation

For a simple pendulum (small oscillations), measuring $T$ and knowing $L$ allows an experimental determination of the local gravitational acceleration $g$.

# Task 05 – Trigonometry: Vector Components

## Problem Statement

A vector $\vec{A}$ has magnitude $15$ and makes an angle $\theta = 60^\circ$ with the horizontal axis. Find horizontal and vertical components.

## Theory

For magnitude $A$ and angle $\theta$ from the positive horizontal axis:

$$
A_x = A\cos\theta, \quad A_y = A\sin\theta
$$

## Step-by-Step Solution

Horizontal component:

$$
A_x = 15\cos 60^\circ
$$

Using $\cos 60^\circ = \frac{1}{2}$:

$$
A_x = 15\cdot \frac{1}{2} = \frac{15}{2}
$$

Vertical component:

$$
A_y = 15\sin 60^\circ
$$

Using $\sin 60^\circ = \frac{\sqrt{3}}{2}$:

$$
A_y = 15\cdot \frac{\sqrt{3}}{2} = \frac{15\sqrt{3}}{2}
$$

## Final Result

$$
A_x = \frac{15}{2}, \quad A_y = \frac{15\sqrt{3}}{2}
$$

## Interpretation

The vector has a positive horizontal and positive vertical component, consistent with a $60^\circ$ angle in the first quadrant.

# Task 06 – Function Analysis: Local Extrema

## Problem Statement

For

$$
f(x) = 3x^2 - 12x + 7
$$

identify any local maxima or minima.

## Theory

Critical points occur where the derivative is zero:

$$
f'(x) = 0
$$

Classification uses the second derivative:

- If $f''(x) > 0$, the critical point is a local minimum.
- If $f''(x) < 0$, the critical point is a local maximum.

## Step-by-Step Solution

Differentiate:

$$
f'(x) = \frac{d}{dx}(3x^2 - 12x + 7) = 6x - 12
$$

Set equal to zero:

$$
6x - 12 = 0
$$

$$
6x = 12
$$

$$
x = 2
$$

Second derivative:

$$
f''(x) = \frac{d}{dx}(6x - 12) = 6
$$

Since

$$
f''(2) = 6 > 0
$$

the point is a local minimum.

Compute the function value:

$$
f(2) = 3(2^2) - 12(2) + 7 = 3(4) - 24 + 7
$$

$$
f(2) = 12 - 24 + 7 = -5
$$

## Final Result

$$
\text{Local minimum at } x=2 \text{ with } f(2)=-5
$$

## Interpretation

Because the quadratic coefficient $3$ is positive, the parabola opens upward, so it has exactly one minimum and no maximum.

# Task 07 – Logic & Series: Fly and Bicycle

## Problem Statement

A bicycle is $10$ m from a wall and moves toward it at constant speed $1$ m/s. A fly starts from the bicycle's front wheel and flies toward the wall at $2$ m/s. Each time it hits the wall, it instantly turns around and flies back to the bicycle, repeating this process. Find the total distance the fly travels before being crushed.

## Theory

If the fly continuously moves at constant speed until the bicycle hits the wall, then total fly distance is:

$$
d_{\text{fly}} = v_{\text{fly}}\,t_{\text{total}}
$$

The total time is determined only by the bicycle reaching the wall:

$$
t_{\text{total}} = \frac{d_{\text{bike}}}{v_{\text{bike}}}
$$

The many back-and-forth trips form an infinite sequence, but the sum is handled by the total time approach.

## Step-by-Step Solution

Time for the bicycle to reach the wall:

$$
t_{\text{total}} = \frac{10\ \text{m}}{1\ \text{m/s}} = 10\ \text{s}
$$

Fly distance in that time:

$$
d_{\text{fly}} = (2\ \text{m/s})(10\ \text{s}) = 20\ \text{m}
$$

## Final Result

$$
d_{\text{fly}} = 20\ \text{m}
$$

## Interpretation

Even though the fly makes infinitely many direction changes, it only has $10$ seconds before the bicycle reaches the wall, so the total traveled distance remains finite.

# Task 08 – Definite Integrals: Area Under $\sin(x)$

## Problem Statement

Compute the area under $f(x) = \sin(x)$ from $x=0$ to $x=\pi$.

## Theory

The signed area under a curve from $a$ to $b$ is the definite integral:

$$
\int_a^b f(x)\,dx
$$

An antiderivative of $\sin(x)$ is:

$$
\int \sin(x)\,dx = -\cos(x) + C
$$

## Step-by-Step Solution

Compute:

$$
\int_0^\pi \sin(x)\,dx = \left[-\cos(x)\right]_0^\pi
$$

Evaluate at the bounds:

$$
\left[-\cos(x)\right]_0^\pi = -\cos(\pi) - \left(-\cos(0)\right)
$$

Use $\cos(\pi)=-1$ and $\cos(0)=1$:

$$
-\cos(\pi) - \left(-\cos(0)\right) = -(-1) - (-(1)) = 1 + 1
$$

$$
\int_0^\pi \sin(x)\,dx = 2
$$

## Final Result

$$
\int_0^\pi \sin(x)\,dx = 2
$$

## Interpretation

On $[0,\pi]$, $\sin(x)\ge 0$, so the definite integral equals the geometric area under the curve.

# Task 09 – Optimization: Maximum-Area Rectangle Under a Curve

## Problem Statement

A rectangle lies under the curve

$$
y = 3 - x^2
$$

in the first quadrant. Find the rectangle dimensions that maximize the area.

## Theory

A standard interpretation for a rectangle "under the curve in the first quadrant" is:

- One corner at the origin $(0,0)$
- Sides along the axes
- The top-right corner at $(x,y)$ on the curve

Then

$$
y = 3 - x^2
$$

and the rectangle area is

$$
A(x) = x y = x(3 - x^2)
$$

Maximize $A(x)$ by setting $A'(x)=0$ and checking endpoints.

## Step-by-Step Solution

Define the area:

$$
A(x) = x(3 - x^2) = 3x - x^3
$$

Differentiate:

$$
A'(x) = \frac{d}{dx}(3x - x^3) = 3 - 3x^2
$$

Set equal to zero:

$$
3 - 3x^2 = 0
$$

$$
1 - x^2 = 0
$$

$$
x^2 = 1
$$

In the first quadrant, $x \ge 0$, so:

$$
x = 1
$$

Compute corresponding height:

$$
y = 3 - x^2 = 3 - 1 = 2
$$

## Final Result

$$
\text{Maximum-area rectangle: width } x=1,\ \text{height } y=2
$$

## Interpretation

The rectangle balances width and height: increasing $x$ increases width but decreases height because the curve slopes downward, producing an interior maximum.

# Task 10 – Infinite Series: Ant’s Final Position

## Problem Statement

An ant starts at the origin and moves:

- $1$ m east
- $1/2$ m north
- $1/3$ m west
- $1/4$ m south
- $1/5$ m east
- and so on

Find the final position.

## Theory

Separate motion into $x$-direction and $y$-direction.

- Odd steps affect $x$: east is positive, west is negative.
- Even steps affect $y$: north is positive, south is negative.

The $x$-coordinate becomes the alternating series over odd reciprocals:

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots
$$

This is the Maclaurin series for $\arctan(1)$:

$$
\arctan(1) = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots
$$

The $y$-coordinate becomes an alternating series over even reciprocals:

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \cdots
$$

Factor out $1/2$:

$$
y = \frac{1}{2}\left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots\right)
$$

The alternating harmonic series satisfies:

$$
1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots = \ln 2
$$

## Step-by-Step Solution

### $x$-coordinate

Using $\arctan(1)=\frac{\pi}{4}$:

$$
x = \frac{\pi}{4}
$$

### $y$-coordinate

Using the alternating harmonic series result:

$$
y = \frac{1}{2}\ln 2
$$

## Final Result

$$
(x,y) = \left(\frac{\pi}{4}, \frac{\ln 2}{2}\right)
$$

## Interpretation

The ant’s path converges to a finite point because both component series converge (alternating decreasing terms). The horizontal motion matches the classic $\arctan$ series at $1$, while the vertical motion is half of the alternating harmonic series.