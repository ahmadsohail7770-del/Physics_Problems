```python
import numpy as np

# Define vectors
a = np.array([2, 1, -3])
b = np.array([4, -2, 1])

# a) Magnitudes
mag_a = np.linalg.norm(a)
mag_b = np.linalg.norm(b)

# b) Dot product
dot_product = np.dot(a, b)

# c) Cross product
cross_product = np.cross(a, b)

# d) Angle
cos_theta = dot_product / (mag_a * mag_b)
angle_rad = np.arccos(cos_theta)
angle_deg = np.degrees(angle_rad)

print(f"{mag_a=}")
print(f"{mag_b=}")
print(f"{dot_product=}")
print(f"{cross_product=}")
print(f"{angle_rad=}")
print(f"{angle_deg=}")



```

```text
mag_a=3.7416573867739413
mag_b=4.58257569495584
dot_product=3
cross_product=array([ -5, -14,  -8])
angle_rad=1.3949275767021716
angle_deg=79.92346287144585


```

To calculate the properties of the vectors $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$, we follow these steps:

### a) Magnitude of each vector

The magnitude of a vector $\vec{v} = [x, y, z]$ is given by $|\vec{v}| = \sqrt{x^2 + y^2 + z^2}$.

* **Magnitude of $\vec{a}$:**

$$|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14} \approx 3.742$$


* **Magnitude of $\vec{b}$:**

$$|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21} \approx 4.583$$



### b) Dot Product $\vec{a} \cdot \vec{b}$

The dot product is the sum of the products of the corresponding components:


$$\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1)$$

$$\vec{a} \cdot \vec{b} = 8 - 2 - 3 = 3$$

### c) Cross Product $\vec{a} \times \vec{b}$

The cross product is calculated using the determinant of a $3 \times 3$ matrix:


$$\vec{a} \times \vec{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}$$

$$\vec{a} \times \vec{b} = \mathbf{i}(1(1) - (-3)(-2)) - \mathbf{j}(2(1) - (-3)(4)) + \mathbf{k}(2(-2) - 1(4))$$

$$\vec{a} \times \vec{b} = \mathbf{i}(1 - 6) - \mathbf{j}(2 + 12) + \mathbf{k}(-4 - 4)$$

$$\vec{a} \times \vec{b} = [-5, -14, -8]$$

### d) Angle between vectors $\vec{a}$ and $\vec{b}$

The angle $\theta$ is found using the dot product formula: $\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos \theta$.


$$\cos \theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|} = \frac{3}{\sqrt{14}\sqrt{21}} = \frac{3}{\sqrt{294}}$$

$$\cos \theta \approx \frac{3}{17.146} \approx 0.175$$

$$\theta = \arccos(0.175) \approx 1.395 \text{ radians or } 79.92^\circ$$