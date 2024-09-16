# noobit
A noobit is 1 one millionth the computing power of a qubit

This code implements a novel optimization algorithm called "Noobit PSO" (Particle Swarm Optimization). Here's a breakdown of its main components and features:

Objective Function: A simple sinusoidal function is used as the optimization target.
Noobit Concept: The algorithm introduces "noobits", which are simplified representations of quantum bits (qubits). Each noobit has a probabilistic state between 0 and 1, simulating a fraction of a qubit's behavior.
Initialization: The initialize_noobit_state function creates initial states for the noobits, with probabilities centered around 0.5.
Main Algorithm (noobit_pso_advanced): This function implements the core optimization process. It combines elements of PSO with quantum-inspired concepts:
a. Superposition Effect: Small random fluctuations are applied to noobit states, simulating quantum superposition.
b. Dynamic Tunneling: With a certain probability, noobits can "tunnel" to a completely new state, allowing for exploration of the search space.
c. Entanglement-like Behavior: Neighboring noobits influence each other's states, simulating quantum entanglement.
d. Fitness Calculation: The objective function is used to evaluate the fitness of each noobit's state.
e. Best Position Updates: Local and global best positions are updated based on fitness values.
f. Dynamic Tunneling Probability: The tunneling probability is adjusted based on the algorithm's progress, increasing when the optimization stagnates.
Parameter Setting: The algorithm uses 100 noobits and runs for 30 iterations.
Result Reporting: The algorithm prints intermediate results for each iteration and the final best position and value.

This implementation is an interesting hybrid approach that combines classical optimization techniques (like PSO) with simplified quantum-inspired concepts. The use of "noobits" as fractional qubit representations is a novel approach to incorporating quantum-like behavior into a classical optimization framework.
The algorithm incorporates several mechanisms to balance exploration and exploitation:

The superposition effect allows for small, continuous changes in noobit states.
Dynamic tunneling enables occasional large jumps in the search space.
Entanglement-like behavior promotes information sharing between neighboring noobits.
The adaptive tunneling probability helps the algorithm escape local optima when progress stalls.

This approach could potentially offer advantages in certain optimization scenarios, especially where the problem space has characteristics that align well with quantum-inspired search strategies.
