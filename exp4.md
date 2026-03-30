**Experiment 4**  

In this experiment, we compare our method with the ADAM optimizer with MCMC densification.
The densification procedure is taken directly from (Kheradmand, 2024), and the maximum number of splats per scene is set to 1M. 
This experiment is run on the bicycle, drjohnson, and train scenes from the three datasets.

Due to the substantially increased number of Gaussian splats, ADAM with densification is able to outperform our method. 
However, we expect the same reconstruction quality for our method after densfication is incorporated, and we leave this for future work.

![Experiment results](https://anonymous.4open.science/r/8D9R6H4T/fig4.png)  
