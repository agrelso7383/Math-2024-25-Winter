## Equation of a Plane Through Points A(1,2,3), B(3,4,5), and C(2,1,4)

We are given three points in 3D space: 
- Point A at coordinates \( (1, 2, 3) \)
- Point B at coordinates \( (3, 4, 5) \)
- Point C at coordinates \( (2, 1, 4) \)

The equation of a plane is given by:

\[
ax + by + cz + d = 0
\]

To find the equation of the plane, we first calculate two vectors from these points: 
- Vector \( \mathbf{AB} = \mathbf{B} - \mathbf{A} = [3 - 1, 4 - 2, 5 - 3] = [2, 2, 2] \)
- Vector \( \mathbf{AC} = \mathbf{C} - \mathbf{A} = [2 - 1, 1 - 2, 4 - 3] = [1, -1, 1] \)

Next, we compute the cross product of vectors \( \mathbf{AB} \) and \( \mathbf{AC} \) to get the normal vector to the plane:

\[
\mathbf{n} = \mathbf{AB} \times \mathbf{AC} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 2 & 2 \\ 1 & -1 & 1 \end{vmatrix} = [4, -4, -4]
\]

The normal vector \( \mathbf{n} = [4, -4, -4] \) is used to define the plane equation. We substitute the coordinates of point A into the equation to find \( d \), the constant term:

\[
4(1) - 4(2) - 4(3) + d = 0 \quad \Rightarrow \quad 4 - 8 - 12 + d = 0 \quad \Rightarrow \quad d = 16
\]

Thus, the equation of the plane becomes:

\[
4x - 4y - 4z + 16 = 0 \quad \Rightarrow \quad x - y - z + 4 = 0
\]

## Equation of a Plane Parallel to Another Plane

We are given a plane with the equation:

\[
2x + 3y + 4z = 5
\]

We need to find the equation of a plane that passes through point A(1, 2, 3) and is parallel to this given plane. 

The key idea is that the normal vector of the new plane will be the same as that of the given plane, since parallel planes share the same normal vector. The normal vector is \( \mathbf{n} = [2, 3, 4] \).

The equation of the new plane will be of the form:

\[
2x + 3y + 4z + d = 0
\]

We substitute the coordinates of point A into this equation and solve for \( d \):

\[
2(1) + 3(2) + 4(3) + d = 0 \quad \Rightarrow \quad 2 + 6 + 12 + d = 0 \quad \Rightarrow \quad d = -20
\]

Thus, the equation of the new plane is:

\[
2x + 3y + 4z - 20 = 0
\]

## Equation of a Plane Perpendicular to a Given Normal Vector

In this case, we are given a normal vector \( \mathbf{n} = [2, 3, 4] \) and point A(1, 2, 3). 

The equation of the plane passing through point A and perpendicular to this normal vector is:

\[
2x + 3y + 4z + d = 0
\]

We substitute the coordinates of point A into the equation to solve for \( d \):

\[
2(1) + 3(2) + 4(3) + d = 0 \quad \Rightarrow \quad 2 + 6 + 12 + d = 0 \quad \Rightarrow \quad d = -20
\]

Thus, the equation of the plane is:

\[
2x + 3y + 4z - 20 = 0
\]

## Line of Intersection Between Two Planes

We are given two planes with the following equations:

\[
2x + 3y + 4z = 5
\]
\[
3x + 4y + 2z = 6
\]

The line of intersection of these two planes is the set of points that satisfy both equations. To find the line, we calculate the direction vector by taking the cross product of the normal vectors of the two planes:

\[
\mathbf{n_1} = [2, 3, 4], \quad \mathbf{n_2} = [3, 4, 2]
\]

The direction vector \( \mathbf{d} = \mathbf{n_1} \times \mathbf{n_2} = [2, 3, 4] \times [3, 4, 2] = [-4, 8, -4] \).

Next, we substitute \( z = 0 \) into both plane equations to solve for \( x \) and \( y \):

\[
2x + 3y + 4(0) = 5 \quad \Rightarrow \quad 2x + 3y = 5
\]
\[
3x + 4y + 2(0) = 6 \quad \Rightarrow \quad 3x + 4y = 6
\]

Solving this system of equations, we get the point \( (x, y, z) = (1, 1, 0) \).

Thus, the parametric equation of the line is:

\[
x = 1 - 4t, \quad y = 1 + 8t, \quad z = -4t
\]

## Equation of a Plane Parallel to Two Vectors

We are given two vectors \( \mathbf{v_1} = [1, 0, 1] \) and \( \mathbf{v_2} = [0, 1, -1] \), and point A(1, 2, 3). The equation of the plane passing through point A and parallel to both vectors is:

\[
n_1(x - x_0) + n_2(y - y_0) + n_3(z - z_0) = 0
\]

First, we compute the normal vector to the plane by taking the cross product of \( \mathbf{v_1} \) and \( \mathbf{v_2} \):

\[
\mathbf{n} = \mathbf{v_1} \times \mathbf{v_2} = [1, 0, 1] \times [0, 1, -1] = [-1, 1, 1]
\]

Then, we substitute the coordinates of point A into the equation to find \( d \):

\[
-1(1 - 1) + 1(2 - 2) + 1(3 - 3) = 0 \quad \Rightarrow \quad d = 0
\]

Thus, the equation of the plane is:

\[
-x + y + z = 0 \quad \Rightarrow \quad x - y - z = 0
\]

## Parallel and Perpendicular Planes

We are given the plane:

\[
2x + 3y + 4z = 5
\]

To find a parallel plane, we simply use the same normal vector \( \mathbf{n} = [2, 3, 4] \) and choose any constant \( n \). For example, with \( n = 10 \), the equation of the parallel plane is:

\[
2x + 3y + 4z = 10
\]

For a perpendicular plane, we select a vector \( \mathbf{v} = [2, 3, 4] \) and solve for the equation using the condition that the dot product of the normal vectors equals zero. The equation of the perpendicular plane is:

\[
x + y + z = 0
\]

## Distance from a Point to a Plane

We are given point A(1, 2, 3) and the plane equation:

\[
2x + 3y + 4z = 5
\]

The distance \( D \) from a point \( (x_1, y_1, z_1) \) to the plane \( ax + by + cz + d = 0 \) is given by the formula:

\[
D = \frac{|ax_1 + by_1 + cz_1 + d|}{\sqrt{a^2 + b^2 + c^2}}
\]

Substituting the values of point A and the plane equation:

\[
D = \frac{|2(1) + 3(2) + 4(3) - 5|}{\sqrt{2^2 + 3^2 + 4^2}} = \frac{|2 + 6 + 12 - 5|}{\sqrt{4 + 9 + 16}} = \frac{|15|}{5} = 3
\]

Thus, the distance from point A to the plane is 3 units.

## Equation of the Plane Intersecting the Axes

We are given three points where the plane intersects the coordinate axes: A(2, 0, 0), B(0, 3, 0), and C(0, 0, 4).

To find the equation of the plane, we first calculate the vectors \( \mathbf{AB} \) and \( \mathbf{AC} \). The normal vector to the plane is the cross product of these two vectors:

\[
\mathbf{AB} = [-2, 3, 0], \quad \mathbf{AC} = [-2, 0, 4]
\]

\[
\mathbf{n} = \mathbf{AB} \times \mathbf{AC} = \begin{vmatrix} \mathbf{i} & \mathbf

## Angle Between Two Planes

We are given two planes:

\[
x + y + z = 1 \quad \text{and} \quad x = 0
\]

The angle \( \theta \) between two planes is determined by the angle between their normal vectors. The normal vector to the first plane \( x + y + z = 1 \) is \( \mathbf{n_1} = [1, 1, 1] \), and the normal vector to the second plane \( x = 0 \) is \( \mathbf{n_2} = [1, 0, 0] \).

We compute the cosine of the angle using the formula:

\[
\cos(\theta) = \frac{\mathbf{n_1} \cdot \mathbf{n_2}}{|\mathbf{n_1}| |\mathbf{n_2}|}
\]

First, compute the dot product \( \mathbf{n_1} \cdot \mathbf{n_2} \):

\[
\mathbf{n_1} \cdot \mathbf{n_2} = (1)(1) + (1)(0) + (1)(0) = 1
\]

Now compute the magnitudes of \( \mathbf{n_1} \) and \( \mathbf{n_2} \):

\[
|\mathbf{n_1}| = \sqrt{1^2 + 1^2 + 1^2} = \sqrt{3}
\]
\[
|\mathbf{n_2}| = \sqrt{1^2 + 0^2 + 0^2} = 1
\]

Now, substitute into the formula for \( \cos(\theta) \):

\[
\cos(\theta) = \frac{1}{\sqrt{3} \times 1} = \frac{1}{\sqrt{3}}
\]

Thus,

\[
\theta = \cos^{-1}\left(\frac{1}{\sqrt{3}}\right) \approx 54.74^\circ
\]

Therefore, the angle between the two planes is approximately \( 54.74^\circ \).

## Perpendicular Vector to a Plane

Given the plane equation:

\[
x + y + z = 1
\]

The normal vector to this plane is \( \mathbf{n} = [1, 1, 1] \), which is also the vector perpendicular to the plane. This vector defines the direction perpendicular to every point on the plane.