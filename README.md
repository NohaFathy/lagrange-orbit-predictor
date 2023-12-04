# lagrange-orbit-predictor
# Satellite Orbit Calculator

A simple Python project for calculating the current velocity and position for a satellite. This project uses Lagrange coefficients to compute the current velocity and position based on the initial values provided by the user. Additionally, it calculates the time taken to reach this position.

## Features

- **Input:** Initial values of the satellite's velocity and position (\(V_0\), \(R_0\)).
- **Output:** Current velocity and position (\(V\), \(R\)) & time (\(t\)).

## How it Works

1. **Initial Values:**
   - Gravitational Parameter (\(\mu\)): \(398.6 \times 10^3 \, \text{km}^3/\text{s}^2\)
   - User inputs initial values for \(R_0\) and \(V_0\).

2. **Calculations:**
   - Specific angular momentum (\(h\))
   - Radial velocity (\(v_{r0}\))
   - Eccentricity (\(e\))
   - Magnitude of the new position vector (\(r_{\text{mag}}\))
   - Lagrange coefficients (\(f\), \(g\), \(f'\), \(g'\))
   - New position (\(R\)) and velocity (\(V\))

3. **Time Calculation:**
   - Specific energy (\(\epsilon\))
   - Semi-major axis (\(a\))
   - Orbital period (\(T\))

## Usage

1. Enter the values for \(R_0\) and \(V_0\) when prompted.
2. Run the script.
3. View the calculated current velocity (\(V\)) and position (\(R\)), as well as the time (\(t\)) taken to reach this position.

Feel free to explore and modify the code to suit your specific requirements.

# concepts 
Lagrange coefficients
orbit equation
perifocal frame 
true anomly 
semi major axis 

![orbit ](https://github.com/NohaFathy/lagrange-orbit-predictor/assets/112027310/2db7375e-3d41-4829-af16-2ba2c3548303)
 
# requirements 
Python3 IDLE OR VS
Tools:
(numpy )



# Resources
[references](https://kyleniemeyer.github.io/space-systems-notes/orbital-mechanics/two-body-problems.html)











