# Experiment No: 2 - Adding Two Complex Numbers

## AIM
To write a Python program for adding two complex numbers, and get the user input using the `eval()` function.

## ALGORITHM
1. Begin the program.
2. Use the `eval()` function to get two complex numbers as input from the user.
3. Print the complex numbers entered by the user.
4. Perform the addition of the two complex numbers using the `+` operator.
5. Print the sum of the two complex numbers.
6. Terminate the program.

## PROGRAM
```python
# Get user input for two complex numbers
A = eval(input())
B = eval(input())

# Print the complex numbers
print(f"A is {A}")
print(f"B is {B}")

# Add the complex numbers
sum_complex = A + B

# Print the sum
print(f"Sum is {sum_complex}")
```
## OUTPUT
Enter first complex number: (2+3j)
Enter second complex number: (1+4j)
A is (2+3j)
B is (1+4j)
Sum is (3+7j)

## RESULT
Thus the python program for  adding two complex numbers has been implemented and executed successfully.
