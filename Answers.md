##Question 1
*[What is the complexity of each of the four search methods in terms of array or list size n?]*

The first two search methods, findTeamPosition, are both of complexity **O(n)**. The linear search algorithm is of complexity **O(n)** as well. The final search method, the binary search, has the complexity **O(log(n))**.

##Question 2
*[What happens in the case of binary search if the array is not sorted?]*

With a binary search, it would not work as intended if the array is not sorted. This method ignores certain elements based on information that is inherent to sorted arrays. Without it being sorted, the potential answer may be one of the values that are skipped.

##Question 3
*[What is the purpose of constructor argument validity checking?]*

With argument validity checking, the program will still compile and methods can be called safely even if a null or invalid argument is passed in.

##Question 4
*[What is the purpose of using the keyword final with variables and arguments?]*

The "final" keyword helps prevent variables from being accidentally or inappropriately assigned new values. The compiler will give an error if a final variable is assigned a new value, letting you know that something must be incorrect. Without this keyword, the program would compile and, consequently, there would be less information about where the code's issues are located.

##Question 5
*[What are alternatives to using Optional and how do they compare?]*

Some alternatives to using Optional are to use "-1" and "null," for example. An important feature that Optional provides is the ability to return an empty object without using work around methods like the ones listed previously. The Optional implementation is less prone to errors and other problems that may arise from using null and negative indexes.