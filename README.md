# OneShotML
This project is for my one-shot learning algorithm. Designed for my computer architecture class, this project was one of my first major projects using the C language.

Here's the overview:
-train.txt is the training data set. This contains a table of a list of attributes where the price of houses with those attributes is known
-We use this train.txt to train our one-shot ML algorithm to predict the housing prices of data.txt
-Solution.txt shows the expected result that we should see after running the one-shot algorithm

Now, how does it actually work?
-We store the training data in a matrix
-We then Gauss-Jordan elimination for finding inverses
-We also have methods for finding the transpose of a matrix, as well as the inverse
-In addition, we have cross product as well
-The final formula for the price is W = (Xtransposed X)^−1Xtransposed Y, 
-Essentially, what we are finding is the cross product of X and X transposed, taking the inverse, and crossing it with X transposed, and then , where Y is our solution vector
