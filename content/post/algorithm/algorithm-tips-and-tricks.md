+++
authors = ["bataraga radu"]
date = 2020-09-20T21:00:00Z
excerpt = "You are given an algorithm problem. How do you proceed?"
hero = "/images/algorithm-preview.jpg"
timeToRead = 3
title = "Algorithm Tips and tricks"

+++
**You are given an algorithm problem. How do you proceed?**

Try finding a working solution, even if it's performance is low and optimize it. Atleast, you have something working. Even a brute-force.

**Do we need to use a recursive solution or iterative solution?**  
First you must ask yourself, how big is the input?  
By using recursion we use stack space so we are pretty limited when a big input is delivered. With iterative solution we can are free of charge, limited only by the RAM memory.

Maybe the iterative solution is harder to understand but it's not using that much memory because of the stack and the recursive solution is more straight-forward.

  
**Data structure operation complexity:**

Hashmap GET and PUT operations are complexity O(1)

String algorithms:  
We can create a Array of integers for each a-z letters for occurence. Or we can use a hashmap