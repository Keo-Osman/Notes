
# A-Level Further Pure 1
## Leibnitz's Theorem and nth Derivatives
For $y=uv$

$$
\frac{d^n y}{dx^n} = \sum_{k=0}^n \binom{n}{k} \frac{d^k u}{dx^k} \frac{d^{n-k} v}{dx^{n-k}}
$$

(This can be proved with induction with repeated differentiation)
## L'Hôpital's Rule
If either:
- $\displaystyle \lim_{x \to a} f(x) = \lim_{x \to a} g(x) = 0$
- $\displaystyle \lim_{x \to a} f(x) = \pm \infty$ & $\displaystyle \lim_{x \to a} g(x) = \pm \infty$
Then:
$$
\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{f'(x)}{g'(x)} \quad \text{(provided that } \lim_{x \to a} \frac{f(x)}{g(x)} \text{ exists)}
$$
You can also use the following rule in conjunction to evaluate more limits:
- If $\displaystyle \lim_{x \to a} f(x)$ exists, then $\displaystyle \lim_{x \to a} e^{f(x)} = e^{\left( \displaystyle \lim_{x \to a} f(x)\right)}$


# Flashcards
#Maths/Topics/Differentiation, #Maths/A-Level-Further-Pure/Methods-In-Calculus

What is Leibnitz's Theorem for the nth derivative of a product of two functions $y=UV$?
?
Leibnitz's Theorem states that for $y=UV$, the nth derivative is given by:
$$\frac{d^n y}{dx^n} = \sum_{k=0}^n \binom{n}{k} \frac{d^k U}{dx^k} \frac{d^{n-k} V}{dx^{n-k}}$$
This formula allows us to calculate higher-order derivatives of product functions. 

How can Leibnitz's Theorem be proved?
?
Leibnitz's Theorem can be proved using mathematical induction. The proof would involve showing that the formula holds for the base case (usually n=1) and then demonstrating that if it holds for n, it also holds for n+1. 

#Maths/Topics/Limits, #Maths/A-Level-Further-Pure/Methods-In-Calculus

What does L'Hôpital's Rule state?
?
L'Hôpital's Rule states that under certain conditions:
$$\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{f'(x)}{g'(x)}$$
provided that the limit of the ratio of derivatives exists.
L'Hôpital's Rule can be applied under two conditions:
1. When $\lim_{x \to a} f(x) = \lim_{x \to a} g(x) = 0$ (0/0 form)
2. When $\lim_{x \to a} f(x) = \pm \infty$ & $\lim_{x \to a} g(x) = \pm \infty$ ($\infty/\infty$ form) 

What additional rule can be used in conjunction with L'Hôpital's Rule to evaluate more complex limits?
?
The rule states that if $\lim_{x \to a} f(x)$ exists, then:
$$ \displaystyle \lim_{x \to a} e^{f(x)} = e^{\left(\displaystyle \lim_{x \to a } f(x)\right)}$$
This rule can be useful when dealing with exponential functions in limit calculations. 
