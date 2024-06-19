**NEAT ALGORITHM**

In our project, we have applied a variant of Genetic Algorithms (GAs) known as NeuroEvolution
of Augmenting Topologies (NEAT) to evolve the behavior of an AI agent to play a game effec-
tively. NEAT is an innovative algorithm that combines the principles of neuroevolution with a unique
approach to evolving both the weights and structure of neural networks.
The NEAT algorithm begins with a population of simple neural networks, where each network
represents a potential solution to the problem. These networks are then evaluated based on their
performance in the given task (in our case, playing the game). The algorithm employs three key
techniques:
1. Tracking Genes through Historical Markings: Each gene (representing a connection or
node in the neural network) is assigned a unique historical marking. This allows NEAT to
efficiently match up genes during crossover between different topologies, ensuring that the con-
nectivity patterns are preserved.
2. Protecting Structural Innovation through Speciation: NEAT employs a speciation mech-
anism that separates the population into species based on the similarity of their topologies. This
protects innovative solutions from being immediately discarded, allowing them to potentially
further evolve and optimize.
3. Incrementally Growing from Minimal Structure: The algorithm starts with a minimal
neural network structure and incrementally adds complexity through mutations that introduce
new nodes and connections. This allows for an efficient exploration of the search space while
avoiding the potential bloat associated with starting with overly complex structures.

By leveraging these techniques, NEAT is capable of evolving both the weights and topologies
of neural networks simultaneously, making it well-suited for problems where the optimal network
structure is not known a priori. In our project, we utilized NEAT to evolve the neural network
controlling the behavior of the AI agent, allowing it to adapt and improve its gameplay strategy
through successive generations of evolution.

## Contributors

Aman Vaibhav Jha

Ammar Ahmad

Akash Sinha
