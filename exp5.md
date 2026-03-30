**Experiment 5**  

In this experiment, we demonstrate the effectiveness of the derived trust region bounds in section 4.2 and Appendix B. We randomly generate 1000 Gaussian splats with random parameters. 
For each parameter type (position, scale, rotation, opacity, color), we select a single dimension to perturb by a large amount. 
We use our trust region clipping kernel by varying trust region thresholds, and measure the squared Hellinger distance after the clipped perturbation.

The resulting scatter plot shows that our derived bounds are accurate around small thresholds, and we note that the bounds are sometimes exceeded for the opacity and color parameters due to the quadratic approximation used in the derivation.


![Experiment results](https://anonymous.4open.science/r/8D9R6H4T/fig5.png)  
