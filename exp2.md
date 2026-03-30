**Experiment 2**  

In this experiment, we sweep the hyperparameter epsilon, which is the trust region threshold.
We keep the exponential decay scheduler the same as the ADAM optimizer, and vary the initial epsilon value from 1e-5 to 1e-7. (Epsilon from 1e-6 to 1e-8 is the setting we used in the paper.)
This results reported below are averaged across all scenes in the three datasets.

We found that the performance of our method is improved with a larger epsilon value, which allows the Gaussian splats to be updated faster.

![Experiment results](https://anonymous.4open.science/r/8D9R6H4T/fig2.png)  
