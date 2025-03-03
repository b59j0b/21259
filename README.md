java c
21-259: Calculus in Three Dimensions 
Lecture #4 
Spring 2025 
Cylinders and Quadric Surfaces
Definition: A cylinder is a surface that consists of all lines (called rulings) that are parallel to a given line and pass through a given plane curve.
A quadric surface is the graph of a second-degree equation in three variables x, y, and z. The most general such equation is
Ax2 +B y2 +C z2 +Dx y +E yz +F xz +G x + H y + I z + J = 0.
By translation and rotation (i.e., change of variables) any quadric surface can be written as on of the two standard forms
Ax2 +B y2 +C z2 + J = 0            or            Ax2 +B y2 + I z = 0.
Some examples of cylinders: 


Some examples of quadric surfaces: 


We can use traces to help us sketch cylinders and quadric surfaces. We find traces by setting one of the variables equal to a constant and then drawing the resulting plane curve, keeping in mind the plane where the curve lies. Below are traces of the surface z = y2 − x2:

Example 1. Classify the quadric surface x2 +2z2 −6x − y +10 = 0.
Example 2. Reduce the equation 4y2+z2−x−16y−4z+20 = 0 to one of the standard forms and classify the surface.
Example 3. place the letter of the correct equation next to each plot.

Cylindrical and Spherical Coordinates 
In many situations, it is physically or mathematically advantageous to describe a point or region in space with a different coordinate system. One such coordinate system for a point P(x, y, z) in R3is constructed on the following three pieces of information:
— r : the (nonnegative) distance between the origin and the projection of P into the x y-plane (x, y)r,
— θ: the angle between the positive x-axis and the line segment from the origin to the point (x, y)r, and
— z: the height of the point above the x y-plane (the z in P(x, y, z)r ).
These three coordinates form. the cylindrical coordinate system and a point is represented by the triple (r,θ, z)c . Cylindrical coordinates are essentially the polar coordinate system for R2together with a Cartesian coordinate for z. We will use the subscript. c to denote cylindrical coordinates (even in 2-D where they are polar coordinates).

Note that r itself is a nonnegative distance - it cannot be negative. The quantity −r can be interpreted as the distance from the origin at the angle of θ +π. Recall that代 写21-259: Calculus in Three Dimensions Lecture #4 Spring 2025
代做程序编程语言
sin(θ +π) = −sinθ                   cos(θ +π) = −cosθ

While θ is meaningful for any real number, is it also common to restrict 0 ≤ θ ≤ 2π. If r ≥ 0 and 0 ≤ θ < 2π, then every point in R3 other than the origin has a unique set of cylindrical coordinates.
Example 4. Convert the following Cartesian coordinates to cylindrical coordinates (using a positive r ):
a) (−1,√3,√3)r
b) (−2,−2,−1)r
Example 5. Convert the following cylindrical coordinates to Cartesian coordinates:
a) (2,π/3,−1)c
b) (1,−π/4,4)c
Example 6. Describe (in words) the surface in R3that is given by the following cylindrical equations:
a) r = 2
b) θ = π/6
c) z = 4−r2
Spherical Coordinates 
Spherical coordinates are much like polar coordinates for the x y-plane combined with polar coordinates for the θz-plane. The three components of the system are:
— ρ: the distance between the origin and P (ρ > 0),
— θ: the angle between the positive x-axis and the line segment from the origin to the point (x, y,0)r, and
— φ: the angle between the z-axis and the line segment from the origin to the point (x, y, z)r.
These three coordinates form. the Spherical coordinate system and a point is represented by the triple (ρ,θ,φ)s. We will use the subscript. s to indicate that a point is written in spherical coordinates.

Much like the case with cylindrical coordinates, we commonly restrict ρ ≥ 0 and 0 ≤ θ ≤ 2π. The convention for φ is to restrict it to values between 0 and π.
Example 7. Convert the following Cartesian coordinates to spherical coordinates:
a) (1,−√3,2√3)r
b) (−1,1,√6)r
Example 8. Convert the following spherical coordinates to Cartesian coordinates:
a) (1,π,π/2)s
b) (4,3π/4,π/3)s
Example: If a point satisfies x > 0, y < 0, and z < 0, what can you say about θ and φ?
The spherical coordinate system represents several geometric objects with very simple formulas. For example, ρ = 2 represents the sphere centered at the origin with radius 2. θ = π/4 represents the halfplane that contains the line y = x and is bounded by the z-axis. The equation φ = π/4 represents the top half of the cone z2 = x2 + y2.
Example 9. Describe (in words) the surface in R3that is given by the following spherical equations:
a) ρ = sinφsinθ
b) ρ2(sin2φsin2θ +cos2φ) = 9







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
