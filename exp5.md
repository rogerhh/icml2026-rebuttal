**Experiment 5**  

In this experiment, we demonstrate the effectiveness of the derived trust region bounds in section 4.2 and Appendix B. We randomly generate 1000 Gaussian splats with random parameters. 
For each parameter type (position, scale, rotation, opacity, color), we select a single dimension to perturb by a large amount. 
We use our trust region clipping kernel to clip the perturbation by varying trust region thresholds, and measure the resulting squared Hellinger distance.


![Experiment results](https://anonymous.4open.science/r/8T9B6D4P/fig5.png)  
