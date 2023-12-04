# Lab Report 5 - Putting It All Together 

## Part 1 - Debugging Scenario

Student:

![bug symptom](bug%20symptom.png)

I keep getting this error message and I don't know how to resolve it. 
The output from running the tests says `ListExamples.merge(ListExamples.java:44)`.
I think the bug could be somewhere in the method `merge` in one 
of the while loops. What do you think? 

TA: 

You're off to a good start! It's telling you to look inside the `merge` method 
and go to line 44. What do you think the bug is on that line?  


Student:

![bug fixed - tests pass](bug%20fixed%20-%20tests%20pass.png)

I got the program to work. While looking at line 44, I was able to see the bug,
so I fixed it and ran the tests and they were successful. In the third and final 
`while` loop in `merge`, the loop control variable `index2` needed to be updated, 
so instead of `index1 += 1;`, it should have been `index2 += 1;`. 

Info about setup: 

- The file & directory structure needed

  ```
    lab7/
      lib/
        hamcrest-core-1.3.jar
        junit-4.13.2.jar
      ListExamples.java
      ListExamplesTests.java
      test.sh
  ```

- The contents of each file before fixing the bug

  *ListExamples.java*

```
    import java.util.ArrayList;
    import java.util.List;

    interface StringChecker { boolean checkString(String s); }

    class ListExamples {

    // Returns a new list that has all the elements of the input list for which
    // the StringChecker returns true, and not the elements that return false, in
    // the same order they appeared in the input list;
    static List<String> filter(List<String> list, StringChecker sc) {
    List<String> result = new ArrayList<>();
    for(String s: list) {
    if(sc.checkString(s)) {
    result.add(0, s);
    }
    }
    return result;
    }
  
  
    // Takes two sorted list of strings (so "a" appears before "b" and so on),
    // and return a new list that has all the strings in both list in sorted order.
    static List<String> merge(List<String> list1, List<String> list2) {
    List<String> result = new ArrayList<>();
    int index1 = 0, index2 = 0;
    while(index1 < list1.size() && index2 < list2.size()) {
    if(list1.get(index1).compareTo(list2.get(index2)) < 0) {
    result.add(list1.get(index1));
    index1 += 1;
    }
    else {
    result.add(list2.get(index2));
    index2 += 1;
    }
    }
    while(index1 < list1.size()) {
    result.add(list1.get(index1));
    index1 += 1;
    }
    while(index2 < list2.size()) {
    result.add(list2.get(index2));
    // change index1 below to index2 to fix test
    index1 += 1;
    }
    return result;
    }
  
    
    }
```


  *ListExamplesTests.java*

```
    import static org.junit.Assert.*;
    import org.junit.*;
    import java.util.*;
    import java.util.ArrayList;
      
      
    public class ListExamplesTests {
    @Test(timeout = 500)
    public void testMerge1() {
    List<String> l1 = new ArrayList<String>(Arrays.asList("x", "y"));
    List<String> l2 = new ArrayList<String>(Arrays.asList("a", "b"));
    assertArrayEquals(new String[]{ "a", "b", "x", "y"}, ListExamples.merge(l1, l2).toArray());
    }
      	
    @Test(timeout = 500)
    public void testMerge2() {
    List<String> l1 = new ArrayList<String>(Arrays.asList("a", "b", "c"));
    List<String> l2 = new ArrayList<String>(Arrays.asList("c", "d", "e"));
    assertArrayEquals(new String[]{ "a", "b", "c", "c", "d", "e" }, ListExamples.merge(l1, l2).toArray());
    }
      
    }
```


  *test.sh*

    javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
    java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
 

- The full command line (or lines) you ran to trigger the bug

  I ran the command `bash test.sh`, which caused the bug to occur.
  This was the only command I ran. 

- A description of what to edit to fix the bug

  In *ListExamples.java*, in the third and final `while` loop in the method `merge`,
  the loop control variable `index2` needed to be updated, so instead of `index1 += 1;`,
  it should have been `index2 += 1;`. Remove the 1 from `index1` and type 2, so it's now
  `index2 += 1;` instead of `index1 += 1;`. This will fix the bug, and when you run the
  JUnit tests, all the tests will pass. 


## Part 2 - Reflection

I really enjoyed creating a grading script like Autograder to grade student submissions, 
that was cool to learn. I never knew how to do that and it was interesting
going through that process. 


