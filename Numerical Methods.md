# A-Level Further Pure
## First order differential equations
Some differential equations can not be solved analytically; however, they can be accurately approximated with Euler's Method:

$$y_{r+1} \approx y_r + h \left.\frac{dy}{dx}\right|_{\displaystyle x_r}$$
$$ r \in \mathbb{N},\space x_r = x_{r-1}+h, \space h \in \mathbb{R}$$

*The way this works is that you are given initial conditions $(x_0, y_0)$. So you can compute $\left.\frac{dy}{dx}\right|_{x_0}$, then you can approximate the coordinates some $h$ away from $x_0$ by using a straight line with gradient $\left.\frac{dy}{dx}\right|_{x_0}$. To get a more accurate approximation, you can calculate the next point with smaller steps $h$. As a result, you have to do more iterations to get a point some distance from $x_0$*

You could also use the **Midpoint Formula**:

$$y_{r+1} \approx y_{r-1} + 2h \left.\frac{dy}{dx}\right|_{x_r}$$

## Second order differential equation
You can extend Euler's method to second order differential equations with:

$$y_{r+1} \approx 2y_r - y_{r-1} + h^2 \left.\frac{d^2y}{dx^2}\right|_{\displaystyle x_r}$$
$$\left.\frac{d^2y}{dx^2}\right|_{\displaystyle x_0} \approx \frac{y_1 - 2y_0 + y_{-1}}{h^2}$$

## Simpson's Rule
You can approximate $\int_a^b g(x) dx$ with the formula:

$$\frac{h}{3}\left(y_0 + 4\sum_{k=1}^{n-1} y_{2k-1} + 2\sum_{k=1}^{n-1} y_{2k} + y_{2n}\right)$$

where $2n$ is the number of strips used to approximate the area and $h$ is the width of each strip.
This formula is derived by using quadratic curves and using the result that area of quadratic curve passing through $(x_0, y_0)$, $(x_0 + h, y_1)$, $(x_0 + 2h, y_2)$ is $\frac{1}{3}h(y_0 + 4y_1 + y_2)$.

Other forms:

$$\frac{1}{3}h(\text{endpoints} + 4 \times \text{odd values} + 2 \times \text{even values})$$

$$\frac{1}{3}h(y_0 + 4(y_1 + y_3 + \ldots + y_{2n-1}) + 2(y_2 + y_4 + \ldots + y_{2n-2}) + y_{2n})$$

This formula approximates the area under the curve by using quadratic curves to fit the function, providing a more accurate estimate than simpler methods like the trapezoidal rule.


# Flashcards

#Maths/Topics/Calculus/Differential-Equations, #z_Legacy/Maths/A-Levels/Further-Pure/Numerical-Methods, #Maths/Topics/Numerical-Methods 

What is the formula for Euler's Method for first-order differential equations?
?
Euler's Method for first-order differential equations is given by:
$$y_{r+1} \approx y_r + h \left.\frac{dy}{dx}\right|_{x_r}$$
where $r \in \mathbb{N}$, $x_r = x_{r-1}+h$, and $h \in \mathbb{R}$. This formula approximates the next point $(x_{r+1}, y_{r+1})$ using the current point $(x_r, y_r)$ and the derivative at that point.  It provides a numerical technique to estimate the value of a function at future points given an initial condition and the derivative of the function.  

How does reducing the step size $h$ affect the accuracy of Euler's Method?
?
Reducing the step size $h$ in Euler's Method generally increases the accuracy of the approximation. Smaller steps lead to more frequent recalculations of the derivative, resulting in a closer approximation to the true solution curve. However, this comes at the cost of requiring more iterations to cover the same distance from the initial point.  

What is the midpoint formula in the context of numerical methods for differential equations? ?
The midpoint formula is an alternative to Euler's Method for approximating solutions to first-order differential equations. It is given by:
$$y_{r+2} \approx y_{r-1} + 2h \left.\frac{dy}{dx}\right|_{x_r}$$


How can Euler's Method be extended to solve second-order differential equations?
?
Euler's Method can be extended to second-order differential equations using the formula:
$$y_{r+1} \approx 2y_r - y_{r-1} + h^2 \left.\frac{d^2y}{dx^2}\right|_{x_r}$$
This extension allows for the approximation of solutions to more complex differential equations involving second derivatives.  

What is the formula for approximating the second derivative at the initial point in numerical methods for second-order differential equations?
?
The second derivative at the initial point can be approximated using the formula:
$$\left.\frac{d^2y}{dx^2}\right|_{x_0} \approx \frac{y_1 - 2y_0 + y_{-1}}{h^2}$$
This approximation is useful when extending Euler's Method to second-order differential equations.  

#z_Legacy/Maths/A-Levels/Further-Pure/Numerical-Methods, #Maths/Topics/Calculus/Integration, #Maths/Topics/Numerical-Methods 

How is Simpson's Rule of approximating $\int_a^b g(x) dx$ derived?
?
Simpson's Rule is derived by using quadratic curves to approximate the function being integrated. The key steps are:
1. Divide the integration interval into an even number of strips (2n).
2. For each pair of adjacent strips, fit a quadratic curve through the three points.
3. Use the result that the area under a quadratic curve passing through $(x_0, y_0)$, $(x_0 + h, y_1)$, and $(x_0 + 2h, y_2)$ is given by: $$\frac{1}{3}h(y_0 + 4y_1 + y_2)$$
4. Sum up these areas for all pairs of strips to get the final formula. 

What is the equation for Simpsons Rule of approximating $\int_a^b g(x) dx$?
?
Simpson's Rule can be expressed in several equivalent forms:
1. Standard formula:
   $$\frac{h}{3}\left(y_0 + 4\sum_{k=1}^{n-1} y_{2k-1} + 2\sum_{k=1}^{n-1} y_{2k} + y_{2n}\right)$$ where:
- $h$ is the width of each strip
- $2n$ is the number of strips used
- $y_k$ represents the function value at the $k$-th point
2. Using endpoints, odd, and even values:
   $$\frac{1}{3}h(\text{endpoints} + 4 \times \text{odd values} + 2 \times \text{even values})$$
3. Expanded sum notation:
   $$\frac{1}{3}h(y_0 + 4(y_1 + y_3 + \ldots + y_{2n-1}) + 2(y_2 + y_4 + \ldots + y_{2n-2}) + y_{2n})$$  


