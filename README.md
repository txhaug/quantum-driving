# Fully-programmable universal quantum computer with a one-dimensional quantum system
Companion code for
"Fully-programmable universal quantum computer with a one-dimensional quantum system" (VM Bastidas, T Haug, C Gravel, LC Kwek, WJ Munro, K Nemoto) arXiv:2009.00823

https://arxiv.org/abs/2009.00823

Create arbitrary effective Hamiltonians by driving a one-dimensional quantum system in time.
A restricted quantum system (e.g. a one-dimensional chain with nearest-neighbor interation) can nativly realise only a restricted Hamiltonian.
This program allows this system to realise arbitrary Hamiltonians by driving the system in time, e.g. by varying its local potential.
The driving protocol is optimised to realise the desired effective Hamiltonian which describes the dynamics of one driving period.

Driving protocols found by optimisation with GRAPE and qutip.

Prerequisits:

NOTE: Requires older version of qutip, namely <=4.7.5, which has dependencies on older versions of numyp and scipy.
To install, make clean python environment and install packages as:
pip install numpy==1.26.4
pip install scipy==1.12.0
pip install qutip==4.7.5



