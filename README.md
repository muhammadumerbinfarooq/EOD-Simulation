<h1>EOD-Simulation</h1>

<h2>Description</h2>
<p>MATLAB code for simulating explosive ordnance disposal (EOD) using finite element method and finite difference method.</p>

<h2>Table of Contents</h2>
<ol>
<li><a href="#introduction">Introduction</a></li>
<li><a href="#features">Features</a></li>
<li><a href="#simulation-details">Simulation Details</a></li>
<li><a href="#visualization">Visualization</a></li>
<li><a href="#code-structure">Code Structure</a></li>
<li><a href="#future-work">Future Work</a></li>
</ol>

<h2 id="introduction">Introduction</h2>
<p>This repository contains MATLAB code for simulating explosive ordnance disposal (EOD). The simulation uses the finite element method and finite difference method to model pressure wave propagation and velocity calculation.</p>

<h2 id="features">Features</h2>
<ul>
<li>Simulates pressure wave propagation and velocity calculation</li>
<li>Uses finite element method and finite difference method</li>
<li>Includes visualization of simulation results</li>
</ul>

<h2 id="simulation-details">Simulation Details</h2>
<ul>
<li>Explosive properties: mass, energy, detonation velocity</li>
<li>Environmental properties: air density, soil density, water density</li>
<li>Simulation parameters: time step, grid size, number of elements</li>
</ul>

<h2 id="visualization">Visualization</h2>
<ul>
<li>3D visualization of pressure wave propagation</li>
<li>2D visualization of velocity field</li>
</ul>

<h2 id="code-structure">Code Structure</h2>
<ul>
<li>`EOD_Simulation.m`: main simulation script</li>
<li>`create_mesh.m`: function to create finite element mesh</li>
<li>`assemble_global_matrix.m`: function to assemble global stiffness matrix and force vector</li>
<li>`solve_linear_system.m`: function to solve linear system using Gaussian elimination</li>
<li>`calculate_velocity.m`: function to calculate velocity using finite difference method</li>
</ul>

<h2 id="future-work">Future Work</h2>
<ul>
<li>Implement more advanced numerical methods, such as finite volume method or lattice Boltzmann method</li>
<li>Incorporate more complex explosive and environmental properties</li>
<li>Develop a user-friendly interface for inputting simulation parameters and visualizing results</li>
</ul>
