# A-Level Further Core 2
## Polar Coordinates & Equations

The coordinates of P can be written in Cartesian form as $(x,y)$ but can be written as $(r,\theta)$ in polar form where $r$ is the distance from the origin and $\theta$ is the angle of rotation counter-clockwise from the positive $x$-axis.

To convert from polar to Cartesian you can use the following:
- $r \cos\theta = x$
- $r \sin\theta = y$
- $r^2 = x^2 + y^2$
- $\theta = \arctan(\frac{y}{x})$

Polar equations are usually given in the form $r = f(\theta)$ so as $\theta$ varies from 0 to $2\pi$ points are placed around the whole graph varying distance.
## Sketching curves
Common curves are: 
$r = a$, a circle with centre origin radius $a$ 
$\theta = \alpha$, a half line making angle $\alpha$ 
$r = a\theta$, a spiral starting at origin

$r = a(p + q \cos\theta)$, They are called ***Cardioids*** They are defined for all $\theta$ if $p \geq q$ so to make $r>0$ - this can be defined in some contexts but for A-level this is undefined)

Cardioids fall into 2 categories "egg" shaped and those with a "dimple", egg shaped are convex curves, dimples are concave at $\theta = \pi$. They are egg shaped when $p \geq 2q$ and dimple shaped if $q \leq p < 2q$ - This is proved by considering the number of tangents that are perpendicular to the initial line.
## Area enclosed by a Polar Curve
The area enclosed by a polar curve and half lines $\theta = \alpha, \theta = \beta$ where $\theta$ is measured in radians is given as: $$A = \frac{1}{2} \int_{\alpha}^{\beta} r^2 d\theta$$
Very useful trig identities for integration $$\sin^2\theta = \frac{1-\cos 2\theta}{2}\quad\cos^2\theta = \frac{1+\cos 2\theta}{2}$$
## Tangent to polar Curve
You can differentiate parametrically to get:
$$\frac{dy}{dx} = \frac{dy /d\theta}{dx/d\theta}$$

To find a tangent line to the parallel to the initial set: $\displaystyle\frac{dy}{d\theta} = 0$
To find a tangent perpendicular to the initial line set: $\displaystyle\frac{dx}{d\theta} = 0$

---
# Flashcards
## A-Level Further Core 2
#z_Legacy/Maths/A-Levels/Further-Core/Polar-Coordinates,  #Maths/Topics/Polar-Coordinates

How do you convert from polar to Cartesian coordinates?
?
Use these equations:
- $x = r \cos \theta$
- $y = r \sin \theta$
- $r^2 = x^2 + y^2$
- $\theta = \arctan(\frac{y}{x})$      

What polar equation represents a circle with centre at the origin?
?
$r = a$, where $a$ is the radius of the circle.      

What polar equation represents a half-line?
?
$\theta = \alpha$, where $\alpha$ is the angle the line makes with the positive X-axis.  

What polar equation represents a spiral starting at the origin?
?
$r = a\theta$, where $a$ is a constant.      

What is the general form of a cardioid in polar coordinates, when are they *"egg-shaped"* and when does it have a *"dimple"*?
?
$r = a(p + q \cos \theta)$, where $a$ and $q$ are constants, $p \geq q$
Egg-shaped (convex): when $p \geq 2q$
Dimple (concave at $\theta = \pi$): when $q \leq p < 2q$   

How do you find the slope of a tangent line to a polar curve?
?
$$\frac{dy}{dx} = \frac{dy /d\theta}{dx/d\theta}$$  

How do you find a tangent line parallel to the initial line?
?
Set $$\frac{dy}{d\theta} = 0$$ 

How do you find a tangent line perpendicular to the initial line?
?
Set $$\frac{dx}{d\theta} = 0$$    