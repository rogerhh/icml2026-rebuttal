**Experiment 1**  

In this experiment, we compare our adaptive trust region method with a fixed-radius trust region. 
The fixed radius of each parameter type is set to the learning rate in the ADAM optimizer.
This results reported below are averaged across all scenes in the three datasets.

In general, because the fixed-radius trust region method cannot exceed the learning rate of ADAM, the benefits of the faster convergence rate from the second-order optimization are diminished.


![Experiment results](https://anonymous.4open.science/r/8D9R6H4T/fig1.png)  
