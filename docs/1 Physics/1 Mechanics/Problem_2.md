# Problem 2 

# Investigating the Dynamics of a Forced Damped Pendulum

## 1. Theoretical Foundation

The motion of a forced damped pendulum is governed by a second-order nonlinear differential equation that incorporates damping and external forcing effects.

### Governing Equation

The differential equation describing the angular displacement  $$\theta$$ of the pendulum is given by:

$$
\frac{d^2\theta}{dt^2} + b\frac{d\theta}{dt} + \frac{g}{L} \sin \theta = A \cos(\omega t)
$$

where:
- $$\theta(t)$$
 Angular displacement as a function of time  
- $$b$$
 Damping coefficient  
- $$\frac{g}{L}$$
 Term representing gravitational acceleration over pendulum length  
- $$A$$
 Amplitude of the external driving force  
- $$\omega$$
 Angular frequency of the driving force


### Small-Angle Approximation

For small angular displacements, the nonlinear term can be approximated as:

$$
\sin \theta \approx \theta
$$

This leads to the linearized equation:

$$
\frac{d^2\theta}{dt^2} + b\frac{d\theta}{dt} + \frac{g}{L} \theta = A \cos(\omega t)
$$

This simplification allows analytical techniques to be applied for understanding the system’s behavior.

### Phase Space Representation
![alt text](image-23.png)

### General Solution

The general solution is the sum of the transient and steady-state components:

$$
\theta(t) = \theta_{\text{hom}}(t) + \theta_{\text{part}}(t)
$$


 $$\theta_{\text{hom}}(t)$$

 Homogeneous (transient) solution, describing natural damping  

 $$\theta_{\text{part}}(t)$$

 Particular (steady-state) solution, describing forced response
### Numerical Results
 ![alt text](image-24.png)
It shows how the angular position of the system changes with time. It shows the effect of damping and coercive force on the system.
### Resonance Conditions

Resonance occurs when the driving frequency \( omega \) approaches the natural frequency of the system:

$$
\omega_0 = \sqrt{\frac{g}{L}}
$$

At or near resonance:

- The amplitude of oscillations increases significantly.
- Energy transfer from the driving force to the pendulum is maximized.
- System behavior may become unstable if damping is low.

Understanding resonance is essential in designing systems where oscillatory behavior must be controlled or optimized.

![alt text](image-25.png) 

This graph visualizes the resonant response of the system. If the drag force is low, there will be a sudden increase in the resonant frequency.

 ---


