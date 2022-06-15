# MpembaSplitting
We present the data used in 'Mpemba-like effect protocol for granular gases of inelastic and rough hard disks' (A. Megias and A. Santos) submitted to Frontiers in Physics.

## Dynamics and steady states
### Stationary values
The stationary values  $ \widetilde{T}^{\mathrm{st}} $, and  $\theta^{\mathrm{st}} $ from direct simulation Monte Carlo (DSMC) and event-driven molecular dynamics (EDMD) simulation results are in the folder 'Steady states' and the files have the following formats:
- 'Temp_st_results_ALPHA_BETA_METHOD.txt'
- 'theta_st_ALPHA_BETA_METHOD.txt'

Where 'Temp' stands for  $ \widetilde{T}^{\mathrm{st}} $; 'theta' for  $ \theta^{\mathrm{st}} $; 'ALPHA' and 'BETA' are the values of the normal and tangential coefficients of restitution, respectively; and 'METHOD' refers to whether DSMC or EDMD.

### Transient results
The values of  $ T^* $, and  $\theta $ at a given time  $t^* $ from direct simulation Monte Carlo (DSMC) and event-driven molecular dynamics (EDMD) simulation results are in the folder 'Transient' and the files have the following format:
- 'Evolution_METHOD_ALPHA_BETA_EPSILON.txt'

Where 'EPSILON' stands for the parameter  $\varepsilon $ of the Splitting Thermostat. In these files, the systems are initialized to  $T^*_0 = 1.5 $ and  $\theta_0=1 $.

## Applications of Mpemba effect protocols
### Standard Mpemba Effect (SME)

Here are the simulation results for the application of the SME protocol. For more details about the initial conditions see [].

The values of  $ T^* $, and  $\theta $ at a given time  $t^* $ from direct simulation Monte Carlo (DSMC) and event-driven molecular dynamics (EDMD) simulation results are in the folder 'SME' and the files have the following format:
- 'SME_METHOD_ALPHA_BETA_PRE/POST_A/B.txt'

Here 'PRE' refers to  $t<0$  data, and 'POST' for  $t>0$  . Moreover, 'A' stands for the initially hotter sample, and 'B' for the initially colder.

### Overshoot Mpemba Effect (OME)

Here are the simulation results for the application of the OME protocol. For more details about the initial conditions see [].

The values of  $ T^* $, and  $\theta $ at a given time  $t^* $ from direct simulation Monte Carlo (DSMC) and event-driven molecular dynamics (EDMD) simulation results are in the folder 'OME' and the files have the following format:
- 'SME_METHOD_ALPHA_BETA_PRE/POST_A/B.txt'
