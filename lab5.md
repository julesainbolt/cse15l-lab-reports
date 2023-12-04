# Lab Report 5 - Putting It All Together 

## Part 1 - Debugging Scenario

Student:

![bug symptom](bug%20symptom.png)

I keep getting this error message and I don't know how to resolve it. 
The output from running the tests says `ListExamples.merge(ListExamples.java:44)`.
I think the bug could be somewhere in the method `merge` in one 
of the while loops. What do you think? 

TA: 

You're off to a good start! It is telling you to look inside the `merge` method 
and go to line 44. What do you think the bug is on that line?  


Student:

![bug fixed - tests pass](bug%20fixed%20-%20tests%20pass.png)

I got the program to work. While looking at line 44, I was able to see the bug,
so I fixed it and ran the tests and they were successful. In the third and final 
`while` loop in `merge`, the loop control variable `index2` needed to be updated, 
so instead of `index1 += 1;`, it should have been `index2 += 1;`. 


## Part 2 - Reflection

