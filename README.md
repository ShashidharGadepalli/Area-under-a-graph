# Area-under-a-graph
A python code that calculates area under a graph using the midpoint theorem:

The mid point Theorem:
This rule designates how the rectangles are made and used in the approximation. Each rectangle out of "N" rectangles has to have an equal width, Δx, but each nth rectangle cannot be the exact same: the varying factor is the height which varies as the function evaluated at a certain point. The midpoint rule gets its name from the fact that you are evaluating the height of each rectangle as f(x_n), where "x_n" is the respective center-point of each rectangle, as apposed to the left or right of the rectangle. Using the midpoint is like implementing an average which will make the approximation more accurate than if you were to use the right or left. The supporting picture for this step summarizes how the midpoint rule is defined mathematically.
![Screenshot 2021-08-10 at 8 18 32 PM](https://user-images.githubusercontent.com/52597557/128888651-09ccc5f1-7c78-4c33-bcea-bcd5419afa59.png)
The code here in this case calculates the integral of a sin function. 
To calculte the integral of some other fucntion we need to change the function name in the return statement.


The n value we take in the beggining is the no of strips we want to divide the graph into.(More the value of n ,more the no of strips so more accurate answer.)
The graph is divided into a large no of rectangles with different lengths but the same width.
Each interval is of the width (b-a)/n
Since the height or the length of each strip varies, we use the mid point of each interval to get a rough length.
Finally we add all these strips which gives a very close answer.

