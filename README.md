java c
21-259: Calculus in Three Dimensions 
Lecture #3 
Spring 2025 
Planes
The “direction” of a plane in R3is somewhat more difficult to describe than the direction of a line in R3. In fact, at first glance, it seems like there are two directions for a plane. Thus, the idea of using a point in the plane and a single vector that lies in the plane is insufficient for describing it completely. However, since a plane really spans two directions, and there are only three independent directions in R3, a single vector can be used to describe a plane.
Definition: A vector n is a normal vector to a plane if it is orthogonal to all vectors that lie in the plane.

Examining the figure on the left, we see that a normal vector n must satisfy the relationship n · (r − r 0) = 0 where r 0 is the position vector of a given point (x0, y0, z0) on the plane and r = 〈x, y, z〉 is the position vector of any other point (x, y, z) on the plane. If we write n = 〈a,b,c〉, then we have
n ·(r −r 0) = 〈a,b,c〉· (〈x, y, z〉 − 〈x0, y0, z0〉)
                                = a(x − x0)+b(y − y0)+c(z − z0) = 0.
This gives us two ways of representing the plane:
Vector Equation: n ·(r −r 0) = 0
Scalar Equation: a(x − x0)+b(y − y0)+c(z − z0) = 0
The scalar equation is also known as the point-normal form. of the equation of a plane. The scalar equation is what we most commonly use to represent a plane. In fact, any single linear equation in x, y, and z, such as 3x − y + 2z = 4, represents a plane in R3. If you are given a scalar equation, it is very easy to spot the normal vector, as all you need to do is look at the coefficients of the variables. Also note that if n is normal to a plane, then so is −n, or any other nonzero scalar multiple of n.
Example 1. Find the scalar equation of the plane passing through the point (3,−1,7) with normal vector n = 〈4,2,−5〉.
Example 2. Determine if the planes 3x −4y +5z = 0 and −6x +8y −10z = 4 are parallel.
Example: Can a plane contain skew lines?

Now, sometimes you are not given a point on the plane and its normal vector. Nevertheless, with enough information you can find a point and normal and find the equation of the plane.
— If you are given a point in the plane and two vectors v 1 and v 2 that lie in the plane (are parallel to the plane), then a normal vector can be found by computing v 1 × v 2.
— If you are given two points P1 and P2 and a single vector v in the plane, then you can find another vector in the plane by finding the vector from P1 to P2, provided it is not parallel to v, and then find the normal using the cross product.
— If you are given three noncollinear points in the plane, you can find two nonparallel vectors in the plane, and then find the normal using the cross product.
Example 3. Find an equation of the plane that contains the point (2,0,3) and the line x = −1+ t, y = t, z = −4+2t.
Example 4. Find an equation of the plane tha代 写21-259: Calculus in Three Dimensions Lecture #3 Spring 2025Web
代做程序编程语言t contains the line x = −2+3t, y = 4+2t, z = 3− t and is perpendicular to the plane x −2y + z = 5.
Example: Is it possible to find the equation of a plane if you know the symmetric equations of two intersecting lines that lie in the plane? How would you find the plane equation?

Two planes in R3are either parallel, or they intersect in a line. If they are parallel, then their normal vectors are also parallel, so the equations of the plans can be written as ax +by +cz = d1 and ax +by + cz = d2. If they intersect, then their normal vectors (call them n1 and n2) will have an angle θ between them where 0 ≤ θ ≤ π/2. Then, since the angle between n1 and n2 is the same as the angle between the two planes, we have that the acute angle between two planes satisfies

But what about the line of intersection L? How can we find it? Recall that we need a point on the line and a direction vector v. One of the things you can see in the figure on the above right is that the direction vector v of the line must lie in both planes. So we know that v must be orthogonal to n1 and n2. To find a point on the line L, we know that the point must be on both planes. We also know that the line must pass through at least one of the coordinate planes x = 0, y = 0, or z = 0.
A direction vector of the line of intersection of the planes with normal vectors n1 and n2 is given by v = n1×n2. A point on the line can be found by setting one of the variables in the plane equations to 0 and solving both equations for the remaining variables.
Example 5. Find the line of intersection of the planes 2x −4y +4z = 6 and 6x +2y −3z = 4.
With a working knowledge of planes, several distance problems can be addressed:
— Find the distance between a point and a plane.
— Find the distance between two parallel planes.
— Find the distance between two skew lines.
All of these problems actually reduce to the first one - finding the distance from a point to a plane. For example, to find the distance between two parallel planes, you can just take a point in one plane and find how far that point is from the other plane. To find the distance between skew lines, find parallel planes that contain the two lines (if they are skew, then this is possible).

Looking at the figure on the right, if Q(x1, y1, z1) is any point in the plane, and r is the vector , then the distance from the point P to the plane is the (absolute value of the) scalar projection of r onto the normal vector n. Now we know that n = 〈a,b,c〉 and r = 〈x0 − x1, y0 − y1, z0 − z1〉, and that

The distance D from the point P(x0, y0, z0) to the plane ax +by +cx +d = 0 is

Example: If two lines are skew, how can you find two parallel planes containing those lines?
Example 6. Find the distance between the parallel planes 10x +2y −2z = 5 and 5x + y − z = 1.
Example 7. Find the distance between the skew lines




         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
