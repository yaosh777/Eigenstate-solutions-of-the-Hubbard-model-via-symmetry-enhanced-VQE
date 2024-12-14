# Eigenstate solutions of the Hubbard model via symmetry-enhanced variational quantum eigensolver
Open the derivation details, source code of the simulation program, and data generated by running the program in the paper.

&#8226; The derivation details can be found in the LyX (version 2.3.6.1) file located in the "Encoding and Initial states" folder. For more information about LyX, see http://www.lyx.org/.

&#8226; The code for the simulation program is located in the "Simulation program code" folder. It is written in Python (version 3.9.19) and saved in Jupyter Notebook (version 7.0.8). The encoding of the operators and the construction of the quantum circuits are done using paddle-quantum (version 2.4.0). The implementation of the classical optimization algorithm uses paddlepaddle (CPU version, version 2.3.0). For more information about paddle-quantum and paddlepaddle, see https://github.com/PaddlePaddle/Quantum and https://github.com/PaddlePaddle/Paddle, respectively.

&#8226; The data generated by the program is located in the "Data" folder. The txt files whose filenames contain 'parameters' provide the parameter settings for each process. The folder also includes .npy files, which are used in NumPy to store array data. These files store the parameters of the quantum circuits obtained after each optimization process, although this data is not used in the paper.

&#8226; The code for data processing and plotting (matplotlib: version 3.9.2) can be found in the "Data processing code" folder. To obtain the pdf-format images used in the paper, each part of the program must be run to completion.

&#8226; The eigenstates of the operators for the Fermi-Hubbard model with two and four lattice sites, obtained using classical methods (matrix form and classical algorithms for eigenvalues and eigenstates), can be found in the "Eigenstates_Operators_Classic" folder.

&#8226; Other Python library version information: numpy: 1.23.0, scipy: 1.13.1. The CPU used is: 12th Gen Intel(R) Core(TM) i9-12900HX.
