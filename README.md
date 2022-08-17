#### VISCOUS introduction
VISCOUS is a computationally frugal variance-based global sensitivity analysis framework (Sheikholeslami et al., 2021). VISCOUS consists of two elements, namely (1) developing a probability model to describe the relationship between model inputs (e.g., model parameters) and outputs (e.g., model responses); and (2) computating sensitivity indices based on the developed probability model. 

#### Repository structure
The repo is split between functions and demos. 
- Functions include the open-source code of VISCOUS, which is pyVISCOUS. pyVISCOUS is independent from models and can be applied with user-provided input-output data. 
- Demos include the four functions employed in Liu et al. (2022): the Rosenbrock function and three Sobol functions (Type A, B, and C). In each demo, there are scripts to generate input-output data, set up and run VISCOUS, and evaluate the sensitivity results.


#### References
Sheikholeslami, R., Gharari, S., Papalexiou, S. M., & Clark, M. P. (2021) VISCOUS: A variance-based sensitivity analysis using copulas for efficient identification of dominant hydrological processes. Water Resources Research, 57, e2020WR028435. https://doi.org/10.1029/2020WR028435 

Liu, H., Clark, M. P., Gharari, S., Sheikholeslami, R., Freer, J., & Papalexiou, S. M. (2022) pyVISCOUS: An open-source tool for computationally frugal global sensitivity analysis. (Prepare to submit to Water Resources Research)
