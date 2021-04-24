# Part 1 Questions

## Part 1a

1. Line 9 prints: `values added: 20`
2. Line 13 prints: `final result: 20`
3. Line 9 prints: `values added: 20`
4. The code returns an error because `result` is not defined outside of the `if` statement.
5. The code returns an error because we are modifying `result` in line 7 after it was already set in line 5.
6. The code returns an error because we are modifying `result` in line 7 after it was already set in line 5.

## Part 1b

1. Line 12 will print the length of the `prices` array, 3.
2. Line 13 will print the final price in the `prices` array, but discounted by the amount specified (0.5), which turns out to be 150. This value has not been rounded to 2 decimal places.
3. Line 14 will print the final discounted price but rounded to no more than 2 decimal places (150).
4. This function returns the `prices` array passed in, but with prices discounted by the `discount` percentage given and rounded to 2 decimal places.
5. This code will cause an error because the variable `i` is not defined outside of the scope of the `for` loop due to the use of `let`.
6. This code will cause an error because the variable `discountedPrice` is not defined outside of the body of the `for` loop due to the use of `let`.
7. Line 14 will print the final price, but rounded to no more than 2 decimal places.
8. This function returns the `prices` array passed in, but with prices discounted by the `discount` percentage given.
9. This code will cause an error because the variable `i` is not defined outside of the scope of the `for` loop due to the use of `let`.
10. Line 12 will print the length of the `prices` array, 3.
11. This function will return the `prices` array passed in, but with prices discounted by the `discount` percentage given. Values in this array are not rounded to 2 decimal places.
12. Notation is below:

    A. Accessing the value of the name property in the student object

    ```js
    student.name
    ```

    B. Accessing the value of the Grad Year property in the student object

    ```js
    student.['Grad Year']
    ```

    C. Calling the function for the greeting property in the student object

    ```js
    student.greeting()
    ```

    D. Accessing the name property of the object in the Favorite Teacher property in student

    ```js
    student['Favorite Teacher'].name
    ```

    E. Access the first index in the array of the courseLoad property of the student object

    ```js
    student.courseLoad[0]
    ```

13. Arithmetic

    A. `32` is the output because the 3 is a string and the 2 is concatenated to it.

    B. `1` is the output because the 3 is converted to a number, and then 2 is subtracted to get 1.

    C. `3` is the output. The `null` is converted to a 0 and then added to 0, resulting in 3.

    D. `3null` is the output. The `null` is converted to the string "null" and then concatenated after the 3.

    E. `4` is the output. The `true` is converted to a 1 and then added to 3, resulting in 4.

    F. `0` is the output. The `false` is converted to 0 and the `null` is converted to a 0. These are added together to produce 0.

    G. `3undefined` is the output. The `undefined` is converted to the string "undefined" and then concatenated after the 3.

    H. `NaN` is the output. `undefined` is converted to `NaN` (not a number) which means the conversion failed and the operation could not be completed.

14. Comparison

    A. `true` is the output. The string `'2'` is converted to the number 2 and then 2 is greater than 1, hence the true.

    B. `false` is the output. This is a string comparison, so the strings are compared letter by letter. So the `'2'` in the first string is greater than the `'1'` in the second string lexicographically, hence the comparison is false.

    C. `true` is the output. The string `'2'` is converted to the number 2, so the comparison is true.

    D. `false` is the output. Since we are using strict equality, the equality is checked without type conversion. Since the types are different, this fails.

    E. `false` is the output. The `true` is converted to the number 1, which is not equal to 2.

    F. `true` is the output. The `Boolean` is an explicit boolean conversion. It will convert items to true unless they are one of 6 things that specifically convert to false, and the number 2 is not one of these.

15. The difference with `==` is that `==` performs type conversion before checking for equality, thus allowing for things like `2 == '2'` to return true as the string was converted to a number. However, `===` does not perform type conversion before checking for equality, so the types must match as well in order for the check to evaluate to true.
16. See [part1b-question16.js](part1b-question16.js).
17. A new array will be returned that has the contents of the original array, but multiplied by 2. With the given array `[1,2,3]` it will return an array with `[2,4,6]`.
18. See [part1b-question18.js](part1b-question18.js).
19. This code prints the numbers 1 4 3 2 in that order, each on their own line. There is a 1 second delay before 2 is printed, and 4 prints before 3 because the timeout does not have to be registered.
