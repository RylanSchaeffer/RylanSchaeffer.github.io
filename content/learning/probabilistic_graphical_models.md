# Probabilistic Graphical Models

## Overview

A joint distribution over $$N$$ variables $$\underline{x}$$ can permit complicated relationships
between the variables. One general principle is that performing inference
becomes easier in the absence of relationships between variables. This motivates
us to specify relationships between variables as a graphs and then use the graph
structure to design efficient inference algorithms.

- [History](probabilistic_graphical_models/history.md)
- Types of Graphical Models
    - [Directed Graphs](probabilistic_graphical_models/directed_graphical_models.md)
    - [Undirected Graphs](probabilistic_graphical_models/undirected_graphical_models.md)
    - [Factor Graphs](probabilistic_graphical_models/factor_graphical_models.md)
    - [Ancestral Graphs](probabilistic_graphical_models/ancestral_graphical_models.md)
    - [Graph Relations](probabilistic_graphical_models/)  
    - Causal Graphs
- Parameter Estimation
    - Maximum Likelihood
- Types of Inference Problems
    - Marginalization
    - Most Probable Configuration / MAP
- Exact Inference Algorithms
    - [Elimination Algorithm](probabilistic_graphical_models/elimination_algorithm.md)
    - [Sum-Product (Belief Propagation)](probabilistic_graphical_models/belief_propagation.md)
    - [Junction Tree Algorithm](probabilistic_graphical_models/junction_tree_algorithm.md)
- Approximate Inference Algorithms
    - Loopy Belief Propagation
    - Variational Inference
    - Graph Partitioning
- Learning
    - Some variables unobserved, graph is known -> [Expectation Maximization](probabilistic_graphical_models/expectation_maximization.md)
    - All variables observed, graph is unknown [Chow Liu Algorithm]()
  
    
