# Equation Solver
## About
This project is a Python-based equation solver designed to run inside Jupyter Notebooks, including those within Visual Studio Code. It utilizes SymPy, a Python library for symbolic mathematics, to parse, simplify, and solve equations. The solver supports rendering of both the input equations and the solutions in LaTeX format, providing a visually appealing presentation of mathematical expressions.
## Features
- Automatic detection of symbols in equations.
- Simplification and solving of equations.
- Rendering of equations and solutions in LaTeX format directly within Jupyter Notebook outputs.
## Installation
To use this equation solver, you need to have Python installed on your system along with Jupyter Notebook (or JupyterLab) and the Visual Studio Code Jupyter extension if you prefer using VS Code. Follow these steps to set up the environment:

1. **Install Python**: Download and install Python from [python.org](www.python.org).
2. **Install Jupyter Notebook**: Run the following command in your terminal:

```bash
pip install notebook
```

3. **Install SymPy and IPython**: The project depends on SymPy for mathematical operations and LaTeX rendering. Install it using pip:

```bash
pip install sympy ipython
```
4. **(Optional) VS Code**: If you're using Visual Studio Code, ensure you have the Python and Jupyter extensions installed.

## Usage
After installing the necessary dependencies, you can run the solver by including it in a Jupyter Notebook cell. Here's a quick start guide:

Use the solve_equation function to solve an equation, for example:

```
equation_str = "(4*x - 40) / 2 = (3*x**2 - 90) * 4"
results = solve_equation(equation_str)
```
To display equations and solutions in LaTeX format, use **display(Latex(your_latex_string))** as demonstrated.
## License
This project is licensed under the GNU General Public License v3.0. For more details, see the LICENSE file in the project repository.
## Acknowledgments
- SymPy: For providing the powerful symbolic mathematics library.
- Jupyter Notebook: For enabling an interactive environment for code execution.
- IPython: For the display utilities that facilitate the rendering of equations and solutions in LaTeX within Jupyter Notebooks.