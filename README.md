# Task-2
Implementation of a quantum circuit that returns |01> and |10> with equal probability (50% for each). 

This python code implements a quantum circuit to return the values of |01> and |10> with equal probability, using Qiskit and IBM Quantum Experience.

This code will satisfy the following requirements: 

- The circuit should consist only of CNOTs, RXs and RYs [The code includes a Haddamard gate but only to parametrize the qubit states]
- Start from all parametric gates being equal to 0 or randomly chosen [This is achieved through the Haddamard Gate]
- You should find the right set of parameters using gradient descent (you can use more advanced optimiziation methods if you like)
- Simulations must be done with sampling (i.e, a limited  number of measurements per iteration) and noise [Sampling was achieved through for loops]
- Compare the results for different numbers of measurements: 1,10, 100 1000 [Diff. measures. achieved by changing the shots value in each for loop]
