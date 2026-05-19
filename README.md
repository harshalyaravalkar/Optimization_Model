# Optimization_Model

## Company Name
CODTECH IT SOLUTIONS PRIVATE LIMITED

---

## Name
Harshal Laxman Yaravalkar

---

## Intern ID
CTIS8789

---

## Domain
Data Science

---

## Duration
4 Weeks

---

## Mentor
Neela Santhosh Kumar

---

# Factory Profit Optimization using PuLP

## Project Description

This project focuses on solving a business optimization problem using Linear Programming and the PuLP library in Python. The objective of the task was to build an optimization model capable of maximizing company profit while satisfying limited resource constraints.

Optimization techniques are widely used in industries such as manufacturing, logistics, supply chain management, finance, and operations research. Businesses often need to determine the best possible use of limited resources in order to maximize profit or minimize cost. Linear Programming is one of the most commonly used mathematical optimization methods for solving such problems.

For this project, a factory production optimization scenario was considered. The factory manufactures two products:
- Product A
- Product B

Each product requires a certain amount of:
- labor hours
- raw materials

At the same time, each product also generates a specific profit value for the company. Since the available labor and material resources are limited, the challenge was to determine the optimal number of units of each product that should be produced in order to maximize total profit.

The optimization problem was implemented using the PuLP library, which is a popular Python library for Linear Programming and operations research problems.

The first step of the project involved defining the optimization model using `LpProblem`. The objective of the model was set to maximization since the goal was to maximize overall profit.

Next, decision variables were created representing the number of units of Product A and Product B to manufacture. These variables were defined as integer variables because product quantities cannot be fractional in practical manufacturing scenarios.

After defining the decision variables, the objective function was created. The objective function calculates total profit based on the number of units produced for each product and their respective profit values.

The project then implemented multiple constraints representing resource limitations. These constraints ensured that:
- total labor usage does not exceed available labor hours
- total raw material usage does not exceed available material limits

Once the optimization problem was fully defined, the PuLP solver was used to compute the optimal solution. The solver automatically calculated the best production quantities for both products while satisfying all constraints.

The project also included result visualization using Matplotlib. A simple bar chart was created to display the optimal quantities of each product suggested by the optimization model.

This project demonstrates several important concepts related to optimization and operations research, including:
- linear programming
- objective function formulation
- constraint-based optimization
- decision variables
- profit maximization
- business problem solving

The technologies used in this project include:
- Python
- PuLP
- Matplotlib
- Jupyter Notebook

Overall, this project successfully demonstrates how optimization techniques can be used to solve practical business problems and improve operational decision-making using Python.

---

# Project Structure

```bash
CODTECH-Task4-Optimization-Model/
│
├── optimization.ipynb
└── README.md
```

---

# Requirements

```bash
pip install pulp matplotlib jupyter
```

---

# How to Run

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then open and run:

```bash
optimization.ipynb
```

Run all notebook cells to generate the optimization results and visualization.

---

# Optimization Problem

## Products

- Product A
- Product B

---

## Profit Per Unit

| Product | Profit |
|---|---|
| Product A | ₹300 |
| Product B | ₹500 |

---

## Constraints

### Labor Hours Constraint

```text
2A + 4B <= 100
```

### Raw Material Constraint

```text
3A + 2B <= 90
```

---

# Example Output

```text
Status: Optimal

Optimal Product A Units: 16
Optimal Product B Units: 17

Maximum Profit: ₹13300
```

---

# Screenshots

## Optimization Output
<img width="382" height="132" alt="Screenshot 2026-05-20 002900" src="https://github.com/user-attachments/assets/d3a7491a-ac99-44b5-8cb6-8af8aa6b3487" />


---

## Product Quantity Visualization

<img width="705" height="491" alt="Screenshot 2026-05-20 002844" src="https://github.com/user-attachments/assets/0a40e749-8346-4706-89c9-cb4687f500bf" />

---

# Features of the Project

- linear programming implementation
- business optimization modeling
- resource constraint handling
- profit maximization
- optimization visualization
- practical operations research example

---

# Business Applications

Optimization models like this are commonly used in:
- manufacturing industries
- logistics and transportation
- supply chain optimization
- inventory planning
- production scheduling
- resource allocation systems

---

# Future Improvements

Possible future enhancements:
- include additional products
- add transportation and storage costs
- use real-world industrial datasets
- create an interactive optimization dashboard
- add sensitivity analysis and scenario testing
