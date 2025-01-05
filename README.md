# Binary-search

This is a situation where we are looking for the index of a target value in a sorted list. If until now we thought of going through and comparing element by element O(n), now we are thinking of a middle position, dividing the list in half O(log n), and checking which side of the list the target value is. Thus, the complexity is reduced by a factor of 2, since each time we give up half of the list.

Since we are searching within a list and dividing it in half, this means that we are creating a range, that is, working with limits, and therefore we are required to define a lower limit position and an upper limit position. In practice, it is the updating of the limits that divides the table in half with each iteration. This dynamic definition also prevents us from defining new lists with an absolute lower and upper limit.

In order to track the progress of the code, we need to make a tracking table in which we write in columns the iterations, variables - lower limit, upper limit, middle value position, comparison to the target variable, and updating limits.
