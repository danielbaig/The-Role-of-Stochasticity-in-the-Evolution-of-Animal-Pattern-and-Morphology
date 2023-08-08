# The-Role-of-Stochasticity-in-the-Evolution-of-Animal-Pattern-and-Morphology
This project was carried out in the summer of 2022. It consisted of an investigation into a gene regulatory network with a three gene topology. This was modelled using a set of coupled non-linear differential equations:

$$
\frac{dg_{ij}}{dt} = \phi\Big(\chi\Big( \sum\limits_{l=1}^3 W^{il}g_{lj} + M \Big)\Big) -\lambda g_{ij}
$$

where $\chi$ is a heaviside function and $\phi$ is a Michaelis-Menten function. Relevant theory and results are discussed in the report.
