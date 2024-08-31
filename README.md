# Solving QUBO problems on real quantum computers

Combinatorial problems, particularly NP-hard problems, present significant challenges for classical computation. Quantum
computers have the potential to solve NP-hard problems more efficiently. In this notebooks, we use real quantum computers
to finding optimal solutions of quadratic unconstrained binary optimization (QUBO) problems. We present the computational results for a QUBO problem with 3 variables, and its extension to 6, 12 and 144 variables. Our findings indicate that the variational quantum eigensolver (VQE) algorithm with the constrained optimization by linear approximation (COBYLA) subroutine can yield optimal, less accurate, or unsatisfactory solutions depending on the problem instance. For all the considered instances of the QUBO problem, an optimal solution was successfully obtained via quantum annealing or hybrid solvers. 


## Accounts

The reader needs to create an account on the following clouds:

 [Dwave Leap](https://cloud.dwavesys.com/leap/login/?next=/leap/)

 [IBM Quantum](https://quantum.ibm.com/)

 [Quafu](https://quafu.baqis.ac.cn/#/home)

and save the api token on the corresponding notebook in order to run them. For Dwave's API token setup see [_Set Up Your Environment_](https://docs.ocean.dwavesys.com/en/latest/overview/install.html).


## Installation

Install requirements locally (ideally, in a virtual environment):

    pip install -r requirements.txt


## License

Released under the Apache License 2.0. See LICENSE file.
