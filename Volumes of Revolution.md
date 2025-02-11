# A-Level Further Core 1 
## Volume of Revolution
In regular integration of a function $f(x)$ you obtain the area under by considering smaller rectangles with height and width $dx$ so the approximate area is $\sum f(x)dx$ as $dx \rightarrow 0$ this is written as $\int f(x)dx$

For a Volume of Revolution you do the same however the areas are small cylindrical volumes. These volume is $\pi r^2h$ in this case $f(x)$ is the radius and we consider $h$ (the width in the case) going to zero so the approximate area $\sum f(x)^2\pi dx$ as $dx \rightarrow 0$. The exact volume is written as $$\pi \int_a^b f(x)^2dx$$

You can do the same thing for a volume of revolution around the y axis by rearranging to get $x = f(y)$ then the volume will be $$\pi \int_a^b{ f(y)^2dy}$$Keep in mind that $a$ and $b$ are values of $y$ and that the radius of the volume is from the $y$ axis going across parallel to the $x$ axis until the curve.

---
# A-Level Further Core 2
## Volume of Parametric Revolution
For a parametric equation defined $y = g(t), x = f(t)$ you can find the volumes of revolution with the following formulae:

**About the x axis** $$\pi \int_{t=q}^{t=p} g(t)^2 \frac{dy}{dt} dt$$
**About the y axis** $$\pi \int_{t=q}^{t=p} f(t)^2 \frac{dx}{dt} dt$$

---
# Flashcards
## A-Level Further Core 1
#z_Legacy/Maths/A-Levels/Further-Core/Volume-of-Revolution

What is the volume of $f(x)$ rotated $2\pi$ radians about the $x$ axis?
?
$$\pi \int_a^b f(x)^2dx$$    

What is the volume of $f(x)$ rotated $2\pi$ radians about the $y$ axis?
?
Rearrange $f(x)$ to get $x = f(y)$
$$\pi \int_a^b{ f(y)^2dy}$$  

---
## A-Level Further Core 2 

What is the volume of $y = g(t), x = f(t)$ rotated about the $x$ axis?
?
$$\pi \int_{t=q}^{t=p} g(t)^2 \frac{dy}{dt} dt$$   

What is the volume of $y = g(t), x = f(t)$ rotated about the $y$ axis?
?
$$\pi \int_{t=q}^{t=p} f(t)^2 \frac{dx}{dt} dt$$ 