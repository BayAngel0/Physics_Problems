# Section 3 – Waves (Solutions)

# Task 01 – Wave Properties

## Problem Statement

A sound wave in air has frequency $f = 440\ \text{Hz}$. If the speed of sound in air is $343\ \text{m/s}$, determine its wavelength in air. Then determine its wavelength in water, where the speed of sound is $1482\ \text{m/s}$.

## Theory

The basic wave relation is

$$
v = f\lambda
$$

Therefore,

$$
\lambda = \frac{v}{f}
$$

When a wave passes from one medium to another, its frequency remains constant, while its speed and wavelength change.

## Step-by-Step Solution

### Wavelength in air

Use

$$
\lambda_{\text{air}} = \frac{v_{\text{air}}}{f}
$$

Substitute the values:

$$
\lambda_{\text{air}} = \frac{343}{440}\ \text{m}
$$

$$
\lambda_{\text{air}} \approx 0.7795\ \text{m}
$$

### Wavelength in water

Use

$$
\lambda_{\text{water}} = \frac{v_{\text{water}}}{f}
$$

Substitute the values:

$$
\lambda_{\text{water}} = \frac{1482}{440}\ \text{m}
$$

$$
\lambda_{\text{water}} \approx 3.368\ \text{m}
$$

## Final Result

$$
\lambda_{\text{air}} \approx 0.780\ \text{m}
$$

$$
\lambda_{\text{water}} \approx 3.37\ \text{m}
$$

## Interpretation

The wavelength is much larger in water because the speed of sound is much higher there, while the frequency remains unchanged.

# Task 02 – String Harmonics

## Problem Statement

A guitar string is $64\ \text{cm}$ long and has a fundamental frequency of $330\ \text{Hz}$. Determine the wave speed on the string.

## Theory

For a string fixed at both ends, the fundamental mode has one antinode and satisfies

$$
L = \frac{\lambda_1}{2}
$$

Thus,

$$
\lambda_1 = 2L
$$

Then the wave speed is

$$
v = f\lambda
$$

## Step-by-Step Solution

Convert the length to meters:

$$
L = 64\ \text{cm} = 0.64\ \text{m}
$$

For the fundamental mode,

$$
\lambda_1 = 2L = 2(0.64) = 1.28\ \text{m}
$$

Now compute the wave speed:

$$
v = f\lambda_1 = 330 \cdot 1.28
$$

$$
v = 422.4\ \text{m/s}
$$

## Final Result

$$
v = 422.4\ \text{m/s}
$$

## Interpretation

The fundamental mode fits half a wavelength along the string, so the wave speed follows directly from the known frequency and string length.

# Task 03 – Superposition Principle

## Problem Statement

Two waves are given by

$$
y_1(x,t) = A\sin(kx-\omega t)
$$

and

$$
y_2(x,t) = A\sin(kx+\omega t)
$$

Determine the equation of the resulting standing wave and identify the node positions.

## Theory

The trigonometric identity

$$
\sin \alpha + \sin \beta = 2\sin\left(\frac{\alpha+\beta}{2}\right)\cos\left(\frac{\alpha-\beta}{2}\right)
$$

converts the sum of two traveling waves into the form of a standing wave.

## Step-by-Step Solution

Add the two waves:

$$
y(x,t) = y_1(x,t) + y_2(x,t)
$$

$$
y(x,t) = A\sin(kx-\omega t) + A\sin(kx+\omega t)
$$

Factor out $A$:

$$
y(x,t) = A\left[\sin(kx-\omega t) + \sin(kx+\omega t)\right]
$$

Use the identity with

$$
\alpha = kx-\omega t, \qquad \beta = kx+\omega t
$$

Then

$$
\frac{\alpha+\beta}{2} = kx, \qquad \frac{\alpha-\beta}{2} = -\omega t
$$

Since $\cos(-\omega t)=\cos(\omega t)$,

$$
y(x,t) = 2A\sin(kx)\cos(\omega t)
$$

This is the standing-wave form.

### Nodes

Nodes are positions where the displacement is always zero. Therefore,

$$
\sin(kx)=0
$$

This occurs when

$$
kx = n\pi
$$

where $n$ is any integer. Hence,

$$
x_n = \frac{n\pi}{k}
$$

Using $k=\frac{2\pi}{\lambda}$,

$$
x_n = \frac{n\pi}{2\pi/\lambda} = \frac{n\lambda}{2}
$$

## Final Result

$$
y(x,t) = 2A\sin(kx)\cos(\omega t)
$$

Node positions:

$$
x_n = \frac{n\pi}{k} = \frac{n\lambda}{2}, \qquad n \in \mathbb{Z}
$$

## Interpretation

The result is a standing wave: the spatial part $\sin(kx)$ determines fixed node positions, while $\cos(\omega t)$ describes the oscillation in time.

# Task 04 – Phase Difference

## Problem Statement

Determine the phase difference in radians between two points on a wave separated by a distance of $\lambda/3$.

## Theory

The phase difference associated with a spatial separation $\Delta x$ is

$$
\Delta \phi = k\Delta x
$$

where

$$
k = \frac{2\pi}{\lambda}
$$

Therefore,

$$
\Delta \phi = \frac{2\pi}{\lambda}\Delta x
$$

## Step-by-Step Solution

Given

$$
\Delta x = \frac{\lambda}{3}
$$

Substitute into the phase formula:

$$
\Delta \phi = \frac{2\pi}{\lambda}\cdot \frac{\lambda}{3}
$$

$$
\Delta \phi = \frac{2\pi}{3}
$$

## Final Result

$$
\Delta \phi = \frac{2\pi}{3}\ \text{rad}
$$

## Interpretation

A separation of one third of a wavelength corresponds to one third of a full $2\pi$ phase cycle.

# Task 05 – Echo Ranging

## Problem Statement

A person shouts toward a cliff and hears the echo $1$ second later. The speed of sound in air is $343\ \text{m/s}$. Determine the distance to the cliff.

## Theory

The echo time includes the forward trip to the cliff and the return trip back to the person. Thus the total distance traveled by the sound is

$$
d_{\text{total}} = vt
$$

The one-way distance to the cliff is half of that:

$$
d = \frac{vt}{2}
$$

## Step-by-Step Solution

Given

$$
v = 343\ \text{m/s}, \quad t = 1\ \text{s}
$$

Total distance traveled by the sound:

$$
d_{\text{total}} = vt = 343 \cdot 1 = 343\ \text{m}
$$

Distance to the cliff:

$$
d = \frac{343}{2} = 171.5\ \text{m}
$$

## Final Result

$$
d = 171.5\ \text{m}
$$

## Interpretation

The sound wave travels to the cliff and back, so the measured time must be divided equally between the two parts of the journey.

# Task 06 – Wave Equation Parameters

## Problem Statement

A wave is described by

$$
y(x,t) = 0.05\sin(2\pi x - 50\pi t)
$$

with $x$ and $y$ in meters and $t$ in seconds. Determine:

- amplitude $A$,
- wavelength $\lambda$,
- frequency $f$,
- wave speed $v$.

## Theory

The standard traveling-wave form is

$$
y(x,t) = A\sin(kx-\omega t)
$$

where

$$
k = \frac{2\pi}{\lambda}, \qquad \omega = 2\pi f, \qquad v = \frac{\omega}{k} = f\lambda
$$

## Step-by-Step Solution

Compare the given equation

$$
y(x,t) = 0.05\sin(2\pi x - 50\pi t)
$$

with the standard form.

Thus,

$$
A = 0.05
$$

$$
k = 2\pi
$$

$$
\omega = 50\pi
$$

### Amplitude

$$
A = 0.05\ \text{m}
$$

### Wavelength

Use

$$
k = \frac{2\pi}{\lambda}
$$

So

$$
2\pi = \frac{2\pi}{\lambda}
$$

Hence,

$$
\lambda = 1\ \text{m}
$$

### Frequency

Use

$$
\omega = 2\pi f
$$

So

$$
50\pi = 2\pi f
$$

$$
f = 25\ \text{Hz}
$$

### Wave speed

Use

$$
v = f\lambda = 25 \cdot 1 = 25\ \text{m/s}
$$

Alternatively,

$$
v = \frac{\omega}{k} = \frac{50\pi}{2\pi} = 25\ \text{m/s}
$$

## Final Result

$$
A = 0.05\ \text{m}
$$

$$
\lambda = 1.0\ \text{m}
$$

$$
f = 25\ \text{Hz}
$$

$$
v = 25\ \text{m/s}
$$

## Interpretation

The wave has a small amplitude, one-meter wavelength, and propagates in the positive $x$ direction with speed $25\ \text{m/s}$.

# Task 07 – Standing Wave Modes

## Problem Statement

A standing wave with four antinodes is produced on a string of length $L = 80\ \text{cm}$. Determine the wavelength.

## Theory

For a string fixed at both ends, the $n$th normal mode has $n$ antinodes and satisfies

$$
L = n\frac{\lambda}{2}
$$

Therefore,

$$
\lambda = \frac{2L}{n}
$$

## Step-by-Step Solution

Convert the length:

$$
L = 80\ \text{cm} = 0.80\ \text{m}
$$

Four antinodes means

$$
n=4
$$

Thus,

$$
\lambda = \frac{2L}{n} = \frac{2(0.80)}{4}
$$

$$
\lambda = \frac{1.60}{4} = 0.40\ \text{m}
$$

## Final Result

$$
\lambda = 0.40\ \text{m}
$$

## Interpretation

Four antinodes correspond to the fourth harmonic, so the string contains four half-wavelength segments.

# Task 08 – Which Functions Describe Traveling Waves?

## Problem Statement

Determine which of the following can describe a traveling wave by checking whether it satisfies the wave equation

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2}\frac{\partial^2 y}{\partial t^2}
$$

a)

$$
y(x,t) = A\cos(kx^2-\omega t)
$$

b)

$$
y(x,t) = A(x-vt)^2
$$

c)

$$
y(x,t) = A\log(x+vt)
$$

## Theory

Any sufficiently differentiable function of the form

$$
y(x,t)=f(x-vt)
$$

or

$$
y(x,t)=g(x+vt)
$$

is a traveling-wave solution of the one-dimensional wave equation.

## Step-by-Step Solution

### a) Function $A\cos(kx^2-\omega t)$

This function depends on the combination

$$
kx^2-\omega t
$$

which is not of the form $x\pm vt$. Therefore it is already suspicious.

Compute derivatives. Let

$$
\phi = kx^2-\omega t
$$

Then

$$
\frac{\partial y}{\partial x} = -A\sin\phi \cdot 2kx
$$

Differentiate again:

$$
\frac{\partial^2 y}{\partial x^2} = -2Ak\sin\phi - 4Ak^2x^2\cos\phi
$$

Now time derivatives:

$$
\frac{\partial y}{\partial t} = -A\sin\phi \cdot (-\omega) = A\omega\sin\phi
$$

$$
\frac{\partial^2 y}{\partial t^2} = -A\omega^2\cos\phi
$$

These expressions cannot satisfy

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2}\frac{\partial^2 y}{\partial t^2}
$$

for all $x$ and $t$ because $\frac{\partial^2 y}{\partial x^2}$ contains both $\sin\phi$ and $x^2\cos\phi$ terms.

Therefore, function (a) is not a traveling-wave solution.

### b) Function $A(x-vt)^2$

Let

$$
u = x-vt
$$

Then

$$
y = Au^2
$$

Spatial derivatives:

$$
\frac{\partial y}{\partial x} = 2Au
$$

$$
\frac{\partial^2 y}{\partial x^2} = 2A
$$

Time derivatives:

$$
\frac{\partial y}{\partial t} = 2Au(-v) = -2Avu
$$

$$
\frac{\partial^2 y}{\partial t^2} = 2Av^2
$$

Hence,

$$
\frac{1}{v^2}\frac{\partial^2 y}{\partial t^2} = \frac{1}{v^2}(2Av^2)=2A
$$

Thus,

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2}\frac{\partial^2 y}{\partial t^2}
$$

So function (b) satisfies the wave equation.

### c) Function $A\log(x+vt)$

Let

$$
u = x+vt
$$

Then

$$
y = A\log u
$$

Spatial derivatives:

$$
\frac{\partial y}{\partial x} = \frac{A}{u}
$$

$$
\frac{\partial^2 y}{\partial x^2} = -\frac{A}{u^2}
$$

Time derivatives:

$$
\frac{\partial y}{\partial t} = \frac{A}{u}\cdot v = \frac{Av}{u}
$$

$$
\frac{\partial^2 y}{\partial t^2} = -\frac{Av^2}{u^2}
$$

Therefore,

$$
\frac{1}{v^2}\frac{\partial^2 y}{\partial t^2} = \frac{1}{v^2}\left(-\frac{Av^2}{u^2}\right) = -\frac{A}{u^2}
$$

Thus,

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2}\frac{\partial^2 y}{\partial t^2}
$$

So function (c) also satisfies the wave equation.

## Final Result

- (a) does **not** describe a traveling-wave solution.
- (b) **does** describe a traveling wave.
- (c) **does** describe a traveling wave.

## Interpretation

The decisive feature is dependence on the combinations $x-vt$ or $x+vt$. Functions of these variables propagate without changing shape and therefore satisfy the wave equation.

# Task 09 – Damped Oscillator

## Problem Statement

For the damped harmonic oscillator

$$
m\frac{d^2x}{dt^2} + b\frac{dx}{dt} + kx = 0
$$

provide:

1. the general analytical solution,
2. the classification into underdamped, critically damped, and overdamped cases,
3. a numerical RK4 solution strategy,
4. discussion of the effect of parameter $b$,
5. a graph of $x(t)$,
6. a phase portrait,
7. an interactive HTML animation with a slider for $b$.

## Theory

The damped oscillator equation is

$$
m\ddot{x} + b\dot{x} + kx = 0
$$

Its characteristic equation is

$$
mr^2 + br + k = 0
$$

The nature of the roots determines the motion.

Define the discriminant

$$
\Delta = b^2 - 4mk
$$

## Step-by-Step Solution

### 1. General solution

The characteristic roots are

$$
r_{1,2} = \frac{-b \pm \sqrt{b^2-4mk}}{2m}
$$

#### Underdamped case

If

$$
b^2 < 4mk
$$

the roots are complex:

$$
r = -\frac{b}{2m} \pm i\omega_d
$$

where

$$
\omega_d = \sqrt{\frac{k}{m} - \frac{b^2}{4m^2}}
$$

The solution is

$$
x(t) = e^{-bt/(2m)}\left(C_1\cos(\omega_d t) + C_2\sin(\omega_d t)\right)
$$

#### Critically damped case

If

$$
b^2 = 4mk
$$

the repeated root is

$$
r = -\frac{b}{2m}
$$

and the solution is

$$
x(t) = (C_1 + C_2 t)e^{-bt/(2m)}
$$

#### Overdamped case

If

$$
b^2 > 4mk
$$

the roots are real and distinct:

$$
r_{1,2} = \frac{-b \pm \sqrt{b^2-4mk}}{2m}
$$

and the solution is

$$
x(t) = C_1 e^{r_1 t} + C_2 e^{r_2 t}
$$

### 2. Classification of cases

The critical damping value is

$$
b_c = 2\sqrt{mk}
$$

Thus:

- underdamped if $b < b_c$,
- critically damped if $b = b_c$,
- overdamped if $b > b_c$.

### 3. RK4 formulation

Rewrite the second-order equation as a first-order system:

$$
\dot{x} = v
$$

$$
\dot{v} = -\frac{b}{m}v - \frac{k}{m}x
$$

This system can be solved numerically with the fourth-order Runge–Kutta method.

### 4. Effect of $b$

- Small $b$ gives oscillatory motion with slowly decaying amplitude.
- At $b=b_c$, the system returns to equilibrium as fast as possible without oscillation.
- Large $b$ suppresses oscillation and produces a slow monotonic return to equilibrium.

### 5. Graph of $x(t)$

The graph of $x(t)$ shows decaying oscillations for the underdamped case and non-oscillatory relaxation for the other two cases.

### 6. Phase portrait

The phase portrait is the curve in the $(x,v)$ plane.  
For underdamping it spirals toward the origin.  
For critical and overdamping it approaches the origin without spiraling.

### 7. Interactive HTML animation

The following HTML file implements:

- a slider for $b$,
- RK4 integration,
- a plot of $x(t)$,
- a phase portrait $(x,v)$,
- case classification.

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Damped Oscillator</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 20px;
    background: #f7f7f7;
  }
  h1, h2 {
    margin-bottom: 8px;
  }
  .controls {
    margin-bottom: 16px;
    padding: 12px;
    background: white;
    border-radius: 8px;
  }
  canvas {
    background: white;
    border: 1px solid #ccc;
    border-radius: 8px;
    margin-right: 16px;
    margin-bottom: 16px;
  }
  .row {
    display: flex;
    flex-wrap: wrap;
  }
  label {
    display: inline-block;
    min-width: 140px;
  }
  .info {
    margin-top: 8px;
    font-weight: bold;
  }
</style>
</head>
<body>
  <h1>Damped Harmonic Oscillator</h1>

  <div class="controls">
    <div>
      <label for="bSlider">Damping $b$:</label>
      <input type="range" id="bSlider" min="0" max="20" step="0.1" value="2">
      <span id="bValue">2.0</span>
    </div>
    <div>
      <label for="mInput">Mass $m$:</label>
      <input type="number" id="mInput" value="1" step="0.1">
    </div>
    <div>
      <label for="kInput">Spring constant $k$:</label>
      <input type="number" id="kInput" value="10" step="0.1">
    </div>
    <div>
      <label for="x0Input">Initial position $x(0)$:</label>
      <input type="number" id="x0Input" value="1" step="0.1">
    </div>
    <div>
      <label for="v0Input">Initial velocity $v(0)$:</label>
      <input type="number" id="v0Input" value="0" step="0.1">
    </div>
    <div class="info" id="caseLabel"></div>
  </div>

  <div class="row">
    <canvas id="xtCanvas" width="600" height="300"></canvas>
    <canvas id="phaseCanvas" width="600" height="300"></canvas>
  </div>

<script>
const bSlider = document.getElementById("bSlider");
const bValue = document.getElementById("bValue");
const mInput = document.getElementById("mInput");
const kInput = document.getElementById("kInput");
const x0Input = document.getElementById("x0Input");
const v0Input = document.getElementById("v0Input");
const caseLabel = document.getElementById("caseLabel");

const xtCanvas = document.getElementById("xtCanvas");
const phaseCanvas = document.getElementById("phaseCanvas");
const xtCtx = xtCanvas.getContext("2d");
const phaseCtx = phaseCanvas.getContext("2d");

function rk4Step(x, v, dt, m, b, k) {
  function ax(x, v) {
    return -(b/m)*v - (k/m)*x;
  }

  const k1x = v;
  const k1v = ax(x, v);

  const k2x = v + 0.5 * dt * k1v;
  const k2v = ax(x + 0.5 * dt * k1x, v + 0.5 * dt * k1v);

  const k3x = v + 0.5 * dt * k2v;
  const k3v = ax(x + 0.5 * dt * k2x, v + 0.5 * dt * k2v);

  const k4x = v + dt * k3v;
  const k4v = ax(x + dt * k3x, v + dt * k3v);

  x += (dt / 6) * (k1x + 2*k2x + 2*k3x + k4x);
  v += (dt / 6) * (k1v + 2*k2v + 2*k3v + k4v);

  return { x, v };
}

function simulate(m, b, k, x0, v0, tMax = 20, dt = 0.01) {
  const data = [];
  let x = x0;
  let v = v0;
  for (let t = 0; t <= tMax; t += dt) {
    data.push({ t, x, v });
    const step = rk4Step(x, v, dt, m, b, k);
    x = step.x;
    v = step.v;
  }
  return data;
}

function drawAxes(ctx, width, height, xLabel, yLabel) {
  ctx.clearRect(0, 0, width, height);
  ctx.strokeStyle = "#999";
  ctx.lineWidth = 1;

  ctx.beginPath();
  ctx.moveTo(40, height - 30);
  ctx.lineTo(width - 20, height - 30);
  ctx.stroke();

  ctx.beginPath();
  ctx.moveTo(40, 20);
  ctx.lineTo(40, height - 30);
  ctx.stroke();

  ctx.fillStyle = "#000";
  ctx.fillText(xLabel, width - 30, height - 10);
  ctx.fillText(yLabel, 10, 20);
}

function drawXT(data) {
  drawAxes(xtCtx, xtCanvas.width, xtCanvas.height, "t", "x");

  const tMax = data[data.length - 1].t;
  const xs = data.map(p => p.x);
  const xMin = Math.min(...xs);
  const xMax = Math.max(...xs);
  const range = Math.max(1e-6, xMax - xMin);

  xtCtx.strokeStyle = "#0066cc";
  xtCtx.lineWidth = 2;
  xtCtx.beginPath();

  data.forEach((p, i) => {
    const px = 40 + (p.t / tMax) * (xtCanvas.width - 60);
    const py = (xtCanvas.height - 30) - ((p.x - xMin) / range) * (xtCanvas.height - 50);
    if (i === 0) xtCtx.moveTo(px, py);
    else xtCtx.lineTo(px, py);
  });

  xtCtx.stroke();
}

function drawPhase(data) {
  drawAxes(phaseCtx, phaseCanvas.width, phaseCanvas.height, "x", "v");

  const xs = data.map(p => p.x);
  const vs = data.map(p => p.v);
  const xMin = Math.min(...xs), xMax = Math.max(...xs);
  const vMin = Math.min(...vs), vMax = Math.max(...vs);
  const xRange = Math.max(1e-6, xMax - xMin);
  const vRange = Math.max(1e-6, vMax - vMin);

  phaseCtx.strokeStyle = "#cc3300";
  phaseCtx.lineWidth = 2;
  phaseCtx.beginPath();

  data.forEach((p, i) => {
    const px = 40 + ((p.x - xMin) / xRange) * (phaseCanvas.width - 60);
    const py = (phaseCanvas.height - 30) - ((p.v - vMin) / vRange) * (phaseCanvas.height - 50);
    if (i === 0) phaseCtx.moveTo(px, py);
    else phaseCtx.lineTo(px, py);
  });

  phaseCtx.stroke();
}

function update() {
  const m = parseFloat(mInput.value);
  const b = parseFloat(bSlider.value);
  const k = parseFloat(kInput.value);
  const x0 = parseFloat(x0Input.value);
  const v0 = parseFloat(v0Input.value);

  bValue.textContent = b.toFixed(1);

  const bc = 2 * Math.sqrt(m * k);
  let label = "";
  if (b < bc) label = "Underdamped";
  else if (Math.abs(b - bc) < 1e-6) label = "Critically damped";
  else label = "Overdamped";

  caseLabel.textContent = `Critical damping b_c = ${bc.toFixed(3)} | Current case: ${label}`;

  const data = simulate(m, b, k, x0, v0);
  drawXT(data);
  drawPhase(data);
}

[bSlider, mInput, kInput, x0Input, v0Input].forEach(el => {
  el.addEventListener("input", update);
});

update();
</script>
</body>
</html>