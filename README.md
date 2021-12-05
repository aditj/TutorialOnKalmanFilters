# DSP Tutorial On Kalman (Particle) Filters
Text Contents:  ( Please see Jupyter Notebook (Simulations.ipynb for detailed simulation tutorial ) 
### THE PROBLEM


Snippet of the actual route from Lohit to Library


### REPRESENTATION

```
Representative Route
```

### SENSORS

```
Sensor Locations
```

### MEASUREMENT

```
Measurement are noisy!
```

### BRIEF ON BAYES FILTER


## WHY PARTICLE FILTERS?

## APPLICATIONS

1. Localisations of Robots
2. Stock Trading
3. Tracking aircras and other locomotives (SDVs)

#### WHY PREFER THIS OVER THE OTHER FILTERS?

1. Multimodal - Multi Objects
2. Non Linear Behaviour - No Linear Model Required!

3. Unknown Process Model - Knowing process model is
good but not necessary
4. Non Gaussian Noise - Noise can be abrupt as well

5. Continous - Measurement Can be continous
6. Multivariate - Many Properties can be tracked

7. Occlusions - Collisions can be accounted for


### HOW PARTICLE FILTERS WORK?

```
Steps Involved:
```
1. Generate Particles
2. Predict Next State of the Particles
3. Update Particles according to measurements
4. Resample Particles
5. Compute Estimate

### SIMULATIONS, BOTTLENECKS AND IMPROVEMENTS
### SIMULATION RESULTS
### BOTTLENECKS AND IMPROVEMENTS
```
Filter Degeneracy
Filter Divergence - Noise of the sensor
Computation Costs
```



