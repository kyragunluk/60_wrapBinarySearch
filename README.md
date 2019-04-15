What is meant by count = log2n ?  Answer in 1–2 sentences .
ycount = log2n means that 2^count = n, or the power that 2 needs to be raised to in order to get n, is count.

What does its graph look like?
say x = n
and y = count
Its graph looks like the graph of y = 2^x, reflected over the line y=x. Essentially if you were to graph 2^y = x. It increases rapidly between x = 0 and x = 1, and y is negative. after x = 1, y is positive and the function increases very slowly.


State the problem
    How can we find a certain name in a book of n pages?
State the recursive abstraction
    Find the name in pages (mid to end) OR (beginning to mid)
Identify the parts of this solution that correspond to the six parts of a generalized recursive solution.
    Decision: Does nameOnPage.compareTo(targetName) == 0
    Base Case: If true: return the number of the current pages
    Recursive Case: If false:
        Check if nameOnPage.compareTo(targetName) < 0
        return the result of...
        If true: recursive abstraction mid to end
        Else: recursive abstraction beginning to mid

    
