# Recursive Least Squares : Variable Directional Forgetting

This notebook contains the unofficial implementation of the paper Recursive Least Squares with Variable-Direction Forgetting -- Compensating for the loss of persistency [https://arxiv.org/abs/2003.03523]
- Generated a synthetic dataset with two parameters (beta, gamma) for test the algorithm convergence [Present as example_data_gen() method in the RLS_VDF class
- The algorithm is stable over increase in time steps
- Estimated parameters are quite close to the ones used for generation of the synthetic dataset
# Use cases
- Adaptive filtering: Enables adaptive filters to adapt to changing conditions by updating parameters based on relevant and recent information while forgetting outdated data

- Signal processing: Widely used in noise cancellation, echo cancellation, equalization, and channel estimation to accurately estimate and track time-varying parameters

- Non-stationary environments: Enhances adaptability in scenarios where input signal properties change over time or exhibit non-stationary behavior

- System identification: Useful for estimating parameters of unknown systems based on observed input-output data, particularly for tracking time-varying parameters and capturing changes in system dynamics

- Robustness to outliers: Improves robustness by adaptively adjusting the forgetting factor to assign less weight to outliers, reducing their impact on parameter estimation

- Online learning: Suitable for real-time learning scenarios where data arrives sequentially, allowing continuous adaptation and utilization of new information

- Resource optimization: Optimizes computational resources by allocating effort based on parameter adaptability, leading to improved efficiency in memory usage and computational complexity
