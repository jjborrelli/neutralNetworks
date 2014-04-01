# Neutral Networks Nonsense

New paper by Canard et al. compare neutral expectations of network metrics to empirical estimates. Neutral expectations are derived by the empirical abundance distribution.  

**THEIR PAPER ASSUMES THAT THERE IS NO LINK BETWEEN SPECIES ABUNDANCE AND THE COMMUNITY STRUCTURE IN WHICH IT IS FOUND!**

Neutral models of networks are those in which the probability of two species interacting is simply the product of their abundances.  

A key assumption of nuetral models of interaction networks then, is that abundance is independent of the links between species. To me, this assumption of disconnection between population abundance and community structure is nonsensical. Neutral interaction networks don't really make sense then. If abundance is related to, or a function of, the particular characteristics of the network that a given node is embedded in, then we would of course expect that neutral models using empirical abundance measures replicate network structure. 

Alternatively, one could imagine an experiment that showed that abundance is independent of community context. If organism A is in two communities (a generalist in one and a specialist in another) and it was abundant in both, then I could imagine that abundance could be decoupled from network structure.    

Here I propose a simulation modelling approach to determine whether neutral models are in fact reliable null models?  

- create a niche model food web, that we know is explicitly created through niche processes
- randomly assign population sizes to the nodes
- run population dynamic simulations for a predefined number of timesteps
- "sample" the populations to get abundance
- recreate the network using neutral approaches
- A neutral model should not be able to capture the basic network patterns