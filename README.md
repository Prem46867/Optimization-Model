# Optimization-

Company Name: CodeTech It Solutions

Name : Prem M

Domain : Data Science

Duration : 4 Weeks

Intern ID : CTIS6711

Desprition of the task:

This business problem is a classic example of optimization using Linear Programming, a technique widely used in operations research to make the best possible decision under given constraints. The goal here is to determine how many units of Product A and Product B a manufacturing company should produce in order to maximize profit while staying within the limits of available machine and labor hours.

The problem is formulated mathematically by defining decision variables: x for the number of units of Product A and y for Product B. The objective function, Z = 40x + 30y, represents the total profit, where each unit of Product A contributes ₹40 and each unit of Product B contributes ₹30. The company aims to maximize this profit.

However, production is constrained by limited resources. The first constraint, 2x + y ≤ 100, represents the machine hours limitation. Product A requires 2 machine hours per unit, while Product B requires 1 hour. The second constraint, x + y ≤ 80, represents the labor hours limitation, where both products require 1 labor hour per unit. Additionally, non-negativity constraints ensure that production quantities cannot be negative.

To solve this optimization problem, the script uses PuLP, a powerful Python library designed for linear programming problems. A model is created with the objective of maximization, and decision variables are defined with lower bounds of zero. The objective function and constraints are then added to the model in a straightforward manner.

Once the model is fully defined, the solve() function is called. PuLP internally uses optimization solvers to compute the optimal values of x and y that maximize the objective function while satisfying all constraints. The results are then printed, including the status of the solution, the optimal values of Product A and Product B, and the maximum profit achieved.

The output shows that the optimal production plan is to produce 20 units of Product A and 60 units of Product B. This combination yields a maximum profit of ₹2600. An important observation is that both constraints are fully utilized at this solution. This means that all available machine hours and labor hours are consumed, indicating an efficient allocation of resources with no wastage.

To enhance understanding, the script also uses Matplotlib to visualize the optimal production plan. A bar chart is created showing the number of units produced for each product, providing a clear and intuitive representation of the solution.

From a business perspective, this analysis highlights the importance of optimization techniques in decision-making. Instead of relying on guesswork, the company can use mathematical models to determine the most profitable strategy. It also demonstrates how constraints influence production decisions and how balancing limited resources can lead to maximum efficiency.


In conclusion, this example effectively shows how Linear Programming can be applied to real-world business problems. By leveraging tools like PuLP, organizations can make data-driven decisions, optimize operations, and improve profitability in a systematic and reliable way.

Output of the task

<img width="911" height="687" alt="Image" src="https://github.com/user-attachments/assets/3bc65293-3bf3-4367-b815-fa1277734153" />

<img width="1055" height="697" alt="Image" src="https://github.com/user-attachments/assets/03dd944c-e898-45be-b6f2-6ea310acd6c9" />
