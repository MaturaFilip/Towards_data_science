Preparation for maturity exam from mathematicator.com

- Assignments was mostly written on paper (not shared)
- For some assignments python was used (shared)



## Main topics

- basics of combinatorics

- basics of probability

- basics of statistics



This document summarise most important things from this topic from [mathematicator](https://mathematicator.com) course. Exercises are not included in this repository (writen in paper)



# Combinatorics

#### Rule of product

Rule of product / multiplication principle = if there are $n$ ways of doing something, and $m$ ways of doing another thing after that, then there are $n \times $m ways to perform both of thse actions 

examples:

- 2 persons, 3 ice cream flavors (banana, apple, orange) - how many pairs I can create?

$$
2 \times 3 = 6
$$



## #### Rule of sum

Addition principle / rule of sum = if there are $n$ choices for one action, and $m$ choices for another action and the ____two actions cannot be done at the same time___, then there are $n+$m ways to choose one of these actions

examples:

- 3 north shops, 2 south shops -> need to decide which shop to visit, because I can't to visit north and south at the same time, so I can choose which schop to visit today

$$
3 + 2 = 5
$$



### Factorials

Are useful when we try to calculate combinations of something. For instance, in how many ways we can order 5 people in line?



$$
5 \times 4 \times 3 \times 2 \times 1 = 120
$$

or we can write it rather like:

$$
5! = 120
$$

Factorial is one-to-one function for $\mathbb{N_0}$ (natural number), so number must be $0,1,2,3,4$ etc...



and because factorial is one-to-one function we can do this:

$$
(x + 2)! = 10!\\[2ex]
x + 2 = 10\\[2ex]
n! = m!\\[2ex]
n = m
$$



#### Partial permutation

- order matter

- without repetition

- For instance we have 5 people and we have to choose 2 people. 1 person will get candy, second milk. How many permutations we have if order matter and no repetition is allowed? 

$$
n = 5\\
k = 2\\[2ex]

\text{We have 5 options for first pick and 4 for second pick}\\[2ex]

5 \times 4 = 20\\[2ex]

\text{so it looks like factorial without tail}\\[2ex]

P(n, k) = \frac{5 \times 4 \times 3 \times 2 \times 1}{3 \times 2 \times 1}\\[2ex]

\text{we get 3 from 5 - 2 so...}\\[2ex]

P(n, k) = \frac{n!}{(n-k)!}\\[2ex]


$$



#### Permutations with repetition

- almost same as previous, but now order matter and repetition allowed

- We have 5 people and we pick 2 persons, both of them get candy and also the same person can get candy twice, so it doesn't matter if the person is pick first or second

$$
n = 5\\
k = 2\\[2ex]

\text{5 options for the firct pick and 5 options for second pick}\\[2ex]

5 \times 5 = 25\\[2ex]
5^2 = 25\\[2ex]
n^k

$$



#### Permutation

- order matter, we always use whole set of $n$

- so the $k = n$

- example: We have 5 dogs and we want to know  in how many ways we can sort them in line

$$
n = 5\\
k = 5\\[2ex]


5 \times 4 \times 3 \times 2 \times 1 = 120\\[2ex]
5! = 120\\[2ex]
P(n) = n!
$$



### Combination

- order doesn't matter

- I will perform partial permutation and then divide it by permutation from $k$

$$
C(n, k) = \binom{n}{k} = \frac{n!}{k! \cdot (n-k)!}


$$

#### Binomial coefficient

- some interestik properties of binomial coefficient

$$
\binom{n}{k}
$$

- we can write it like equation in ombination, but we can leverage this:

$$
\binom{n}{0} = 1\\[2ex]

\binom{n}{1} = n\\[2ex]

\binom{n}{n} = 1\\[2ex]

\binom{n}{k} = \binom{n}{n - k}\\[2ex]


\binom{n}{k} + \binom{n}{k + 1} = \binom{n + 1}{k + 1}\\[2ex]
$$







# Probability
