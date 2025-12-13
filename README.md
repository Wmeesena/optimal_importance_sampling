# optimal_importance_sampling_simulation
**Author:** Wasin (Ton) Meesena, Liviu Aolaritei
**Date:** 12/12/2025




Code for Liviu's [paper](https://arxiv.org/abs/2504.03560). The technical part is shown in [report](https://www.overleaf.com/read/rvcdtbcynhtp#9e8fc6).





# Overview


We want to show three main results from this simulation: 

- convergence (+variance) of decision variable $\theta$ and tilting parameters $\mu$.
- tightness of the constraints on $\mu.$
- variance reduction 





## Experiment 1 

We want to compare this NDA approach with vanilla NDA and projected SGD.



## Experiment 2

We will try to reduce the box constraint on $\mu$, and see if they remain at the active constraints. 


## Experiment 3 

We specifically look at the variance. We will compute the optimal IS variance and the optimal non-IS variance, and display these as baselines. Then, we want to show that the variance from using this algorithm will converge to the optimal IS variance with a few iterations. 




