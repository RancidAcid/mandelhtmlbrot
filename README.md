# mandelhtmlbrot
Mandelbrot in html
The Mandelbrot set is a famous mathematical fractal discovered by Benoit Mandelbrot. It's defined in the complex plane by a simple iterative equation:

Z(n+1) = Z(n)² + C

Where Z and C are complex numbers. Z starts at 0, and C is the current point we're testing.

For each point C in the complex plane:
- We repeatedly apply the formula Z = Z² + C
- If the magnitude of Z stays below 2 after many iterations, the point is in the set (colored black)
- If Z eventually exceeds 2, the point is not in the set (colored based on how quickly it escapes)
