# Merge and Sort 2 Arrays (70! pts)

Complete the mergeArrays function which has two parameters-
array, a and array b. Both arrays contains m elements in non-decreasing order. The mergeArrays function should merge arrays a and b into a single, non-decreasing array of size 2m and then returns the merged array.

### Input Format

The first line of the input is an integer m, total number of elements in arrays a and b. Each of the next subsequent m lines contains a single integer, denoting the elements of array a. Then the next line of input is the integer m. Each of the next m lines contains a single integer, denoting the elements of array b.

### Output Format

Your function should return the merged array.

#### Sample Input 1

```
//The test will create two variables for you
  var a = [1,5,7,7];
  var b = [0,1,2,3];
  // Then it will call the function mergeArrays
  like this
  var result = mergeArrays(a,b);
  //the value of result should be = { 0, 1, 1, 2,
  3, 5, 7, 7 }
  //Don't forget to BABY STEP your way to the
  answer!
```

#### Sample Input 2

```
  //The test will create two variables for you
var a =  [ 2, 4, 6, 9, 9];
var b =  [ 0, 1, 2, 3, 5];
// Then it will call the function mergeArrays
like this
var result = mergeArrays(a,b);
//the value of result should be =  {0, 1, 2, 2,
3, 4, 4, 5, 9, 9}
//Don't forget to BABY STEP your way to the
answer!
```
