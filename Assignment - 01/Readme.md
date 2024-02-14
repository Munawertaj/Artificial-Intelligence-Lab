# Mathematical Functions Program

This Python program calculates and displays values of 'y' for various mathematical functions with 'x' as an independent variable having values [-10, 10, step_size = 0.1].

## Functions Implemented

1. **Linear Function**
   - Formula: y = wx + b
   - Parameters: 'w' (slope), 'b' (intercept)

2. **Quadratic Function**
   - Formula: y = x^2

3. **Sigmoid Function**
   - Formula: y = 1 / (1 + e^(-x))

4. **Hyperbolic Tangent Function**
   - Formula: y = (e^x - e^(-x)) / (e^x + e^(-x))

5. **Composite Function 1**
   - Formula: y = g(f(x))
   - Where u = f(x) = wx + b and g(u) = 1 / (1 + e^(-u))

6. **Composite Function 2**
   - Formula: y = g(f(x))
   - Where f(x) = wx + b, u = f(x), and g(u) = (e^u - e^(-u)) / (e^u + e^(-u))

7. **Composite Function 3**
   - Formula: y = g3(f3(v))
   - Where f3(v) = w3y1 + w4y2 + b, w = f3(v), and g3(w) = 1 / (1 + e^(-w))
     - y1 = g1(f1(x)) where f1(x) = w1x + b1, u1 = f1(x), and g1(u1) = 1 / (1 + e^(-u1))
     - y2 = g2(f2(x)) where f2(x) = w2x + b2, u2 = f2(x), and g2(u2) = 1 / (1 + e^(-u2))