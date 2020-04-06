# Classification-Tree
A basic decision tree algorithm.

For simpler understanding, the code can be broken down into:

1. CART on the Bank Note dataset
2. Load a CSV file
3. Convert string column to float
4. Split a dataset into k folds
5. Calculate accuracy percentage
6. Evaluate an algorithm using a cross validation split
7. Split a dataset based on an attribute and an attribute value
8. Calculate the Gini index for a split dataset

  8.1. count all samples at split point
  8.2. sum weighted Gini index for each group
  8.3. avoid divide by zero
  8.4. score the group based on the score for each class
  8.5. weight the group score by its relative size
9. Elect the best split point for a dataset
10. Create a terminal node value
11. Create child splits for a node or make terminal

	11.1 check for a no split
	11.2 check for max depth
	11.3 process left child
	11.4 process right child
12. Build a decision tree
13. Make a prediction with a decision tree

# Classification and Regression Tree Algorithm

A. Test CART on Bank Note dataset

B. Load and prepare data

C. Convert string attributes to integers

D. Evaluate algorithm


