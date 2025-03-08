
Create an interactive HTML simulation for Physics (Mechanical Engineering) on the topic of "Simple Harmonic Motion".

Simulation Name: Pendulum Motion Simulation

Details:
Here’s a clear description of how your Simple Harmonic Motion (SHM) simulator should look and work:

Visual Appearance
Main Screen:

A horizontal axis representing time (t).

A vertical axis representing displacement (x) from the equilibrium position.

A smooth, oscillating curve (e.g., a sine or cosine wave) that represents the displacement of the object over time.

Moving Object:

A small dot or circle (e.g., red or blue) that moves back and forth along the displacement axis, tracing the oscillating curve.

The dot represents the object undergoing SHM (e.g., a mass on a spring or a pendulum bob).

Additional Plots (Optional):

Below the displacement plot, you can include two more graphs:

Velocity (v) vs. Time: A sine wave (out of phase with displacement).

Acceleration (a) vs. Time: A cosine wave (in phase with displacement but inverted).

Controls (Optional):

Sliders or input fields to adjust:

Amplitude (A): How far the object moves from the equilibrium position.

Frequency (f): How fast the object oscillates.

Phase Angle (φ): The starting point of the oscillation.

How It Works
Initialization:

When the simulation starts, the object (dot) is at its maximum displacement (amplitude).

The displacement curve begins to plot as time progresses.

Oscillation:

The dot moves smoothly back and forth along the displacement axis, following the equation:

x
(
t
)
=
A
cos
⁡
(
ω
t
+
ϕ
)
x(t)=Acos(ωt+ϕ)
where:

A
A = amplitude,

ω
=
2
π
f
ω=2πf = angular frequency,

ϕ
ϕ = phase angle.

Real-Time Updates:

As time progresses, the displacement curve is drawn, and the dot moves in sync with the curve.

If velocity and acceleration plots are included, they update simultaneously, showing how they relate to displacement.

Interactive Features (Optional):

Students can adjust the amplitude, frequency, or phase angle using sliders or input fields.

The simulation updates in real-time to reflect the changes, helping students visualize how these parameters affect the motion.

Key Observations:

The displacement curve is a smooth, periodic wave.

The velocity is maximum when the displacement is zero (equilibrium position).

The acceleration is maximum at the extremes of motion (maximum displacement) and always points toward the equilibrium position.

Example Scenario
Imagine a mass attached to a spring:

The dot represents the mass.

The displacement curve shows how the mass moves over time.

Students can see how increasing the amplitude makes the mass move farther, while increasing the frequency makes it oscillate faster.

Technical Requirements:
- Complexity Level: medium
- Interactivity Level: medium
- The simulation should be a single HTML file with embedded JavaScript and CSS
- Use modern JavaScript (ES6+) and CSS3
- Ensure the simulation is responsive and works on different screen sizes
- Include clear instructions for users
- Add appropriate visualizations, controls, and feedback mechanisms
- Implement proper physics/mathematical models where applicable
- Include appropriate error handling

The code should be well-commented and organized for educational purposes.
