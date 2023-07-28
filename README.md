# Integration-Techniques
Introductory project using Matplotlib and Numpy to showcase different integration techniques in a Jupyter Notebook.

## How to Navigate:
- All the code for this project is on `integration.ipynb`
  - To properly visualize the Jupyter Notebook, you may need to run all cells twice so that the graphs appear properly formatted.

## Post-Completion Comments:
- Challenges:
  - Visualizing Integration with Matplotlib: Matplotlib is primarily meant for data analysis rather than math visualation; however, I found ways to overcome these hurdles by establishing `fig` and `ax` as global variables that define a base chart that other functions can edit, using `ax.bar()` (which is meant for bar graphs) for riemann sum blocks, and utilizing `ax.fill_between()` (which is meant for stackplots) for trapezoidal sum trapezoids.
- Enjoyed:
  - Mathematics: I got to code and visualize different integration techniques that I once learned in class.
  - Using new technologies: For this project, numerous technologies were used in addition to Python...
    - Matplotlib helped visualize the techniques,
    - Numpy simplified the math calculations,
    - Latex constructed the math formulas,
    - and Jupyter Notebook organized the code and graphs.
- For Future Projects:
  - Future projects in visualizing mathematics could cover other integration techniques (like Simpson's Rule), differentiation, and/or estimation techniques with geometric elements (like the method of exhaustion for pi).
  - A symbolic approach to integration could provide a general method of identifying and solving improper integrals.
