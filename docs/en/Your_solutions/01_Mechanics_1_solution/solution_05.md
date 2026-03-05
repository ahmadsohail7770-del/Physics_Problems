
# Solution: Variable Velocity

# Step 1 — Given velocity

The velocity is

$$
v(t)=t^2+2t-5
$$

---

# Step 2 — Find acceleration

Acceleration is the derivative of velocity:

$$
a(t)=\frac{dv}{dt}
$$

Differentiate:

$$
a(t)=\frac{d}{dt}(t^2+2t-5)
$$

$$
a(t)=2t+2
$$

Now evaluate at $t=3$:

$$
a(3)=2(3)+2
$$

$$
a(3)=8
$$

So the **acceleration at $t=3$ is**

$$
a(3)=8
$$

---

# Step 3 — Find position function

Since

$$
v(t)=\frac{dx}{dt}
$$

we integrate:

$$
x(t)=\int (t^2+2t-5),dt
$$

Integrating term by term:

$$
x(t)=\frac{t^3}{3}+t^2-5t+C
$$

---

# Step 4 — Use the initial condition

We know

$$
x(0)=4
$$

Substitute $t=0$:

$$
4=\frac{0^3}{3}+0^2-5(0)+C
$$

$$
4=C
$$

Thus the **position function** is

$$
x(t)=\frac{t^3}{3}+t^2-5t+4
$$

---

# Step 5 — Position at $t=3$

Substitute $t=3$:

$$
x(3)=\frac{3^3}{3}+3^2-5(3)+4
$$

Compute each term:

$$
x(3)=\frac{27}{3}+9-15+4
$$

$$
x(3)=9+9-15+4
$$

$$
x(3)=7
$$

---

# Final Results

Position function:

$$
x(t)=\frac{t^3}{3}+t^2-5t+4
$$

Position at $t=3$:

$$
x(3)=7
$$

Acceleration function:

$$
a(t)=2t+2
$$

Acceleration at $t=3$:

$$
a(3)=8
$$

