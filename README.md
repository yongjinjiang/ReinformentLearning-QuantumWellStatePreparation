## About

In quantum physics, tuning a time-dependent term(controlling protocal) in the Hamiltonian of a system to prepare a desired quantum state is an important task in the context of quantum computing and/or quantum information. A simple example is to get a state with nearly 50% probabilties for the ground state and the first excited state in a quantum well, by tuning the strength of a barrier described by Dirac function. This problem is studied recently in the paper "Deep reinforcement learning for robust quantum optimization"(arXiv:1904.04712), in which several different methods are used. Especially, the authors used 
deep Q-learning(DQL) as well as deep deterministic policy gradient(DDPG) algorithms to attack the problem. The protocal obtained by these reinforcement learning approches bear a greatly desired property, i.e., they show robustness with respect to certain geometrical randomness(in the position of the Dirac barrier) of the quantum well. 

 In this repo, the code to solve the eigenstates and useful wave function overlaps of the problem is provided. Besides that, I also worked on the base code of DQL from the first authors' [repo](https://github.com/vegardbs/PhD-research) and chained these two parts together to get an independent repo to solve the problem. 
 
 
 ## Run
   Run Main.ipynb only
