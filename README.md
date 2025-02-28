java c
21-259: Calculus in Three Dimensions 
Lecture #1
Spring 2025
Three-dimensional Coordinate Systems
Definition: The Cartesian product of a set X and a set Y is the set of all ordered pairs (a,b) with a ∈ X and b ∈ Y , i.e.,
X × Y = {(a,b) | a ∈ X and b ∈ Y}.
We have that (a,b) = (c,d) if and only if a = c and b = d. The Cartesian product of a set X with itself is often written as X2. The Cartesian product of the sets X1,X2,...,Xn is the set
X1 × X2 ×··· × Xn = {(a1,a2,...,an) | ai ∈ Xi, 1 ≤ i ≤ n}.
The elements (a1,a2,...,an) are called n-tuples.
We use R2and R3to represent the set of all ordered pairs and triples in two and three dimensional phys-ical space, respectively. We often use (x, y, z) to represent the coordinate axes in R3. The coordinate planes are shown on the left below, while the eight octants that comprise R3are show in the two right figures.

In Cartesian coordinates, a point P(a,b,c) in R3is represented sim-ply by its values along each of the coordinate axes. The Cartesian coordinate system is also called the rectangular coordinate system. The projection of the point P(a,b,c) onto the x y-plane is the point (a,b) in R2.

The distance between two points P1(x1, y1, z1) and P2(x2, y2, z2) is given by the formula

Example: Determine if the following points lie on a straight line:
P(0,−5,5),       Q(1,−2,4),       R(3,4,2)
The equation of a sphere with center (h,k,l) and radius ρ is
(x −h)2 +(y −k)2 +(z −l)2 = ρ2.
Example: Show that the equation x2 + y2 + z2 + 8x − 6y + 2z + 17 = 0 represents a sphere, and find its center and radius.
Example: Find an equation of the sphere with center (1,−4,3) and radius 5. What is the intersection of this sphere with the xz-plane?
Vectors 
Definition: A vector is a quantity that has both magnitude and direction. Geometrically a vector is usually represented with an arrow. A (real) vector with n components is an element of the set Rn. Vectors are typically represented using Cartesian coordinates. A scalar is an element of R (i.e., a scalar is a real number).
Notation: We typically use boldface letters (v) or an arrow above a symbol (v) to denote vectors. Any two points in Rncan be used to define a vector. A vector v = 〈v1, v2,..., vn〉 is determined by its com-ponents v1, v2,..., vn.
— If P(x1, y1, z1) and Q(x2, y2, z2) are two points in R3, then the vector  is given by
〈x2 − x1, y2 − y1, z2 − z1〉.
In this case v represents the displacement from point P to point Q.
— Two vectors u and v in Rnare equal if and only if ui = vifor all i = 1,...,n.
— Vectors are independent of position - this means that two vector with the same components are equal, regardless of where they may be situated in space.
Definition: The magnitude or length of a vector v is denoted by |v| and is given by

Example 1. Find the magnitude of the vector v = 〈−2,4,1〉.
The zero vector 0 = 〈0,0,...,0〉 is the only vector with a magnitude of 0.
Scalar Multiplication of a Vector: Let v = 〈v1, v2,..., vn〉 be a vector and let a be a scalar. The scalar multiple av is given by
av = 〈av1,av2,...,avn〉.
If v is any vector and a is any scalar, then |av| = |a||v|. Two vectors are parallel if they are scalar multiples of each other.
Vector Addition: Let u = 〈u1,u2,...,un〉 and v = 〈v1, v2,..., vn〉 be vectors. The sum of u and v is given by
u + v = 〈u1 + v1,u2 + v2,...,un + vn〉.
Example 2. Let u = 〈4,2〉 and v = 〈−1,−3〉. Compute and draw the vector u + v in the x y-plane.

Definition: Let v 1,v 2,...,vm be vectors and let a1,a2,...,am be scalars. The expression
a1v 1 + a2v 2 +··· + amvm
is a linear combination of the vi and the ai.
Definition: A unit vector is a vector with magnitude 1. For any vector v, the vector |v|/v is a unit vector in the same direction as v.
Example 3. Given u = 〈2,0,−1〉, v = 〈1,1,1〉, and w = 〈4,2,3〉, find a unit vector in the same direction as v −2u +w.
Definition: 
The standard basis vectors (or elementary basis vectors) are given by
ı = 〈1,0,0〉
ȷ = 〈0,1,0〉
k = 〈0,0,1〉
Any vector v in R3can be written as a linear combination of the standard basis vectors:
v = 〈a1,a2,a3〉 = a1ı + a2 ȷ + a3k.

The components of a vector v in R3are sometimes denoted using a subscript. that represents the vari-able of the direction: v = 〈vx , vy , vz〉. The standard basis vectors give us a way to express any vector as a linear combination of unit vectors.
Properties of Vectors: Let u,v, and w be vectors and let a and b be scalars. Then we have
1. u + v = v +u                                                        (commutativity of +)
2. u +(v +w) = (u + v)+w                           (associativity of +)
3. u +0 = u                                                                    (additive identity)
4. u +(−u) = 0                                                            (additive inverse)
5. a(u + v) = au + av                                           (left distribution of scalar multiplication)
6. (a +b)u = au +bu                                               (right distribution of scalar multiplication)
7. a(bu) = (ab)u                                                            (associativity of scalar multiplication)
8. 1u = u                                                                代 写21-259: Calculus in Three Dimensions Lecture #1 Spring 2025R
代做程序编程语言                (scalar multiplication identity)
Definition: Let P(x, y, z) be a point in R3. Then the vector v = xı+y ȷ+zk = 〈x, y, z〉is the position vector of P.
Vectors can be used to represent forces acting on an object (particle, rigid body, etc.). When multiple forces act on an ob-ject, the net force or resultant force is the sum of all forces acting on the object. An object that is being acted upon by the forces v 1,v 2,...,v N is said to be in static equilibrium if the net force is zero, i.e., if


Example 4. A 100-lb weight hangs from two wires as shown in the figure. Find the tensions (forces) T 1 and T 2 in both wires and their magnitudes.



The velocity of an object is a quantity that is often represented by a vector. If the velocity of an object is given by the vector v, then |v| is the speed of the object.
The resultant concept can also be applied to objects in motion. For example, consider a plane flying with velocity v through a wind that has a velocity w. Then the true course or track of the plane is the direction of the resultant v +w. The ground speed of the plane is the magnitude of the resultant.
The Dot Product 
Definition: Let u = 〈u1,u2,...,un〉 and v = 〈v1, v2,..., vn〉 be vectors in Rn. The dot product of u and v is the scalar quantity

Example 5. Compute the following dot products:
a) (ı + ȷ +k)·(ı −2ȷ +2k)
b) ı · ȷ
c) 〈4,−3,1〉· 〈2,2,−2〉
d) 〈1,2,3〉· 〈−1,−2,−3〉
e) 〈1,2,3〉· 〈1,2,3〉
The dot product can be given in terms of the angle θ between two nonzero vectors:
u · v = |u||v|cosθ
Example 6. Since we know −1 ≤ cosθ ≤ 1, what does that say about the dot product of u and v?

— If u and v are unit vectors, u · v = cosθ.
— u ·u = |u||u|cos0 = |u|2so |u| = √u ·u.
— cosθ = |u||v|/u · v so θ = cos−1 (|u| v|/u· v).
Example 7. Find the angle between the vectors u = √3ı − ȷ and v = −ı + √3ȷ.
Example 8. What is the dot product of two vectors that form. a right angle?
Definition: The vectors u and v are orthogonal if and only if u · v = 0.
Properties of the Dot Product: Let u, v, and w be vectors in Rnand let a ∈ R. Then we have:
1. u · v = v ·u                                                                       (commutativity of ·)
2. a(u · v) = (au)· v = u ·(av)                           (associativity of scalar multiplication)
3. u ·0 = 0                                                                                (orthogonality of 0)
4. u ·(v +w) = u · v +u ·w                                    (distributivity of ·)
Example 9. If u is orthogonal to v, what is |u + v|2?
Example 10. Is the expression u ·(v ·w) meaningful? Why or why not? Is the dot product associative?
Definition: The direction angles α, β, and γ of a vector v in R3are the angles between v and ı, ȷ, and k, respectively. The direction cosines are the cosines of the angles α, β, and γ.

The direction cosines are easy to calculate. For example, we have
cos α = |v||ı|/v ·ı = |v|/v1. 
This means we can write v as
v = 〈v1, v2, v3〉 = 〈|v|cosα,|v|cosβ,|v|cosγ〉.
Thus we have v = |v|〈cosα,cosβ,cosγ〉.
Example 11. What is a reasonable range of values that the angles α,β,γ can take on?
The dot product can be used to determine how much of a given vector lies in the same direction as another vector. This is known as the projection of a vector onto another.
Definition: The scalar projection (or component) of u along v is the signed magnitude of the component of u in the direction of v:

The vector projection of u onto v is the component of u along v times the unit vector in the direction of v:


Example 12. What is the projection of a vector onto itself?
Example 13. Find the component and vector projection of u = 〈3,6,−2〉 onto v = 〈1,2,3〉.
Using the vector projection, we can decompose u into a sum of a vector parallel to v and a vector orthogonal to v:

Example 14. Write the vector u = 〈2,−1,4〉 as the sum of a vector parallel to v = 〈2,0,1〉 and a vector orthogonal to v.
As the dot product gives a quantification of how much of a given vector lies in the direction of another, it is useful in several applications. A classic example of this is the physical concept of work.
Definition: Work is the result of the application of a force F across a displacement d.
When the force and displacement have the same direction, the work is simply the product of the mag-nitudes, W = |F||d|. However, if the force is applied at a direction that is not the same as d, then a vector projection is used to compute the amount of work done. In this case, the work done is given by the dot product W = F ·d.
In the figure on the right, a force in the direction of F is applied to at the upper left corner of a rect-angular object. The force moves the object across a frictionless surface a displacement d. The work done by this action is given by
W = F ·d = |F||d|cosθ.

Example 15. How much work is performed by pulling an object 50ft across a horizontal (frictionless) floor with a constant force of 50lb at an angle of 30◦above the horizontal? If instead the 50lb force was being applied horizontally (i.e., if the force was parallel to the floor), how far would the same amount of work move the object?





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
