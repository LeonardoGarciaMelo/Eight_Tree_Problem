#Eight_Tree_Problem

The Eight Tree problem, is a problem proposed to the second year of computer engineering at #FIAP in 2024, in the Quantum Computing Class, by Henrique Apocalypse.

This problem basically asks for us to create a function in python that creates a quantum Circuit with Qiskit and, through the manipulation of this circuit, the funcion will count the number of tree sets, where: 1 represents a tree, 0 represents something different from a tree and the input will be a python list with length of 8.

The function will return 1 if the number of sets are odd and 0 if it's even.

The list will be the parameter of the function and the 0 and 1 presents in this list will be applied in the Qbit of the Quantum Circuit, so We are gonna have 8 input Qbits and one last Qbit that will be the Qbit measuring the output of the funcion(that is 1 or 0)

The CX gates and CXX gates are quantum gates used do manipulate the information and, this way, the last Qbit will return 0 or 1.

Examples:

Input:

[0,1,1,0,1,0,0,1]

Output:

-1

or

Input:

[1,1,1,0,1,1,1,1]

Output:

-0
