# Integrators and Integraphs

In the study of mathematical instruments, integrators and integraphs are devices used to determine the values of integrals graphically. While an integrator is used to evaluate a definite integral—resulting in a constant value—an integraph is used to determine an indefinite integral, which is expressed as a function of $x$.

## Integrators and the Planimeter
An integrator serves to evaluate a definite integral $\int_{a}^{b} f(x)dx$. When the equation $y = f(x)$ is plotted as a curve, the integral $\int ydx$ between specific limits represents the area of a figure bounded by the curve, the axis of $x$, and the ordinates at $x=a$ and $x=b$. Because of this relationship, any planimeter can be used to find the value of the integral, meaning planimeters function as integrators. Planimeters can be utilized to solve problems more complex than simple area determination by converting a problem graphically.

Certain integrators are designed to provide specific physical quantities. For example, if a line is drawn parallel to the axis $XX$ at a distance $\bar{y}$, it passes through the mass-centre of a given figure. In the context of a beam subject to bending, this line represents the neutral fibre for a proper choice of $XX$. Such an instrument can provide the area $A$, the distance of the mass-centre $\bar{y}$, and the moment of inertia $I$ (where $I + A\bar{y}^2$ is the moment of inertia for the neutral fibre), all of which are required to calculate the strength of a beam under bending. A primary application of this type of integrator is calculating the stability and displacement of a ship using drawings of various sections.

## Harmonic Analysers
A harmonic analyser is a specific type of integrator used to determine the coefficients of a periodic function $y$ of $x$ expanded in a series (Fourier's Series). The function is expressed as:
$y = A_0 + A_1 \cos \theta + A_2 \cos 2\theta + \dots + A_n \cos n\theta + \dots + B_1 \sin \theta + B_2 \sin 2\theta + \dots + B_n \sin n\theta + \dots$
where $\theta = 2\pi x / c$.

The absolute term $A_0$ represents the mean ordinate of the curve and can be determined by any planimeter. The other coefficients are determined by the integrals:
$A_n = \frac{1}{\pi} \int_{0}^{2\pi} y \cos n\theta \, d\theta$ and $B_n = \frac{1}{\pi} \int_{0}^{2\pi} y \sin n\theta \, d\theta$.

The first harmonic analyser was created by Lord Kelvin in 1876. In his design, the curve is drawn on a cylinder with a circumference equal to the period $c$, and simple harmonic motion is used to introduce the sine and cosine terms. Other versions were developed by Sharp, Henrici, and Sommerfeld and Wiechert of Konigsberg; the latter avoided harmonic motion by rotating the cylinder around an axis perpendicular to the cylinder's own axis. Lord Kelvin's instrument was notably used by the Meteorological Office in London to analyse meteorological curves.

## Integraphs and Differential Equations
An integraph determines the value of an indefinite integral, which is a function of $x$. Analytically, if $y$ is a given function $f(x)$, the function $Y = \int ydx + \text{const.}$ is determined by the condition $dY/dx = y$. Because $dY/dx$ is a number and cannot equal a length $y$, an arbitrary constant length $a$ is introduced as the unit to which the integraph draws the curve.

Integraphs can be extended to give the value of a definite integral as a function of a variable parameter. This is achieved by using a block of templets with a curve $y' = \phi(\xi)$ set at right angles to the axis of $x$. As the templets and the drawing-board move at the same rate, the instrument draws the curve $Y = F(\xi)$.

Furthermore, integraphs have been used to solve ordinary differential equations, particularly linear ones, by providing the solution as a curve. Lord Kelvin first suggested this application. While no "really useful" instrument has been produced for this purpose, it can be achieved by combining graphical work with an integraph if the variables are separated. For an equation $Xdx + Ydy = 0$ where $X = p(x)$ and $Y = \phi(y)$ are given as curves, the integraph can find $u$ as a function of $x$ and $v$ as a function of $y$ via the integrals $au = \int Xdx$ and $av = \int Ydy$. The general solution is then $u + v = c$.

## Complex Integration
In the theory of functions of a complex variable, the existence of a complex integral is established, and Cauchy's theorem relates to it. Integration is applied to series of functions of a complex variable, leading to Laurent's theorem and the expansion of functions as power series.

Certain integrals in the complex plane are subject to additive indeterminateness. For example, the integral $\int_{1}^{z} z^{-1}dz$ has an additive indeterminateness of $2\pi i$ when a closed path is taken about $z = 0$. Similarly, the integral $\int_{0}^{z} (1 + z^2)^{-1}dz$ is periodic with period $\pi$, representing the function $\tan(u)$.

Another application involves the integral $\int z \frac{f'(z)}{f(z)} dz$ taken around the perimeter of a primary parallelogram. The result of this integration is equal to $2\pi i$ times the sum of the residues of $z \frac{f'(z)}{f(z)}$ at the poles interior to the parallelogram. This allows for the inference that the sum of the values of $z$ where $f(z) = 0$ within any parallelogram is equal to the sum of the values of $z$ where $f(z) = \infty$, save for integral multiples of the periods.

## Sources
Compiled from: britannica11 vol05a bulgaria to calgary, britannica11 vol09a frost to fyzabad
---
*Written by the AI Librarian strictly from the public-domain books of the archive. Topic memory: data/written-topics.json*
