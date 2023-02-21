**Mid-term March 8th**
**HW2 - Due March 2nd**

**Late Policy**
15 min - 24 - 5%
24 Hrs - 48 Hrs - 10%




## Definition 3.4.1 Joint /Bivariate Distribution
Let $X$ & $Y$ be RV $S$. The joint distribution or bivariate distribution of  $X$ & $Y$ is the collection of all probabilities of the form $Pr(X,Y)$ $\in$  C, $\forall$ C of pairs of $\mathbb{R}$  s.t. ${(X,Y) \in C}$ is an event



### Def 3.4.2 Discrete Joint Distribution

Let $X$ & $Y$ Be RVs and consider the ordered pair $(X,Y)$. If there are finitely or countable many different possible values $(x, y)$ for the pair $(X, Y)$ then we say that $X$ & $Y$ have a discrete joint distribution.


**3.4.1:** If 2 RVs $X$ & $Y$ have discrete distributions then $X$ & $Y$ together have a discrete joint distribution .

### Def 3.4.3. Joint probability function
The joint probability function of $X$ & $Y$ is defined as the function $f$ s.t. $\forall$ points $(x,y)$ in the xy-plane
$$ f(x,y) = Pr(X = x \space and \space Y = y) $$ 

### Example: Picking Balls
Suppose 3 balls are randomly selected from an urn containing 3 red, 4 white, and 4 blue balls.
X = # of red balls chosen
Y = # of white balls chosen

$$p(i,j) = Pr{X=i, Y =j}$$ 

*Below Explained: Because we know that 0 red, 0 white, but that 3 balls in total were chosen, then it must be that 3 blue.
$$Pr(0,0) = \pmatrix{5 \\ 3} / \pmatrix{12 \\ 3} = \frac{10}{220} = \frac{1}{22} = \space _5C_3/_{12}C_3$$




(0,2) = $\pmatrix{4 \\ 2}$ $\pmatrix{5 \\ 1}$ /$\pmatrix{12 \\ 3}$ = $\frac{30}{220}$

(1,1) = $\pmatrix{3 \\ 1}$$\pmatrix{4\\1}$ $\pmatrix{5 \\ 1}$ /$\pmatrix{12 \\ 3}$  = $\frac{60}{220}$


### Def 3.4.4 Continuous Joint Distribution, Joint Pdf

Two RVs $X$ and $Y$ have a continuous joint distribution. If there exists a nonnegative function $f$ defined over the entire xy-plane s.t. for every subset C of the plane 
$$ Pr[(X, Y) \in C] = \int \int f(x,y)dx dy $$ 

### Theorem 3.4.3 
A joint pdf must satisfy the following:

$$ f(x,y) \geq for - \infty < x < \infty \space \& -  \infty < y < \infty  $$
$$ \& $$
$$ \int_{-\infty}^{\infty} \int_{-\infty}^{\infty} f(x,y)dxdy = 1$$





### Def 3.4.5
Let $X$ & $Y$ be RVs s.t. $X$ is discrete and $Y$ is continuous 




If $X$ is discrete with possible values $x_1, x_2 , …$ and $Y$ is the continuous RV $f(x,y) \geq 0 \space \forall x_i, y$ 
$$ \int_{-\infty}^{\infty} \sum_{i=1}^{\infty} f(x_i,y)dy = 1$$


### Example: Clinical Trial 
Each patient is given a drug and followed to see if they relapse. Let $X$ to be an indicator variable $X = 1$  &rarr; no relapse $X =  0$


$$ p^x *(1-p)^{1-x} $$