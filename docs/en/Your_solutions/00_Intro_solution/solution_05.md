```python
import math

magnitude = 15
angle_degrees = 60
angle_radians = math.radians(angle_degrees)

horizontal_component = magnitude * math.cos(angle_radians)
vertical_component = magnitude * math.sin(angle_radians)

print(f"{horizontal_component=}")
print(f"{vertical_component=}")


```

```text
horizontal_component=7.500000000000002
vertical_component=12.990381056766578


```

To calculate the horizontal ($A_x$) and vertical ($A_y$) components of a vector $\vec{A}$ with magnitude $A = 15$ at an angle $\theta = 60^\circ$, we use the following trigonometric relationships:

$$A_x = A \cos(\theta)$$

$$A_y = A \sin(\theta)$$

### 1. Horizontal Component ($A_x$)

$$A_x = 15 \cos(60^\circ)$$


Since $\cos(60^\circ) = 0.5$:


$$A_x = 15 \times 0.5 = 7.5$$

### 2. Vertical Component ($A_y$)

$$A_y = 15 \sin(60^\circ)$$


Since $\sin(60^\circ) = \frac{\sqrt{3}}{2} \approx 0.866$:


$$A_y = 15 \times 0.866 \approx 12.99$$

**Final Result:**

* The horizontal component is $7.5$.
* The vertical component is approximately $12.99$.