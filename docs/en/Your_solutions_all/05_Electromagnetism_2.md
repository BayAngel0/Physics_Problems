# Section 5 – Electromagnetism II (Solutions)

# Task 01 – Gauss’s Law

## Problem Statement

A point charge of

$$
q = +2\ \text{C}
$$

is located at the origin. Determine the electric flux through a spherical surface of radius $1\ \text{m}$ centered at the origin.

## Theory

Gauss’s law states that the total electric flux through any closed surface is

$$
\Phi_E = \frac{q_{\text{enc}}}{\varepsilon_0}
$$

where

$$
\varepsilon_0 \approx 8.85 \times 10^{-12}\ \text{C}^2/(\text{N}\cdot \text{m}^2)
$$

The result depends only on the total enclosed charge, not on the radius of the sphere.

## Step-by-Step Solution

The spherical surface encloses the full charge

$$
q_{\text{enc}} = +2\ \text{C}
$$

Apply Gauss’s law:

$$
\Phi_E = \frac{q_{\text{enc}}}{\varepsilon_0}
$$

Substitute the values:

$$
\Phi_E = \frac{2}{8.85 \times 10^{-12}}
$$

$$
\Phi_E \approx 2.26 \times 10^{11}\ \text{N}\cdot \text{m}^2/\text{C}
$$

## Final Result

$$
\Phi_E \approx 2.26 \times 10^{11}\ \text{N}\cdot \text{m}^2/\text{C}
$$

## Interpretation

The flux is positive because the enclosed charge is positive. The sphere’s radius does not affect the total flux, because Gauss’s law depends only on enclosed charge.

# Task 02 – Ampère’s Law and Magnetic Field of Two Parallel Wires

## Problem Statement

Two long, parallel wires are separated by

$$
d = 10\ \text{cm} = 0.10\ \text{m}
$$

Each wire carries a current of

$$
I = 5\ \text{A}
$$

in opposite directions. Determine the magnitude and direction of the magnetic field at the midpoint between the wires.

## Theory

The magnetic field of a long straight wire at distance $r$ is

$$
B = \frac{\mu_0 I}{2\pi r}
$$

where

$$
\mu_0 = 4\pi \times 10^{-7}\ \text{T}\cdot \text{m/A}
$$

At the midpoint, the distance to each wire is

$$
r = \frac{d}{2}
$$

The two fields are added vectorially. For opposite currents, the field directions at the midpoint are the same, so the magnitudes add.

## Step-by-Step Solution

### Magnetic field due to one wire

The midpoint is at distance

$$
r = \frac{0.10}{2} = 0.05\ \text{m}
$$

Thus

$$
B_1 = \frac{\mu_0 I}{2\pi r}
$$

Substitute the values:

$$
B_1 = \frac{4\pi \times 10^{-7} \cdot 5}{2\pi \cdot 0.05}
$$

Simplify:

$$
B_1 = \frac{20\pi \times 10^{-7}}{0.1\pi}
$$

$$
B_1 = 2.0 \times 10^{-5}\ \text{T}
$$

### Total field

Since the currents are opposite, the two magnetic fields at the midpoint point in the same direction.

Therefore,

$$
B_{\text{tot}} = B_1 + B_2 = 2B_1
$$

$$
B_{\text{tot}} = 2(2.0 \times 10^{-5}) = 4.0 \times 10^{-5}\ \text{T}
$$

### Direction

Using the right-hand rule:

- if the left wire carries current upward and the right wire downward, then both fields at the midpoint point into the page,
- reversing both currents would reverse the field direction.

Thus the direction depends on the chosen current orientation, but the two contributions are always aligned.

## Final Result

$$
B_{\text{mid}} = 4.0 \times 10^{-5}\ \text{T}
$$

The magnetic field is perpendicular to the plane containing the wires and the midpoint. For one common orientation choice, it points into the page.

## Interpretation

Opposite currents produce magnetic fields that reinforce each other at the midpoint, whereas equal-direction currents would partially cancel there.

# Task 03 – Biot–Savart Law for a Small Current Segment

## Problem Statement

A small wire segment of length

$$
\ell = 0.1\ \text{m}
$$

carries current

$$
I = 3\ \text{A}
$$

The segment is at distance

$$
r = 0.2\ \text{m}
$$

from point $P$, and the segment is perpendicular to the line joining it to $P$.

Determine the magnetic field at $P$ due to this segment.

## Theory

For a small current element, the Biot–Savart law gives

$$
dB = \frac{\mu_0}{4\pi}\frac{I\,d\ell \sin\theta}{r^2}
$$

If the segment is perpendicular to the radius vector, then

$$
\theta = 90^\circ
$$

and

$$
\sin\theta = 1
$$

For a small segment of length $\ell$, approximate

$$
B \approx \frac{\mu_0}{4\pi}\frac{I\ell}{r^2}
$$

## Step-by-Step Solution

Substitute the values:

$$
B = \frac{\mu_0}{4\pi}\frac{I\ell}{r^2}
$$

Using

$$
\frac{\mu_0}{4\pi} = 10^{-7}\ \text{T}\cdot \text{m/A}
$$

gives

$$
B = 10^{-7}\frac{(3)(0.1)}{(0.2)^2}
$$

$$
B = 10^{-7}\frac{0.3}{0.04}
$$

$$
B = 10^{-7}(7.5)
$$

$$
B = 7.5 \times 10^{-7}\ \text{T}
$$

## Final Result

$$
B = 7.5 \times 10^{-7}\ \text{T}
$$

## Interpretation

The field is small because only a short current segment contributes. Its direction is given by the right-hand rule applied to the current element and the line to point $P$.

# Task 04 – Magnetic Torque on a Rectangular Loop

## Problem Statement

A rectangular wire loop has dimensions

$$
10\ \text{cm} \times 5\ \text{cm}
$$

and carries current

$$
I = 2\ \text{A}
$$

A uniform magnetic field of

$$
B = 0.3\ \text{T}
$$

is applied parallel to the plane of the loop.

Determine the magnitude of the magnetic torque on the loop.

## Theory

The torque on a current loop in a magnetic field is

$$
\tau = N I A B \sin\theta
$$

where

- $N$ is the number of turns,
- $A$ is the area of the loop,
- $\theta$ is the angle between the loop’s area vector and $\vec{B}$.

If the magnetic field is parallel to the plane of the loop, then it is perpendicular to the area vector, so

$$
\theta = 90^\circ
$$

and

$$
\sin\theta = 1
$$

## Step-by-Step Solution

Assume a single-turn loop, so

$$
N = 1
$$

Convert dimensions to meters:

$$
L = 0.10\ \text{m}, \qquad W = 0.05\ \text{m}
$$

Area:

$$
A = LW = 0.10 \cdot 0.05 = 0.005\ \text{m}^2
$$

Now compute the torque:

$$
\tau = N I A B
$$

$$
\tau = (1)(2)(0.005)(0.3)
$$

$$
\tau = 0.003\ \text{N}\cdot \text{m}
$$

## Final Result

$$
\tau = 3.0 \times 10^{-3}\ \text{N}\cdot \text{m}
$$

## Interpretation

The torque is maximum because the magnetic field is parallel to the plane of the loop. In that configuration, the loop experiences the strongest rotational tendency.

# Task 05 – Parallel-Plate Capacitor

## Problem Statement

A parallel-plate capacitor has parameters

$$
S = 0.02\ \text{m}^2
$$

$$
d = 5\ \text{mm} = 5 \times 10^{-3}\ \text{m}
$$

$$
V = 500\ \text{V}
$$

Determine:

1. the capacitance $C$,
2. the energy stored,
3. the electric field intensity between the plates,
4. the force of attraction between the plates.

## Theory

For a parallel-plate capacitor in vacuum (or air approximately),

$$
C = \varepsilon_0 \frac{S}{d}
$$

Stored energy:

$$
U = \frac{1}{2}CV^2
$$

Electric field between the plates:

$$
E = \frac{V}{d}
$$

The attractive force between the plates can be obtained from the field energy density or pressure:

$$
F = \frac{1}{2}\varepsilon_0 E^2 S
$$

## Step-by-Step Solution

### 1. Capacitance

Use

$$
C = \varepsilon_0 \frac{S}{d}
$$

Substitute values:

$$
C = 8.85 \times 10^{-12} \cdot \frac{0.02}{5 \times 10^{-3}}
$$

$$
C = 8.85 \times 10^{-12} \cdot 4
$$

$$
C = 3.54 \times 10^{-11}\ \text{F}
$$

### 2. Stored energy

Use

$$
U = \frac{1}{2}CV^2
$$

Substitute:

$$
U = \frac{1}{2}(3.54 \times 10^{-11})(500)^2
$$

$$
U = \frac{1}{2}(3.54 \times 10^{-11})(2.5 \times 10^5)
$$

$$
U \approx 4.43 \times 10^{-6}\ \text{J}
$$

### 3. Electric field intensity

Use

$$
E = \frac{V}{d}
$$

$$
E = \frac{500}{5 \times 10^{-3}}
$$

$$
E = 1.0 \times 10^5\ \text{V/m}
$$

### 4. Force of attraction

Use

$$
F = \frac{1}{2}\varepsilon_0 E^2 S
$$

Substitute:

$$
F = \frac{1}{2}(8.85 \times 10^{-12})(1.0 \times 10^5)^2(0.02)
$$

$$
F = \frac{1}{2}(8.85 \times 10^{-12})(10^{10})(0.02)
$$

$$
F = \frac{1}{2}(8.85 \times 10^{-2})(0.02)
$$

$$
F = 8.85 \times 10^{-4}\ \text{N}
$$

## Final Result

$$
C = 3.54 \times 10^{-11}\ \text{F}
$$

$$
U = 4.43 \times 10^{-6}\ \text{J}
$$

$$
E = 1.0 \times 10^5\ \text{V/m}
$$

$$
F = 8.85 \times 10^{-4}\ \text{N}
$$

## Interpretation

The capacitance is small because the plate area is moderate and the separation is several millimeters. The attractive force is also small, but it is a direct consequence of the stored electric field energy.

# Task 06 – Electromagnetic Wave Analysis

## Problem Statement

An electromagnetic wave has electric field component

$$
E_y(x,t) = 100 \sin(10^7 x - \omega t)\ \text{V/m}
$$

Determine:

- the direction of propagation,
- the wavelength $\lambda$,
- the angular frequency $\omega$,
- the equation for the magnetic field component.

## Theory

A wave of the form

$$
\sin(kx - \omega t)
$$

propagates in the positive $x$ direction.

The wave number is related to wavelength by

$$
k = \frac{2\pi}{\lambda}
$$

For an electromagnetic wave in vacuum,

$$
\omega = ck
$$

where

$$
c = 3.00 \times 10^8\ \text{m/s}
$$

Also,

$$
E_0 = cB_0
$$

so

$$
B_0 = \frac{E_0}{c}
$$

## Step-by-Step Solution

### Direction of propagation

Since the phase is

$$
10^7 x - \omega t
$$

the wave travels in the positive $x$ direction.

### Wavelength

Identify

$$
k = 10^7\ \text{rad/m}
$$

Use

$$
\lambda = \frac{2\pi}{k}
$$

Thus

$$
\lambda = \frac{2\pi}{10^7}
$$

$$
\lambda \approx 6.28 \times 10^{-7}\ \text{m}
$$

### Angular frequency

For an electromagnetic wave in vacuum,

$$
\omega = ck
$$

So

$$
\omega = (3.00 \times 10^8)(10^7)
$$

$$
\omega = 3.00 \times 10^{15}\ \text{rad/s}
$$

### Magnetic field equation

The electric field is along the $y$ direction, and the wave propagates along $+x$. Therefore the magnetic field must point along the $z$ direction so that

$$
\vec{E} \times \vec{B}
$$

points in the $+x$ direction.

The amplitude is

$$
B_0 = \frac{E_0}{c} = \frac{100}{3.00 \times 10^8}
$$

$$
B_0 \approx 3.33 \times 10^{-7}\ \text{T}
$$

Thus one suitable magnetic-field component is

$$
B_z(x,t) = 3.33 \times 10^{-7}\sin(10^7 x - \omega t)\ \text{T}
$$

## Final Result

Direction of propagation:

$$
+\hat{x}
$$

Wavelength:

$$
\lambda = \frac{2\pi}{10^7} \approx 6.28 \times 10^{-7}\ \text{m}
$$

Angular frequency:

$$
\omega = 3.00 \times 10^{15}\ \text{rad/s}
$$

Magnetic field:

$$
B_z(x,t) = 3.33 \times 10^{-7}\sin(10^7 x - \omega t)\ \text{T}
$$

## Interpretation

This is a transverse electromagnetic wave. The electric field oscillates in the $y$ direction, the magnetic field in the $z$ direction, and the wave propagates in the $x$ direction.

# Task 07 – Wavelength, Frequency, and Visible Color

## Problem Statement

The human eye is most sensitive to light with wavelength

$$
\lambda = 550\ \text{nm}
$$

Determine the corresponding visible color and frequency.

## Theory

Visible light around $550\ \text{nm}$ lies in the green region of the spectrum.

Frequency is related to wavelength by

$$
f = \frac{c}{\lambda}
$$

where

$$
c = 3.00 \times 10^8\ \text{m/s}
$$

## Step-by-Step Solution

Convert wavelength to meters:

$$
\lambda = 550\ \text{nm} = 550 \times 10^{-9}\ \text{m} = 5.50 \times 10^{-7}\ \text{m}
$$

Now compute frequency:

$$
f = \frac{3.00 \times 10^8}{5.50 \times 10^{-7}}
$$

$$
f \approx 5.45 \times 10^{14}\ \text{Hz}
$$

## Final Result

The color is approximately

$$
\text{green}
$$

and the frequency is

$$
f \approx 5.45 \times 10^{14}\ \text{Hz}
$$

## Interpretation

A wavelength near $550\ \text{nm}$ is near the peak sensitivity of human daylight vision, which is why green light appears especially bright to the eye.

# Task 08 – Order of the Electromagnetic Spectrum

## Problem Statement

List the following types of electromagnetic radiation in order of increasing wavelength:

- Infrared
- Ultraviolet
- Microwaves
- X-rays
- Radio waves
- Gamma rays

## Theory

Shorter wavelength corresponds to higher frequency and higher photon energy. The electromagnetic spectrum is ordered from shortest to longest wavelength.

## Step-by-Step Solution

From smallest wavelength to largest wavelength, the correct order is:

$$
\text{Gamma rays} \rightarrow \text{X-rays} \rightarrow \text{Ultraviolet} \rightarrow \text{Infrared} \rightarrow \text{Microwaves} \rightarrow \text{Radio waves}
$$

## Final Result

Increasing wavelength:

$$
\text{Gamma rays},\ \text{X-rays},\ \text{Ultraviolet},\ \text{Infrared},\ \text{Microwaves},\ \text{Radio waves}
$$

## Interpretation

Gamma rays and X-rays occupy the high-energy short-wavelength end, while microwaves and radio waves belong to the long-wavelength low-energy end.

# Task 09 – Refraction with Snell’s Law

## Problem Statement

A light ray travels from air

$$
n_1 = 1.00
$$

into glass

$$
n_2 = 1.50
$$

If the angle of incidence is

$$
\theta_1 = 30^\circ
$$

determine the angle of refraction $\theta_2$.

## Theory

Snell’s law is

$$
n_1 \sin\theta_1 = n_2 \sin\theta_2
$$

Thus,

$$
\sin\theta_2 = \frac{n_1}{n_2}\sin\theta_1
$$

## Step-by-Step Solution

Substitute the known values:

$$
\sin\theta_2 = \frac{1.00}{1.50}\sin 30^\circ
$$

Use

$$
\sin 30^\circ = 0.5
$$

So

$$
\sin\theta_2 = \frac{1}{1.5}(0.5) = \frac{1}{3}
$$

Therefore,

$$
\theta_2 = \sin^{-1}\left(\frac{1}{3}\right)
$$

$$
\theta_2 \approx 19.47^\circ
$$

## Final Result

$$
\theta_2 \approx 19.5^\circ
$$

## Interpretation

The ray bends toward the normal when it enters glass because glass has a larger refractive index than air.

# Task 10 – Speed of Light in Diamond

## Problem Statement

Determine the speed of light in diamond, whose refractive index is

$$
n = 2.42
$$

## Theory

The speed of light in a medium is

$$
v = \frac{c}{n}
$$

where

$$
c = 3.00 \times 10^8\ \text{m/s}
$$

## Step-by-Step Solution

Substitute the values:

$$
v = \frac{3.00 \times 10^8}{2.42}
$$

$$
v \approx 1.24 \times 10^8\ \text{m/s}
$$

## Final Result

$$
v \approx 1.24 \times 10^8\ \text{m/s}
$$

## Interpretation

Light travels much more slowly in diamond than in vacuum because diamond has a high refractive index, which is also responsible for its strong optical refraction and brilliance.