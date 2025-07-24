# OPTIMIZATION-MODEL

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : JOSHUA ATULYA LAKRA

*INTERN ID* : CT08DG1187

*DOMAIN* : DATA SCIENCE

*DURATION* : 8 WEEKS

*MENTOR* : Neela Santhosh

*Description* :

Task 4 involves solving a linear programming (LP) problem using the PuLP library in Python. Linear programming is a mathematical technique used to optimize a linear objective function, subject to linear equality and inequality constraints. This is widely used in supply chain, finance, manufacturing, and transportation.

The business problem here is a product mix optimization: a company makes two products — Product A and Product B. Each product earns a specific profit but consumes limited resources like labor and materials. The objective is to determine how many units of each product to produce to maximize profit without exceeding available resources.

The LP model is formulated as:

Objective function: Maximize 40x + 30y (x = units of A, y = units of B)

Constraints:

2x + y ≤ 100 (labor)

3x + 2y ≤ 80 (material)

x, y ≥ 0 (non-negativity)

Using PuLP:

We define the problem as a maximization.

We declare x and y as decision variables.

We set the objective and constraints using Python expressions.

We solve the model and print the results.

The output gives the optimal number of units to produce and the maximum profit. This solution can be visualized using Matplotlib to show the feasible region and optimal point.

Additionally, the notebook includes insights:

Whether constraints are tight (fully used)

How much more profit could be made with more resources

How sensitive the solution is to changes in profit or availability

This task bridges business understanding with mathematical modeling. It teaches how to turn vague business goals into structured optimization problems — a highly valued skill in industries like operations, logistics, and finance.


*Output* :
<img width="718" height="576" alt="Image" src="https://github.com/user-attachments/assets/ab5c9db7-ba2a-4ad6-8b7b-d9ef50153978" />
<img width="407" height="116" alt="Image" src="https://github.com/user-attachments/assets/e1977916-5d3a-4cbe-be8a-67afb12a5179" />
