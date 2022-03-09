# Random Problems and Monte Carlo
Assignment 1: (from Project 10.1 of the textbook) Simulate 1D random walks. Construct a program that calculates individual path of a single walker as well as the averages $\left<x(n)\right>$ and $\left<x^2(n)\right>$ for $N$ walkers as a function of step number $n$. 
 * Write a standalone subroutine `walknsteps()` as the workhorse. It should be similar to the function of the same name in Program 10.1. The function should assume artibrary step size $l$ and probability $p$. At each step, draw a random number. If it is less than $p$, the walk is to the right, otherwise it is to the left. The main program should call `walknsteps` $N$ times for a given maximum step number $n_{max}$.
* Compute the averages $\left<x(n)\right>$ and $\left<x^2(n)\right>$ after $N$ walks
* Assume unit step size, $l=1$, and choose $n_{max}=50$ and $N=100$. Vary $p$ values, for example $0.2$, $0.5$, $0.9$, etc. Predict and sketch $\left<x(n)\right>$ and $\left<x^2(n)\right>$ in each case. Plot the results

Assignment 2: (from Project 10.2 of the textbook) Let us investigate Brownian motion in this project. 
* 
