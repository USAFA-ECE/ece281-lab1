# ECE 281 Lab 1 Prelab

## Prelab questions

### Truth Table

| Month     | A | B | C | D | Y |
|-----------|---|---|---|---|---|
|           | 0 | 0 | 0 | 0 | X |
| January   | 0 | 0 | 0 | 1 | 1 |
| February  | 0 | 0 | 1 | 0 | 0 |
| March     | 0 | 0 | 1 | 1 | 1 |
| April     | 0 | 1 | 0 | 0 | 0 |
| May       | 0 | 1 | 0 | 1 | 1 |
| June      | 0 | 1 | 1 | 0 | 0 |
| July      | 0 | 1 | 1 | 1 | 1 |
| August    | 1 | 0 | 0 | 0 | 1 |
| September | 1 | 0 | 0 | 1 | 0 |
| October   | 1 | 0 | 1 | 0 | 1 |
| November  | 1 | 0 | 1 | 1 | 0 |
| December  | 1 | 1 | 0 | 0 | 1 |
|           | 1 | 1 | 0 | 1 | X |
|           | 1 | 1 | 1 | 0 | X |
|           | 1 | 1 | 1 | 1 | X |

### Boolean Equation

$$
Y = !AD + A!C!D + A!B!D
$$

### Digital Simulations

In this folder are also Digital templates for you to complete and simulate.  Do not change the file names or the input and output labels in Digital otherwise the autograder will not work.  The autograder will look in the prelab folder for the files.

Complete all three circuits using the various approaches (generic multiplexer symbol, 74151 multiplexer chip, and a sum of products using and/or logic gates).

You may also wish to run test cases.  The first two rows of the truth table have been added to the Digital simulation files as a test.  You may wish to edit the test to add more rows and fully cover all possible cases but this is not required.

## Submission

1. Make sure all prelab files are in this folder
2. Commit all files
3. Push to GitHub
4. Submit to Gradescope
5. Verify submission
