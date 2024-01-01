# Numerical-Simulation-of-Third-Harmonic-Generation

We have tried to numerically solve the coupled amplitude equations by dividing the domain into small steps(1000 steps taken here for a length of 1 unit). The differential is approximated to the difference in values as the step size is 'small'. 
Therefore, we calculate the values of $A_w$ and $A_{3w}$ at each step by using the difference equation derived from the differential equation. 
$$\Delta A_{3w} = i \kappa A_w^3 e^{i\Delta kz} \Delta z$$
$$\Delta A_{w} = i \kappa A_{3w} A_w^{*2} e^{-i\Delta kz} \Delta z$$
$\Delta z$ is the step size used and $A_w$ and $A_{3w}$ are updated at each step
