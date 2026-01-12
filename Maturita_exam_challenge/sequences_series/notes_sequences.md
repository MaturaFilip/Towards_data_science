# Sequences

posloupnost není řada

posloupnost = uspořádaná množina prvků

# Arithmetic sequence

$$
1, 2,3,4,5,6...
$$

- Imagine that $1$ is $a_1$, $2$ is $a_2$ and so on

- We can guess _$d$_ = $common\ difference$ (difference between $a_1$, $a_2$ and so on)

- or we can derive $d$, $a_1$, or $a_n$ from formulas:

$$
a_{n+1} = n + d\\[2ex]


a_{17} = a_{16} + d
$$

- but we can calculate any $a_n$ from $a_1$

$$
a_n = a_1 + (n - 1) \cdot d
$$

- we can generalized the formula

$$
a_{n} = a_{s} + (n - s) \cdot d
$$

#### Sum of the arithmetic sequence (series)

$$
1+2+3+4+5...+100 = ?\\[2ex]


1+100 = 101\\[2ex]
2+99 = 101\\[2ex]


50 \times 101 = 5050\\[2ex]


S_n = \frac{a_1 + a_n}{2} \cdot n
$$

# Geometric sequence

- in arithmetic sequence, the difference between $a_1$, $a_2$ and $a_3$ were same. In geometric sequences, they don't

- $q$ is always same! If not, so it's not geometric sequence!

$$
a_{n+1} = a_n \cdot q\\[2ex]

q = \frac{a_n + 1}{a_n}
$$

- $q$ is common ratio
  
  - $q \neq 0,1$
  
  - $a \neq 0$ 

$$
a_n = a_s \cdot q^{n - s}\\[2ex]


a_n = a_1 \cdot q^{n - 1}


$$

## Finite sum of a geometric series

$$
S_n = a_1 \cdot \frac{1 -q^n}{1-q}\\[2ex]

or\\[2ex]


S_n = \frac{a_1 \cdot (1 -q^n)}{1-q}
$$

## Infinite sum of a geometric series

- conditions:

$$
-1 < q < 1\\[2ex]
|q| < 1\\[2ex]


if |q| < 1, n-> \infty, q^n -> 0\\[2ex]


S_n = a_1 \cdot \frac{1 -q^n}{1-q}
$$

- but if $n$ goes to infinity and $q^n$ goes close to 0 -> $q^n$ goes close to 0, so it's $1 - 0$ which is $1$ and $a_1 \cdot 1 = a_1$, so final formula:

$$
S_n = \frac{a_1}{1-q}
$$

# System of equations

## Arithmetic system of equations
