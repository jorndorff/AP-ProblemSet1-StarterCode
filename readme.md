# Problem Set One

## Directions

Create a class named *ProblemSet1* which contains methods that solve the questions below. Also submit a test class, *Tests1*, with a main method that tests your Problem Set. Make sure you have enough test cases to thoroughly test each method including *edge cases*. You must have at least three tests per method.

## Grading

| Category      | Points |
| ------------- | ------ |
| Documentation | 2      |
| Functionality | 16     |
| Test Coverage | 2      |

| Deduction | Points |
| --------- | ------ |
|           |        |

## Problems

0. Write a method named createWedge that takes in a positive integer, and returns an array of type int which is filled with the values:   1, 2, …, n-1, n, n-1, …,2, 1 where n is the parameter to the method. 

1. Write a method named fibArray that take takes in an integer (n) which is greater than or equal to 2, and returns an array of the first n Fibonacci numbers. The first two elements should be equal to 1; each subsequent element should be equal to sum of the two previous ones.

   ​

2. Write a boolean method named isMedian that determines whether a given rational number is a median for values stored in an array. We called m a median if the number of elements that are greater than m is the same as the number of elements that are less than m. This method takes in  two parameters: an array of type double and a double.

3. (a) Write methods void `rotateLeft(int[] a)` and void `rotateRight(int[] a)` that rotate an array a by one position in the respective direction.
   ​
    (b) Write a method `public static void rotate(int[] a, int d)` that rotates an array by a given number of positions d. A positive d rotates the array to the right; a negative d, to the left. For example, if `a` holds elements `{1, 4, 9, 16, 25, 36}` after `rotate(a, -2)` the values in `a` are `{9, 16, 26, 36, 1, 4}`.

   ​

4. Create a method called convert that takes in an ArrayList of type Integer and returns the same values in an array of type int (Hint - you can rely on autounboxing to help do this).

   ​

5. Create a method called equalsIgnoreCase that takes in 2 ArrayLists of Strings and returns whether or not they contain identical values, ignoring the case of the Strings. (Note: you may not use String’s equalsIgnoreCase method.)

   ​

6. Create a method called top5 that takes in an array of type int and returns an ArrayList of type Integer that contains, in order from largest to smallest, the 5 largest values in the array. You may assume as a precondition that the length of the array is at least 5.

   ​

7. Create a method called getFirst that takes in an ArrayList of Strings and returns the String that comes first in alphabetical order (Hint - explore String’s compareTo method).

   ​

8. Create a method called replace that takes in an array of arrays of type char and replaces any character that is a digit with the character 'z'.

   ​

9. Create a method called multiply that takes in 2 arrays of arrays of type int and returns an array of arrays of type int that represents the result of multiplying these 2 matrices together. 
   If you're rusty on your matrix multiplication, a web search will yield many explanations and demos. You may assume the number of columns in the first parameter is equal to the number of rows in the second parameter.

