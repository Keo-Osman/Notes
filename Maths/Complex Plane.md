# Definitions
[[Complex Numbers]] can be represented on a cartesian plane *(called the complex plane or an argand diagram)* as a point $(x, y)$ or vector $\begin{pmatrix} x \\ y \end{pmatrix}$ where $z=x+iy$. Therefore the $x$-axis is the real axis and the $y$-axis is the imaginary axis.

---
# A-Level Further Core 1

## Loci
### Circle  $\left|z-z_1\right|=r$
Given $z_1, z_2$,  $|z_2-z_1|$ is the distance between points $z_1, z_2$. So you can replace $z_2$ with the general point $z$ to obtain a locus of points that are all equidistant form $z_1$. Therefore you get a circle centre $z_1$ described by to locus $\left|z-z_1\right|=r$
### Perpendicular Bisector $\left|z-z_1\right|=\left|z-z_2\right|$
Given $z_1, z_2$ the locus $\left|z-z_1\right|=\left|z-z_2\right|$ Is the perpendicular bisector of the line segment connecting $z_1, z_2$
### Half Line $\arg \left(z-z_1\right)=\theta$ 
Given $z_1$ the locus of points described by $\arg \left(z-z_1\right)=\theta$ forms a straight half-line that makes angle $\theta$ with the line extending from $z_1$ that is parallel to the real axis but does not include $z_1$

---
# A-Level Further Pure 2
## Loci

### Circle $|z-z_1| = k|z-z_2|$ 
The locus of points $z$ that satisfy $|z-z_1| = k|z-z_2|, \space k\in \mathbb{R}, k>0, k\neq 1$ is a **circle**.
You can find the equation by splitting $z$ into $x+iy$ then squaring both sides *(which gets rid of modulus and $i$ terms*) and solving from there.
In basic terms it's the locus of points that are $k$ times further from $a$ than they are from $b$.
*When $k=1$ it's a straight line perpendicular bisector which can be thought of as a circle with infinite radius*

### Circle Arc $\arg(\frac{z-z_1}{z-z_2}) = \theta$
The Locus $\displaystyle \arg\left(\frac{z-z_1}{z-z_2}\right) = \theta$ is an arc of a circle with end points $z_1,z_2$. The arc is drawn **anticlockwise** from $z_1$ to $z_2$. You can find the equation of a circle by considering the 2 congruent isosceles triangles formed by $z_1CM$, $z_2CM$ where $C$ is the circle centre and $M$ is the midpoint of the line $z_1z_2$.

## Transformations on the Complex Plane
You can transform loci by mapping the $z$ plane onto a $w$ plane to get $z = x+iy \rightarrow w = u+iv$
- $w = z+a+ib$ represents translation by $\begin{pmatrix} a \\ b \end{pmatrix}$, $a,b \in \mathbb{R}$
- $w = kz$, $k\in \mathbb{R}$ represents enlargement with scale factor $k$ centre $(0,0)$
- $w = iz$ represents anti-clockwise rotation of $\frac{\pi}{2}$ about $(0,0)$
### Möbius transformations
They are transformations in the form $$w = \frac{az+b}{cz+d} \quad a,b,c,d \in \mathbb{C}$$

--- 
# Flashcards

#Maths/A-Level-Further-Core/Complex-Plane, #Maths/Topics/Complex-Numbers  

What does $|z_2-z_1|$ represent on the complex plane?
?
$|z_2-z_1|$ represents the distance between points $z_1$ and $z_2$ on the complex plane. <!--SR:!2024-12-22,4,270--> 

What does the locus of points $|z-z_1|=r$ describe on the complex plane?
?
The locus of points described by $|z-z_1|=r$ forms a circle <!--SR:!2024-12-22,4,270-->

What does the locus of points $|z-z_1|=|z-z_2|$ describe on the complex plane?
?
The locus of points described by $|z-z_1|=|z-z_2|$ is the perpendicular bisector of the line segment connecting $z_1$ and $z_2$. <!--SR:!2024-12-22,4,270--> 

What does the locus of points $\arg(z-z_1)=\theta$ describe on the complex plane?
?
 $\arg \left(z-z_1\right)=\theta$ forms a straight half-line that makes angle $\theta$ with the line extending from $z_1$ that is parallel to the real axis but does not include $z_1$. <!--SR:!2024-12-22,4,270-->

#Maths/A-Level-Further-Pure/Complex-Numbers, #Maths/Topics/Complex-Numbers

What does the locus of points $|z-z_1| = k|z-z_2|$ describe on the complex plane and how do you find it's cartesian equation?
?
The locus is a circle. This equation represents points that are $k$ times further from $a$ than they are from $b$. To find the cartesian equation split $z$ into $x+iy$, then square both sides to eliminate the modulus and $i$ terms and solve the resulting equation. 

What does the locus $\displaystyle \arg\left(\frac{z-z_1}{z-z_2}\right) = \theta$ represent and how do you find it's equation?
?
The Locus $\displaystyle \arg\left(\frac{z-z_1}{z-z_2}\right) = \theta$ is an arc of a circle with end points $z_1,z_2$. The arc is drawn **anticlockwise** from $z_1$ to $z_2$. You can find the equation of a circle by considering the 2 congruent isosceles triangles formed by $z_1CM$, $z_2CM$ where $C$ is the circle centre and $M$ is the midpoint of the line $z_1z_2$.

What does the transformation $w = z+a+ib$ represent?
?
This represents a translation by the vector $\begin{pmatrix} a \\ b \end{pmatrix}$, where $a,b \in \mathbb{R}$

What does the transformation $w = kz$, $k\in \mathbb{R}$ represent?
?
This represents an enlargement with scale factor $k$ centred at the origin $(0,0)$

What does the transformation $w = iz$ represent?
?
This represents an anti-clockwise rotation of $\frac{\pi}{2}$ (90 degrees) about the origin $(0,0)$

What is a Möbius transformation?
?
A Möbius transformation is a transformation of the form $\displaystyle w = \frac{az+b}{cz+d}$, where $a,b,c,d \in \mathbb{C}$.
