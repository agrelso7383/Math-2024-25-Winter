

##Equation of a Sphere with Center at \( P = (1, 2, 3) \) and Radius \( r = 3 \)

The general equation of a sphere is:  
\[
(x - x_0)^2 + (y - y_0)^2 + (z - z_0)^2 = r^2
\]

For the sphere with center \( P = (1, 2, 3) \) and radius \( r = 3 \):  
\[
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 9
\]

### Final Equation:  
\[
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 9
\]

![Círculo generado en GeoGebra](circle_geogebra.png)

## Do the Spheres \( x^2 + y^2 + z^2 = 1 \) and \( x^2 + y^2 + z^2 = 2 \) Have Common Points?

- The two spheres have different radii, and their centers are at the origin (\( (0, 0, 0) \)).
- Since their radii differ, they do not intersect.
- **Conclusion**: The spheres have no common points.

---

## Intersection of the Spheres \( x^2 + y^2 + z^2 = 1 \) and \( (x-1)^2 + y^2 + z^2 = 1 \)

### Given Sphere Equations:
1. \( x^2 + y^2 + z^2 = 1 \)  
2. \( (x-1)^2 + y^2 + z^2 = 1 \)

To find the intersection, substitute \( x = \frac{1}{2} \) (the midpoint between the centers) into the first sphere equation:  
\[
x^2 + y^2 + z^2 = 1 \quad \text{where } x = \frac{1}{2}
\]

Simplify:  
\[
\left(\frac{1}{2}\right)^2 + y^2 + z^2 = 1
\]
\[
y^2 + z^2 = \frac{3}{4}
\]

### Final Equation of the Curve:  
\[
x = \frac{1}{2}, \quad y^2 + z^2 = \frac{3}{4}
\]

---

## Equation of the Tangent Plane to the Paraboloid at \( P = (1, 0, 1) \)

### Paraboloid Equation:
\[
z = (x - 1)^2 + y^2 + 1
\]

### Step 1: Compute Partial Derivatives
- \( \frac{\partial z}{\partial x} = 2(x - 1) \)  
- \( \frac{\partial z}{\partial y} = 2y \)

At point \( P = (1, 0, 1) \):  
\[
\frac{\partial z}{\partial x} \bigg|_{(1, 0)} = 2(1 - 1) = 0
\]  
\[
\frac{\partial z}{\partial y} \bigg|_{(1, 0)} = 2(0) = 0
\]

### Step 2: Tangent Plane Equation
The tangent plane at \( P \) is given by:  
\[
z - z_0 = \frac{\partial z}{\partial x} (x - x_0) + \frac{\partial z}{\partial y} (y - y_0)
\]

Substitute \( z_0 = 1 \), \( \frac{\partial z}{\partial x} = 0 \), and \( \frac{\partial z}{\partial y} = 0 \):  
\[
z - 1 = 0(x - 1) + 0(y - 0)
\]

### Final Equation of the Tangent Plane:
\[
z = 1
\]
