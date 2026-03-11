```python
import sympy

x, y = sympy.symbols('x y')
eq1 = sympy.Eq(2*x + 3*y, 12)
eq2 = sympy.Eq(x - y, 1)

solution = sympy.solve((eq1, eq2), (x, y))
print(solution)


```

```text
{x: 3, y: 2}


```

To find the values of $x$ and $y$ that satisfy the system of equations:

1. $2x + 3y = 12$
2. $x - y = 1$

### Method 1: Substitution

From equation (2), we can express $x$ in terms of $y$:


$$x = y + 1$$

Now, substitute this expression for $x$ into equation (1):


$$2(y + 1) + 3y = 12$$

Distribute and simplify:


$$2y + 2 + 3y = 12$$

$$5y + 2 = 12$$

$$5y = 10$$

$$y = 2$$

Now substitute $y = 2$ back into the expression for $x$:


$$x = 2 + 1$$

$$x = 3$$

### Method 2: Elimination

Multiply equation (2) by 3 to align the $y$ terms:


$$3(x - y) = 3(1)$$

$$3x - 3y = 3$$

Now, add this to equation (1):


$$(2x + 3y) + (3x - 3y) = 12 + 3$$

$$5x = 15$$

$$x = 3$$

Substitute $x = 3$ into equation (2):


$$3 - y = 1$$

$$y = 2$$

**Solution:**
The values that satisfy both equations are $x = 3$ and $y = 2$.