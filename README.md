# Numerical-Methods-and-Computational-Technology
The method is also called the interval halving method, the binary search method or the dichotomy method. This method is used to find root of an equation in a given interval that is value of ‘x’ for which f(x) = 0 .
Given a function f(x) on floating number x and two numbers ‘a’ and ‘b’ such that f(a)*f(b) < 0 and f(x) is continuous in [a, b]. Here f(x) represents algebraic or transcendental equation. Find root of function in interval [a, b] (Or find a value of x such that f(x) is 0)
Assumptions: 
 

    f(x) is a continuous function in interval [a, b]
    f(a) * f(b) < 0

Steps: 
 

   1. Find middle point c= (a + b)/2 .
   2. If f(c) == 0, then c is the root of the solution.
   3. Else f(c) != 0
       3.a If value f(a)*f(c) < 0 then root lies between a and c. So we recur for a and c
       3.b Else If f(b)*f(c) < 0 then root lies between b and c. So we recur b and c.
       3.c Else given function doesn’t follow one of assumptions.
