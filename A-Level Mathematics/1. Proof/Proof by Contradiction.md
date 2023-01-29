In order to prove something by contradiction, you must first make an assumption about the statement, and then attempt to contradict it. This proves that the opposite of your assumption must be true. You must select your assumption such that it will end up proving/disproving the initial statement.

## Example
> Prove that $\sqrt{2}$ is irrational.

> [! Example]
> Prove that $\sqrt{2}$
> 
> Suppose that $\sqrt{2}$ is rational. This means that $\sqrt{2} = \frac{m}{n} \quad m, n \in \mathbb{Z}, \; n \neq 0$.
> 
> It follows that $2m^2 = n^2$, meaning $2 \; \vert \; n^2 \Rightarrow 2 \; \vert \; n$. This means that $n = 2p, \; p \in \mathbb{Z}$
> 
> If we substitute that back into our equation, we get that $2m^2 = 4p^2 \Rightarrow m^2 = 2p^2$, meaning $2 \; \vert \; m^2 \Rightarrow 2 \; \vert \; m$. This means that $m = 2q, \; q \in \mathbb{Z}$
> 
> This in itself is a contradiction, as if $m$ and $n$ are both even, they share a factor of 2 which can be cancelled out in the fraction. This means that $\frac{m}{n} = \frac{p}{q}$, and you can keep applying this method recursively to see that there is always two integers that divide into $\sqrt{2}$ more accurately; this means that the number must be irrational. 

