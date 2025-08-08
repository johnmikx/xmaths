# **Visualizing and Validating the Fundamental Theorem of Calculus with Python**

An analytical walkthrough of the **Fundamental Theorem of Calculus (FTC)** using computational tools. Through both symbolic and numeric techniques, it validates and visualizes the FTC and provides intuitive insights into how integration and differentiation are inherently connected.

### **Objectives:**
- Demonstrate **FTC1** and **FTC2** computationally.
- Confirm symbolic and numeric integration consistently.
- Show that the derivative of the accumulated area matches the original function $f(x)$.
- Allow user-defined function input to generalize FTC analysis.

### **Part 1 (FTC1):**
If $f$ is continuous on $[a, b]$, then the function:

$$ F(x) = \int_a^x f(t) \ dt $$

is continuous on $[a, b]$ differentiable on $(a, b)$ and:

$$ F'(x) = f(x) $$

### **Part 2 (FTC2):**

If $f$ is continuous on $[a, b]$ and $F$ is any antiderivative of $f$ then:

$$ \int_a^b f(x) \ dx = F(b) - F(a) $$

#### **Key Concepts:**
- **Continuity** ensures no jumps or holes in the function.
- **Integrability** means area under curve exists (all continuous functions are integrable).
- FTC connects **area under a curve** to **antiderivatives**.

***:)***