java c
21-259: Calculus in Three Dimensions 
Lecture #6 
Spring 2025 
Arc Length and Curvature
Definition: The arc length L of the curveC defined by r (t) =­〈f (t), g (t),h(t)〉 for a ≤ t ≤ b is given by

Example 1. Find the length of the arc of the circular helix r (t) = 〈cos t,sint,t〉 from the point (1,0,0) to the point (1,0,2π).
Example 2. Find the length of the arc of r (t) = 〈√2t,et,e−t〉 for 0 ≤ t ≤ 1.
A space curve C can be represented with multiple parametrizations. For example, the two vector functions

represent the same space curve, via the substitution t = eu. It is often useful to parametrize with respect to arc length as arc length arises naturally from the shape of the curve and is independent of coordinate system. This can be accomplished by use of the arc length function for r (t) for a ≤ t ≤ b:

Then we can usually solve for the parameter t as a function of s: t = t(s) and rewrite r (t) = r (t(s)). This way, r (t(1)) is the position vector of the point that is one unit of length along the curve from its starting point.
Example 3. Reparametrize the helix r (t) = 〈cos t,sin t,t〉 with respect to arc length measured from (1,0,0) in the direction of increasing t. Find the position vector of the point on the curve that is 1 unit of length from the initial point.
Example 4. Reparametrize the curve r (t) = 〈t +3,2t −4,2t〉 with respect to arc length measured from the point where t = 3 in the direction of increasing t.
Definitio代 写21-259: Calculus in Three Dimensions Lecture #6 Spring 2025Matlab
代做程序编程语言n: The curvature κ of a curve C is  It is a measure of how quickly the curve changes direction, and it is the magnitude of the rate of change of the unit tangent vector with respect to arc length.

Example 5. Find the curvature of a circle with radius a.
Example 6. Find the curvature of the vector function r (t) =­〈t2,sint − t cos t,cos t + t sint〉, (t > 0).
Theorem: Another formula for computing the curvature is

Example 7. Find the curvature of the vector function r (t) =­〈t,t,1+ t2〉.
Theorem: If y = f (x) is a plane curve (i.e. a curve in R2), then the curvature as a function of x is

Example 8. What is the curvature of f (x) = ex?
Example 9. What is the curvature of f (x) = sin2x?
Definition: The principal unit normal vector N(t) is the unit vector in the direction of the derivative of the unit tangent vector :

The unit vector B(t) = T (t)×N(t) is the binormal vector. The plane determined by N and B at a point P on a curve C is called the normal plane of C at P. The plane determined by T and N is called the osculating plane of C at P. The circle that lies in the osculating plane of C at P, has the same tangent as C at P, and lies on the concave side of C (in the direction of N) is the osculating circle of C at P, and it has a radius of ρ = 1/κ.
Example 10. Find the equations of the normal plane and the osculating plane of the curve r (t) =〈t,t2,t3〉 at the point (1,1,1).





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
