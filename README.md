# Water-Jug-problem
### Water Jug problem using BFS
<hr>

You are given an m liter jug and a n liter jug. Both the jugs are initially empty. The jugs don’t have markings to allow measuring smaller quantities. You have to use the jugs to measure d liters of water where d is less than n. 

(X, Y) corresponds to a state where X refers to the amount of water in Jug1 and Y refers to the amount of water in Jug2 
Determine the path from the initial state (xi, yi) to the final state (xf, yf), where (xi, yi) is (0, 0) which indicates both Jugs are initially empty and (xf, yf) indicates a state which could be (0, d) or (d, 0).

The operations you can perform are: 
> Empty a Jug, (X, Y)->(0, Y) Empty Jug 1
> Fill a Jug, (0, 0)->(X, 0) Fill Jug 1
> Pour water from one jug to the other until one of the jugs is either empty or full, (X, Y) -> (X-d, Y+d)
