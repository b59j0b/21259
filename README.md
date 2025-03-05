java c
21-259: Calculus in Three Dimensions 
Lecture #8 
Spring 2025 
Partial Derivatives
Consider the function z = f (x, y) = x2 + 2y2. By fixing y = 2, we focus our attention to all points on the surface where the y-value is 2, shown in both figures. These points form. a curve in space: z = f (x,2) = x2 + 8 which is a function of just one variable. We can take the derivative of z with respect to x along this curve and find equations of tangent lines, etc.
The key notion to extract from this example is: by treating y as constant (it does not vary) we can consider how z changes with respect to x. In a similar fashion, we can hold x constant and consider how z changes with respect to y. This is the underlying principle of partial derivatives. We state the formal, limit–based definition first, then show how to compute these partial derivatives without directly taking limits.

Definition: Let z = f (x, y) be a continuous function on an open set D in R2.
1. The partial derivative of f with respect to x is fx (x, y) = 
2. The partial derivative of f with respect to y is f y (x, y) = 
Alternate notations for fx (x, y) include:

with similar notations for f y (x, y).
Since partial derivatives are defined using the limit definition, all of the standard rules techniques for computing derivatives of single-variable functions apply. Thus all one has to do when finding a partial derivative is treat all other variables as constants.
Example 1. If f (x, y) = x3 + x2y3 −2y2, find fx (2,1) and f y (2,1).
Example 2. If f (x, y) =  find fx and f y .
Example 3. If g (x, y, z) = exy lnz, find gx , gy , and gz .
Example 4. If z is implicitly defined as a function of x and y via the equation x − z = arctan(yz), find 
Example 5. Find fx and f y if f (x, y) = x y.
Just as higher-order derivatives are found for single-variable functions, they can be found for multivariable functions. However, we now have the idea of mixed partials:

Example 6. Compute all second partials of the function f (x, y) = cos(2x2 +3y).
Clairaut’s Theorem: Suppose f is defined on a set D 代 写21-259: Calculus in Three Dimensions Lecture #8 Spring 2025SPSS
代做程序编程语言that contains the point (a,b). If the function fx y and f y x are both continuous on D, then fx y (a,b) = f y x (a,b).
Example 7. If f (r,s,t) = r ln(r s2t3), find fr ss and fr st.
Example 8. How many third-order partial derivatives does a function of two variables have? If all of the partials are continuous everywhere, how many of them are distinct?
Definition: A partial differential equation is an equation relating an unknown function of several variables and some of its partial derivatives.
Example 9. The equation uxx +uy y = 0 is known as Laplace’s equation. Solutions of this equation are known as harmonic functions. Determine if u(x, y) = excos y is a solution of Laplace’s equation.
Tangent Planes and Linear Approximations
Suppose z = f (x, y) has continuous partial derivatives. An equation of the tangent plane to the surface z = f (x, y) at the point P(x0, y0, z0) is
z − z0 = fx (x0, y0)(x − x0)+ f y (x0, y0)(y − y0).

Example 10. Find the equation of the plane tangent to z = y lnx at the point (1,4,0).
Example 11. Find the equation of the plane tangent to z = arctan(x y2) at the point (1,1,π/4).
Definition: The linearization or linear approximation to the function z = f (x, y) at the point (a,b) is given by
f (x, y) ≈ L(x, y) = f (a,b)+ fx (a,b)(x − a)+ f y (a,b)(y −b).
Example 12. Find the linearization of the function  at the point (3,0) and use it to approximate f (3.1,−0.1).
Definition: The differential d z, also known as the total differential, is defined by

It is an estimate of ∆z, the actual change in z, as x changes from x to x +∆x and y changes from y to y + ∆y by taking d x = ∆x and d y = ∆y.
Example 13. Let z = x4e3y. Find d z.

Example 14. A cylindrical steel storage tank is to be built that is 10ft tall and 4ft across in diameter. It is known that the steel will expand/contract with temperature changes; is the overall volume of the tank more sensitive to changes in the diameter or in the height of the tank? What about a tank with a height of 1ft and radius of 5ft?





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
